#### Test 575312431745da8_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3497/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3497/10027)
,--------- beginning of /dev/log/main
W/fb4a(:<default>):UserScope( 3497): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):UserScope( 3497): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3497/10027)
D/WIFI_ICON( 1118): WifiActivity: 3
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [16][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3497/10027)
E/fb4a(:<default>):LocalFbBroadcastManager( 3497): Called registerBroadcastReceiver twice.
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3497/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3497/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3497/10027)
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3790 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/Process (  906): killProcessQuiet, pid=3497
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3497:com.facebook.katana/u0a27 (adj 15): empty #17
E/cutils-trace( 3787): Error opening trace file: No such file or directory (2)
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3497
I/MusicStore( 3790): Database version: 95
D/WifiService(  906): Client connection lost with reason: 4
W/ContextImpl( 3790): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
W/ContextImpl( 3790): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/CheckinRequestBuilder( 2192): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2192): Failed to find provider info for com.google.android.wearable.settings
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3790): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3790): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3790): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
V/AlarmManager(  906): sending alarm PendingIntent{427ce940: PendingIntentRecord{42b82570 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1454592989220, Int=0
D/CustomizationManager( 3787): ====startRecUseTime====
D/htc.customization.log.level( 3787):  is 
W/CustomizationLogLevel( 3787): Level value is invalid, use default level 2
I/ActivityManager(  906): Killing 2872:com.android.defcontainer/u0a19 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=2872
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3790, uid=10154, userID:0
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
D/MediaRouterService(  906): Client com.google.android.music (pid 3790): Registered
I/MediaRouter( 3790): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
I/ActivityManager(  906): Recipient 2872
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/NetworkMonitor( 3790): type=WIFI subType= reason=null isConnected=true
D/TelephonyReceiver( 1245): bind: true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/CustomizationManager( 3787):  Read ACC file spent 0.075 (s)
D/CIDMapFileReader( 3787): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3787): Parsing tag item name = HTC__102
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.music (3790/10154)
D/CIDMapFileReader( 3787): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3787): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3787): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3787): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3787): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3787): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3787): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3787): Parsing tag item name = HTC__031
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
V/CustomizationCIDLoader( 3787): full path : /system/customize/CID/HTC__032.xml
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [3][0][0]
I/CustomizationCIDLoader( 3787): Parsing tag category name = system
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
I/CustomizationCIDLoader( 3787): Parsing tag category name = application
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/CustomizationCIDLoader( 3787): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3787): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3787): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3787): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3787): Parsing tag category name = Settings
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/CustomizationManager( 3787):  Read CID file spent 0.127 (s)
D/CustomizationManager( 3787):  All configurations done spent 0.128 (s)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
W/HtcNativeFlag( 3787): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3787): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3787): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3787): Fail to get flag for type 'language', use default value: -1
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
I/ActivityManager(  906): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3817 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
D/GenericMessagesProvider( 2165): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 2165): (14) cannot open file at line 30190 of [00bb9c9ce4]
E/SQLiteLog( 2165): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2192/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2192/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/HtcModeClient( 1513): handler message = 4011
E/HtcModeClient( 1513): Check connection and retry 5 times.
E/SQLiteConnection( 2165): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 2165): DB info: errno = 2, errno message = No such file or directory
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
E/SQLiteDatabase( 2165): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 2165): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 2165): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2165): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2165): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2165): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2165): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2165): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2165): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2165): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2165): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2165): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 2165): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 2165): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2165): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2165): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 2165): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 2165): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2165): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 2165): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 2165): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 2165): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 2165): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 2165): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 2165): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 2165): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 2165): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 2165): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 2165): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 2165): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 2165): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 2165): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 2165): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 2165): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err( 2165): 	at dalvik.system.NativeStart.run(Native Method)
D/TelephonyReceiver( 1245): switchBindHtcMsgCursor: null
D/PMS     (  906): releaseWL(42ce0e90): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/MediaRouter( 3790): getSelectedRoute
I/NetworkMonitor( 3790): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3790/10154)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/DFPI.PIReciver( 3817): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/DFPI.ApkInstallService( 3817): onHandleIntent
I/DFPI.ApkInstallService( 3817): Media Scan Finished Case 
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/DFPI.ApkInstallService( 3817): check CID = HTC__032
I/DFPI.ApkInstallService( 3817): There is no Demo.apk in sd card or phone storage
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3787
I/ActivityManager(  906): Resuming delayed broadcast
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3790, uid=10154, userID:0
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42bbabc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): releaseWL(42bbabc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/CheckinRequestBuilder( 2192): Classify the device as Phone.
I/ActivityManager(  906): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3835 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
D/Process (  906): killProcessQuiet, pid=3517
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3517:com.google.android.setupwizard/u0a79 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3517
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/CheckinTask( 2192): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2192): Checking schedule, now: 1454592989537 next: 1455115926528
I/CheckinService( 2192): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2192, uid=10029, userID:0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
I/ActivityManager(  906): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
D/CheckinService( 2192): Recording last checkin time for package unspecified as 1454592989559
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
D/PMS     (  906): releaseWL(42260c08): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3835/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3835/10053)
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{42afdc00 u0 ReceiverList{42b3c8a0 3835 com.htc.musicenhancer/10053/u0 remote:42b87900}}
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3835): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/PMS     (  906): releaseWL(429bedc0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=2192, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=2192, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=2192, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=2192, uid=10029, userID:0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.google.android.gms
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
D/AccTypeManager( 1345): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/Prism.ItemManager( 3636): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 3636): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
W/AccTypeManager( 1345): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1345): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
W/Prism.AllAppsManager( 1273): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
E/ExternalAccountType( 1345): Unsupported attribute readOnly
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3856 uid=10081 gids={50081, 5001, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3530
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3530:com.android.chrome/u0a96 (adj 15): empty #17
,I/SoundPicker( 3856): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3856): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3856): SoundPickerReceiver [onReceive] startService
I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/SoundPicker( 3856): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3856): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3856): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3856): MODE_GSM access default DB
,I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
,D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
,I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
,I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3856): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3856): MODE_GSM access default DB
,I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/ActivityManager(  906): Recipient 3530
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/AutoSetting( 1327): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1327): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1327): service - requestNLP() NetworkLocationProvider not enabled
,W/PackageManager(  906): Unable to load service info ResolveInfo{42cdb108 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/GCoreNlp( 1223): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  906): acquireWL(42d3d288): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d3d288): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d3f268): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d3f268): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  906): applying state to connected service
,D/LocationProviderProxy(  906): applying state to connected service
,D/PMS     (  906): acquireWL(42d49670): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): releaseWL(42d49670): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d4aef8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/DFPI.PIReciver( 3817): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3817): onHandleIntent
,I/DFPI.ApkInstallService( 3817): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3817): check CID = HTC__032
,I/DFPI.ApkInstallService( 3817): There is no Demo.apk in sd card or phone storage
D/PMS     (  906): releaseWL(42d4aef8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/GAV2    ( 3549): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 2192): Google Analytics 8.4.89 is starting up.
,I/Prism.ItemManager( 3636): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3636): loadItems() com.htc.launcher.pageview.WidgetManager@42132e30 +
,I/Prism.WidgetManager( 3636): onLoadItems() +
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@42154c70 +
,I/Prism.WidgetManager( 1273): onLoadItems() +
,E/Prism.WidgetManager( 1273): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1273): onLoadItems() -
,I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@42154c70 -
,I/Prism.WidgetManager( 3636): onLoadItems() -
,I/Prism.ItemManager( 3636): loadItems() com.htc.launcher.pageview.WidgetManager@42132e30 -
,D/Process (  906): killProcessQuiet, pid=3358
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  906): killProcessQuiet, pid=3549
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3358:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
I/ActivityManager(  906): Killing 3549:com.google.android.apps.magazines/u0a151 (adj 15): empty #18
,I/ActivityManager(  906): Recipient 3358
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SocialFeedProvider( 1273): +disConnect socialManager
,I/SocialFeedProvider( 1273): disconnect socialManager
,I/SocialFeedProvider( 1273): -disConnect socialManager
,I/ActivityManager(  906): Recipient 3549
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3374
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3374:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/SoundPicker( 3856): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3856): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/ActivityManager(  906): Recipient 3374
,I/SoundPicker( 3856): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 3856): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3856): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3856): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3856): MODE_GSM access default DB
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3856): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3856): MODE_GSM access default DB
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lil,ac.flac
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
D/PhoneApp( 1245): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1245): -- N1 =0
I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
D/PhoneApp( 1245): -- N2 =0
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/PhoneApp( 1245): -- N3 =0
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,V/AlarmManager(  906): sending alarm PendingIntent{428f0b08: PendingIntentRecord{42383610 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1454592992911, Int=0
,I/SocialManager[SocialBiLogHelper]( 3636): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3636): last commit ulog time 1454578885926
,I/SocialManager[SocialBiLogHelper]( 3636): skip commit this time
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  906): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3885 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/DFPI.PIReciver( 3817): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3817): onHandleIntent
,I/DFPI.ApkInstallService( 3817): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3817): check CID = HTC__032
,I/DFPI.ApkInstallService( 3817): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/EASAppSvc( 3885): [ NA ]- onCreate()
,I/EASAppSvc( 3885): [ NA ]> onUpgrade: version = 63
,D/ORMLib  ( 3436): put()
,I/EASAppSvc( 3885): [ NA ]- onDestroy()
,I/EASAppSvc( 3885): [ NA ]> uninitEASService
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.android.mail (3885/10064)
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.htc.android.mail (3885/10064)
,D/ConnectivityService(  906): getNetworkInfo networkType=55 called by com.htc.android.mail (3885/10064)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97,
,D/WifiNative-wlan0(  906):    returned true
,I/EASRequestController( 3885): [ NA ]release
,I/EASAppSvc( 3885): [ NA ]< uninitEASService
,I/EASAppSvc( 3885): [ NA ]- onCreate()
,I/EASAppSvc( 3885): [ NA ]> onUpgrade: version = 63
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.android.mail (3885/10064)
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.htc.android.mail (3885/10064)
D/ConnectivityService(  906): getNetworkInfo networkType=55 called by com.htc.android.mail (3885/10064)
,D/ORMLib  ( 3436): put()
,I/EASAppSvc( 3885): [ NA ]- onDestroy()
,I/EASAppSvc( 3885): [ NA ]> uninitEASService
,I/EASRequestController( 3885): [ NA ]release,
,I/EASAppSvc( 3885): [ NA ]< uninitEASService
I/ActivityManager(  906): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3917 uid=10068 gids={50068, 3003, 5012}
,D/Process (  906): killProcessQuiet, pid=3653
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3653:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3653
,D/ORMLib  ( 3436): put()
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/AlarmManager(  906): sending alarm PendingIntent{421acaf8: PendingIntentRecord{42aba128 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=60327, Int=0
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3669
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/SoundPicker( 3856): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  906): Killing 3669:com.htc.mobiledata/u0a91 (adj 15): empty #17
,W/ContextImpl( 3856): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3856): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3856): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3856): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3856): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3856): MODE_GSM access default DB
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3856): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3856): MODE_GSM access default DB
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/ActivityManager(  906): Recipient 3669
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3790): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/HtcModeClient( 1513): handler message = 4011
,E/HtcModeClient( 1513): Check connection and retry 6 times.
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/DFPI.PIReciver( 3817): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 3817): onHandleIntent
,I/DFPI.ApkInstallService( 3817): Media Scan Finished Case 
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,D/DFPI.ApkInstallService( 3817): check CID = HTC__032
,I/DFPI.ApkInstallService( 3817): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42ccde30 u0 com.google.android.gms/.gcm.GcmService}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/SoundPicker( 3856): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3856): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3856): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3856): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3856): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3856): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3856): MODE_GSM access default DB
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3856): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3856): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3856): MODE_GSM access default DB
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3856): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3856): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3856): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3856): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3790): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(42c255a8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1513 10014 null
I/ActivityManager(  906): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  906): releaseWL(42c255a8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
D/TelephonyReceiver( 1245): bind: false
D/TelephonyReceiver( 1245): switchBindHtcMsgCursor: null
,I/ActivityManager(  906): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3947 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=31 rxSum=27} preTxRxSum={txSum=0 rxSum=0}
,D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20294 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20295 delay=15s
I/ActivityManager(  906): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=3960 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/PMS     (  906): acquireWL(42b83a00): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42b83a00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/GAV2    ( 3960): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  906): acquireWL(42b01478): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{4299a108: PendingIntentRecord{4291e168 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1454592995424, Int=0
,D/PMS     (  906): releaseWL(42b01478): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Delaying start of: ServiceRecord{429c8b20 u0 com.google.android.gms/.icing.service.IndexWorkerService}
,D/PMS     (  906): acquireWL(423c4000): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(423c4000): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/NotificationService(  906): notification sound not played, stream=5 volume=0 always=false
D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
I/RemoteViews( 1118): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{421238c8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.updater 1 7 1 10
,D/Process (  906): killProcessQuiet, pid=3603
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/RemoteViews( 1118): com.htc.updater (true,33751552)
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3603:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,I/Gmail   ( 3960): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{423d7c20 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/[PluginManager]RegisterService( 1327): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1327): handle notify Blinkfeed plugin client changed
,I/RemoteViews.Performance( 1118): com.htc.updater 2 8 1 10
,I/Gmail   ( 3960): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/Gmail   ( 3960): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/IcingCorporaProvider( 2821): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
,I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/Gmail   ( 3960): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/PMS     (  906): acquireWL(42966530): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42966530): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428d6ca8): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Recipient 3603
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(428d6ca8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42b2ef18): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42b2ef18): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428b5688): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(428b5688): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  906): mEventCount = 451
D/PMS     (  906): acquireWL(429c6ca8): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(429c6ca8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42c52a68): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42c52a68): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42c962d8): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42c962d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42af38d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42af38d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3999 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/PMS     (  906): acquireWL(42ac7680): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42ac7680): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42aa21f0): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
D/PMS     (  906): releaseWL(42aa21f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2821): UpdateCorporaTask done [took 377 ms] updated apps [took 376 ms] 
,D/PMS     (  906): acquireWL(42a63400): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3999 10160 null
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(42db8360): PARTIAL_WAKE_LOCK  AsyncService 0x1 3999 10160 null
,D/PMS     (  906): acquireWL(42db46e8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3999 10160 null
,D/PMS     (  906): releaseWL(42a63400): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  906): releaseWL(42db8360): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Resuming delayed broadcast
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3999/10160)
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4027 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3999/10160)
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): releaseWL(42db46e8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/Process (  906): killProcessQuiet, pid=3686
,I/ActivityManager(  906): Killing 3686:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/dalvikvm( 4027): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4027, uid=10074, userID:0
,D/Settings:HtcWirelessFeatureFlags( 3711): id/is att sku: 99/false
,W/SystemReader( 3711): Cannot find devicepolicy_lower_fp_quality, use default value instead
,D/Finsky  ( 4027): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4027/10074)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
W/SystemReader( 3711): Cannot find support_harman, use default value instead
,W/SystemReader( 3711): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 3711): no such activity!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:59, mTXpacketCount:37, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3711): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3711): updateDevelopment, bPrefShow = true
I/ActivityManager(  906): Recipient 3686
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
,E/Settings:HtcUmcWidgetEnabler( 3711): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3711): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3711): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3711): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3711): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3711): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3711): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3711): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3711): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3711): [supportHomeButton]support         :false
,W/dalvikvm( 4027): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/FingerprintManager( 3711): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 3711): isSupportVoWifi: null
,W/dalvikvm( 4027): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3711): Failed to find provider info for com.htc.vowifi
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4027/10074)
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3711): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3711): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3711): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3711): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3711): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3711): [supportRecentAppsButton]support         :false
,D/Finsky  ( 4027): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4027): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3711): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3711): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3711): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3711): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3711): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3711): [supportHomeButton]support         :false
,W/FingerprintManager( 3711): hasFingerprint() - sSensorCode = 0
,W/Settings( 4027): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4027): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Settings:HtcVoWifiWidgetEnabler( 3711): isSupportVoWifi: null
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3711): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 4027): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4027): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4027): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4027): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4027, uid=10074, userID:0
,D/Ads     ( 4027): Skipping gmscore version check
,D/Finsky  ( 4027): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4027): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4027): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 4027): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 4027): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Process (  906): killProcessQuiet, pid=3742
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3742:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3742
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PackageBroadcastService( 2192): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4065 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/PMS     (  906): acquireWL(42ba4660): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42ba4660): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42b83610): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,I/Babel   ( 4065): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4065): MmsConfig.loadMmsSettings
,W/dalvikvm( 4065): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 2192): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2192): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,W/dalvikvm( 4065): VFY: unable to resolve instance field 36
W/dalvikvm( 4065): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 2192): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2192): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2192): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2192): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
W/dalvikvm( 2192): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
V/JNIHelp ( 4065): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2192, uid=10029, userID:0
D/MmsCustomizationProvider( 2165): query uri: content://htc-mms-customization/mms-ua/ua_string
D/MmsCustomizationProvider( 2165): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4065): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 4065): MmsConfig.loadFromDatabase
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4065, uid=10111, userID:0
,I/PeopleDatabaseHelper( 2192): cleanUpNonGplusAccounts done.
,W/Settings( 4065): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Babel   ( 4065): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4065): MmsConfig.loadFromResources
E/Babel   ( 4065): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4065): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4065, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4065, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4065, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4065, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4065, uid=10111, userID:0
D/PMS     (  906): acquireWL(42948e10): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4065 10111 null
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 4065): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  906): releaseWL(42948e10): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(429e4ac0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4065 10111 null
,I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  906): releaseWL(429e4ac0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3725
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Killing 3725:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
D/PMS     (  906): acquireWL(427978d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
I/ActivityManager(  906): Recipient 3725
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,D/PMS     (  906): releaseWL(427978d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(42aa4f58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,D/PMS     (  906): releaseWL(42aa4f58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2192/10029)
,D/PMS     (  906): acquireWL(42ba4d68): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
D/PMS     (  906): acquireWL(42a6ab50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42a6ab50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,D/PMS     (  906): releaseWL(42ba4d68): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(42d049e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  906): releaseWL(42d049e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42a5c5f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42a5c5f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42c774c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42c774c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(42255940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/PMS     (  906): releaseWL(42255940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42c90408): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4111 uid=10041 gids={50041}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(42c90408): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  906): killProcessQuiet, pid=3583
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3583:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,D/PMS     (  906): acquireWL(42c2f398): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3436 10071 null
,D/PMS     (  906): acquireWL(42542988): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3436 10071 null
,I/ActivityManager(  906): Delay finish: com.htc.task/.notification.NotifyReceiver
,E/TodoTaskNotifyService( 3436): java.lang.NullPointerException
,W/System.err( 3436): java.lang.NullPointerException
W/System.err( 3436): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3436): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3436): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3436): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3436): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3436): stopSelfResult true
D/PMS     (  906): releaseWL(42c2f398): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  906): releaseWL(42542988): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(42c1fc58): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42c1fc58): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  906): acquireWL(42c45748): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4065 10111 null
,I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  906): releaseWL(42c45748): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/WearableService( 1223): callingUid 10029, callindPid: 1223
,D/LocationInitializer( 2192): Restart initialization of location
D/AuthorizationBluetoothService( 1361): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1361): Proximity feature is not enabled.
,E/MDM     ( 1223): [105] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  906): Resuming delayed broadcast
W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
D/PMS     (  906): acquireWL(42bb04c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42bb04c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  906): Resuming delayed broadcast
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
I/WSP     ( 1327): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1327): Weather sync is On
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
I/ActivityManager(  906): Recipient 3583
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WSP     ( 1327): [Receiver] next auto-sync alarm event is 60 mins later, at time: Thu Feb 04 15:36:37 CET 2016
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1327/10055)
I/ActivityManager(  906): Delay finish: com.google.android.gsf/.settings.GoogleLocationSettings$LocationSettingsChangedListener
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1327/10055)
D/PMS     (  906): acquireWL(42c03bf8): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1327 10055 null
,V/AlarmManager(  906): sending alarm PendingIntent{42a8c2a8: PendingIntentRecord{42a9d840 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1454592997205, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42a4df80: PendingIntentRecord{42a766a8 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1454592997252, Int=0
I/iu.UploadsManager( 2192): End new media; added: 0, uploading: 0, time: 50 ms
,I/Icing   ( 2192): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2192): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  906): releaseWL(42b83610): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Resuming delayed broadcast
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2192/10029)
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): acquireWL(42c92638): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4065 10111 null
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  906): releaseWL(42c92638): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1327): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1327): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/IcingCorporaProvider( 2821): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  906): acquireWL(42cb8e98): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42cb8e98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d78068): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d78068): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d738f8): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d738f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42caadd8): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42caadd8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42c66e50): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42c66e50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42dca680): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42dca680): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42db46e8): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42db46e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d6af68): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d6af68): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d67378): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d67378): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d647a0): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d647a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2821): UpdateCorporaTask done [took 373 ms] updated apps [took 373 ms] 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(42d35120): PARTIAL_WAKE_LOCK  AsyncService 0x1 3999 10160 null
,D/PMS     (  906): releaseWL(42d35120): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PackageBroadcastService( 2192): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2192): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,I/Icing   ( 2192): updateResources: need to parse f{com.google.android.gms}
D/PMS     (  906): acquireWL(42ce60c0): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,W/MediaManager( 3763): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3763): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/TodoTaskshortcut( 3436): update TASK shortcut>
,I/Icing   ( 2192): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,W/SQLiteConnectionPool( 2192): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/Icing   ( 2192): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2192): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  906): releaseWL(42ce60c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/HtcModeClient( 1513): handler message = 4011
,E/HtcModeClient( 1513): Check connection and retry 7 times.
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2192, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2192, uid=10029, userID:0
,I/CheckinService( 2192): Done disabling old GoogleServicesFramework version
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2192, uid=10029, userID:0
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/GAV2    ( 3960): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 4065): Thread[GAThread,5,main]: No campaign data found.
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/Process (  906): killProcessQuiet, pid=3636
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3636:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3636
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/CalendarProvider2( 1513): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1513): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/WIFI_ICON( 1118): WifiActivity: 1
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(42a0ab00): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(429daea0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
D/PMS     (  906): releaseWL(42a0ab00): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(429daea0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/MediaManager( 3763): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(42db8360): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3790 10154 null
I/ActivityManager(  906): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3790): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3790, uid=10154, userID:0
,W/ContextImpl( 3790): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/PMS     (  906): releaseWL(42db8360): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 3790): Conditions not met for autocaching.
,I/MusicLeanback( 3790): Stop autocaching.
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4170 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4170): Loading default preferences
,W/Resources( 4170): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  906): New client listening to asynchronous messages
,D/SyncApplication( 4170): Overriding preferences with custom values
,D/SyncApplication( 4170): Updating preferences succeeded
,E/SyncApplication( 4170): Application created.
D/VolumeInfo( 4170): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4170): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
,V/VolumeInfo( 4170): Found 0 mount point(s)
,V/VolumeInfo( 4170): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4170): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4170): getNewCalendarAuthority()...
,D/VolumeInfo( 4170): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 4170): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4170): enableAppOperation()+
,D/SyncApplication( 4170): enableAppOperation()-
,D/HTCUtilities( 4170): isNeorSinged() + 
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4170, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4170, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4170): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4170): isNeorSinged() return false
,D/CDMountReceiver( 4170): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4170): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,I/RemoteViews( 1118): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{423fee40 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/CDMountReceiver( 4170): enable CD Auto-mount: true
I/RemoteViews.Performance( 1118): com.nero.android.htc.sync 1 7 3 11
,I/RemoteViews( 1118): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{42400610 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/HTCUtilities( 4170): enable auto-mount
,D/HTCUtilities( 4170): enable auto-mount
I/ActivityManager(  906): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,I/RemoteViews.Performance( 1118): com.nero.android.htc.sync 0 7 3 16
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): releaseWL(42c9b398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3763): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  906): killProcessQuiet, pid=3885
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3885:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,D/PMS     (  906): acquireWL(42b775d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42b775d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42bcb848): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,D/PMS     (  906): releaseWL(42bcb848): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Recipient 3885
D/WifiService(  906): Client connection lost with reason: 4
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42aab508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
,I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4192 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(42aab508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/CalendarApplication( 4192): onCreate
D/ProviderChangeReceiver( 4192): ---------------------------------------------------
,D/ProviderChangeReceiver( 4192): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4192): start to updateAlertNotification!
,D/Process (  906): killProcessQuiet, pid=3917
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4206 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Killing 3917:com.htc.task.gtask/u0a68 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3917
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AlertService( 4192): No fired or scheduled alerts
,D/HtcAlertUtils( 4192): -- cancelReminderNotification --
,D/HtcAlertUtils( 4192): broadcastExistReminder!
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4206): [4206/4206] onCreate()
W/ContextImpl( 4206): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3817
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  906): Killing 3817:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3817
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1513): handler message = 4011
,E/HtcModeClient( 1513): Check connection and retry 8 times.
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42c11a30 u0 com.htc.musicenhancer/.EnhancerService}
,D/PMS     (  906): acquireWL(42992648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42992648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/SensorManager(  906): mEventCount = 600
,D/PMS     (  906): releaseWL(42c03bf8): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/HtcModeClient( 1513): handler message = 4011
,E/HtcModeClient( 1513): Check connection and retry 9 times.
,D/Finsky  ( 4027): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4027): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  906): acquireWL(42c11ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
V/AlarmManager(  906): sending alarm PendingIntent{429943f8: PendingIntentRecord{42c3f200 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454593009609, Int=0
D/PMS     (  906): releaseWL(42c11ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (4027/10074)
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4027): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4027): [NET] getaddrinfo-,err=8
D/libc    ( 4027): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4027): [NET] getaddrinfo-, 1
D/libc    ( 4027): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =ecb3 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET][SMD] Cache EXPIRED (STALE ENTRY 0xb82acea0 DISCARDED) or need renew
,D/libc    (  364): [NET] entry_id:5   entry:0xb82acea0  removed 
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 277
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4027): [NET] getaddrinfo_proxy-, success
,I/global  ( 4027): call createSocket() return a new socket.
D/libc    ( 4027): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4027): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4027): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4027): [NET] getaddrinfo-,err=8
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4027): untagSocket(69) failed with errno -22
,D/Finsky  ( 4027): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/WIFI_ICON( 1118): WifiActivity: 3
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=52 rxSum=47} preTxRxSum={txSum=31 rxSum=27}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20295 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20296 delay=15s
D/PMS     (  906): acquireWL(42cca418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{42a95c10: PendingIntentRecord{42a145e8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=76583, Int=0
D/PMS     (  906): releaseWL(42cca418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/NetworkManagementSocketTagger( 4027): untagSocket(69) failed with errno -22
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=8 [24][2][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:85, mTXpacketCount:59, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,W/NetworkManagementSocketTagger( 4027): untagSocket(69) failed with errno -22
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.android.vending (4027/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4027/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4027/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4027/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4027/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4027/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4027/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4027/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4027/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4027/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4027/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4027/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4027/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4027/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4027/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4027/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4027/10074)
,D/Finsky  ( 4027): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  906): acquireWL(42cb2e38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
,V/AlarmManager(  906): sending alarm PendingIntent{42cc1160: PendingIntentRecord{42cfc070 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1454593011760, Int=0
,D/WearableService( 1223): callingUid 10029, callindPid: 1223
D/PMS     (  906): acquireWL(42ccd280): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4027 10074 null
,D/PMS     (  906): releaseWL(42cb2e38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
D/Finsky  ( 4027): [430] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/DeviceConnectionService( 1223): client connected with version: 8296000
D/Finsky  ( 4027): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 4027): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4027): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4027): [NET] getaddrinfo-,err=8
D/libc    ( 4027): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4027): [NET] getaddrinfo-, 1
,D/libc    ( 4027): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8fec +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=87
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4027): [NET] getaddrinfo_proxy-, success,
,D/PMS     (  906): releaseWL(42ccd280): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=7 [53][4][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/HtcModeClient( 1513): handler message = 4011
,E/HtcModeClient( 1513): Check connection and retry 10 times.
,D/AutoSetting( 1327): service - mHandler: update timezone
,D/AutoSetting( 1327): service - handleMessage() stop self
,D/AutoSetting( 1327): service - handleMessage() quit looper
,D/AutoSetting( 1327): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=3856
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3856:com.htc.sdm/u0a81 (adj 15): empty #17
,D/AutoSetting( 1513): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1513): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1513): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1513): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1513): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1513): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1513): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1513): service - mHandler: update timezone
,D/AutoSetting( 1513): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1513): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1513): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1513): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1554): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1118): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{424ab768 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.htclocationservice 2 7 2 11
,I/ActivityManager(  906): Recipient 3856
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=100 [1][1][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/SensorManager(  906): mEventCount = 750
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1513): handler message = 4011
,E/HtcModeClient( 1513): Check connection and retry 11 times.
,D/PMS     (  906): acquireWL(42dab3f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=86293, Int=0
,D/PMS     (  906): releaseWL(42dab3f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1118): now=1454593020060 next=59940
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/HtcModeClient( 1513): handler message = 4011
,E/HtcModeClient( 1513): Check connection and retry 12 times.
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  906): acquireWL(42d63060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=106 rxSum=98} preTxRxSum={txSum=52 rxSum=47}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20296 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20297 delay=15s
V/AlarmManager(  906): sending alarm PendingIntent{42cc7b60: PendingIntentRecord{42a145e8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=91587, Int=0
D/PMS     (  906): releaseWL(42d63060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  906): acquireWL(42dcaf60): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42dcaf60): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42da9ed0): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42da9ed0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42dca680): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42dca680): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d78478): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d78478): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d67418): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d67418): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:144, mTXpacketCount:85, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/HtcModeClient( 1513): handler message = 4011
,E/HtcModeClient( 1513): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1513): Don't start project servcice
,D/HtcModeClient( 1513): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1513): connectState: CONNECTION_READY = false
,D/SilentMusic( 1513): call stop
,D/HtcModeClient( 1513): close connection
,W/HtcModeClient( 1513): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1513): read the terminate packet, so break
,D/PMS     (  906): acquireWL(42d323f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
,V/AlarmManager(  906): sending alarm PendingIntent{42cae610: PendingIntentRecord{42a5b730 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454593026085, Int=0
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4240 uid=10078 gids={50078}
,V/AlarmManager(  906): sending alarm PendingIntent{429fe120: PendingIntentRecord{429f4d28 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454593030195, Int=60000
,D/PMS     (  906): releaseWL(42d323f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4240): SMSBackupAgentService started
,D/SMSBackup( 4240): Checking restore status
,D/SMSBackup( 4240): Restore complete
,D/SMSBackup( 4240): cancelCheckAlarm
,D/SMSBackup( 4240): SMSBackupAgentService completed: completed in 0.0 seconds
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,D/Finsky  ( 4027): [419] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4027): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  906): killProcessQuiet, pid=3947
,I/ActivityManager(  906): Killing 3947:com.htc.updater/u0a85 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 3947
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42cf8398 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,V/LightsService(  906): setLight #0: color=#3f
,V/LightsService(  906): setLight #0: color=#3b
,V/LightsService(  906): setLight #0: color=#35
,V/LightsService(  906): setLight #0: color=#2e
,V/LightsService(  906): setLight #0: color=#27
,V/LightsService(  906): setLight #0: color=#21
,V/LightsService(  906): setLight #0: color=#1a
,V/LightsService(  906): setLight #0: color=#14
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true,
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@427ae068
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@427ae068, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4292d2b8
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@4297e590
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  906): mWirelessDisplayManager is null
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =6f13 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/PMS     (  906): acquireWL(42c1e698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428c3e48: PendingIntentRecord{4294d6e8 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=106126, Int=0
,D/libc    (  906): [NET] getaddrinfo_proxy-, success
D/PMS     (  906): releaseWL(42c1e698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 328ms
,W/PnPMgr  (  357): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
D/NfcService( 1255): ScreenObserver: OFF
,D/NfcService( 1255): applyRouting - 0
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42a59a18)
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
I/InputMethodManagerService(  906): Disable input method client, pid=1273
D/PMN     (  906): wakingUp
,D/PMS     (  906): acquireWL(42b0dda0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/NfcService( 1255): applyRouting -2
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/WindowManager(  906): No lock screen! windowToken=null
D/PMS     (  906): releaseWL(42b0dda0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  906): acquireWL(42c4a2f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
D/PMN     (  906): onScreenOn
D/PMS     (  906): releaseWL(42c4a2f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,I/IntentController( 1118): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/MtpService( 2723): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1255): applyRouting - 0
,D/MtpService( 2723): [MTP][onReceive]-
,D/NfcService( 1255): applyRouting -2
,D/AutoSetting( 1327): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  906): acquireWL(42a5a190): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMS     (  906): releaseWL(42a5a190): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/TetherSettings( 3711): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3711): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3711): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3711): Cust_ConnectToPC   : spcsc>false
D/        ( 3711): Cust_ConnectToPC   : IPT>true
D/        ( 3711): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3711): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3711): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3711): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3711): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
D/AutoSetting( 1327): service - onCreate()
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20298 delay=15s
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
,I/PSReceiver( 3711): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1327): service - AddressCache: using context: com.htc.Weather
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): SET_SCREEN_ON:On
I/wpa_supplicant( 1185): htc_wext_set_keepalive +
I/wpa_supplicant( 1185): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1185): getPrivFuncNum +	
I/wpa_supplicant( 1185): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,I/SmartNS_PSService( 3711): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3711): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3711):  defaultType:0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,W/ContextImpl( 3711): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  906): mEventCount = 900
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/AutoSetting( 1327): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
I/ClockThread( 1118): stop update clock
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:145, mTXpacketCount:144, avgLinkspeed:72,mAvgTxRate72
D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/LocationManagerService(  906): request 42bbeee8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
D/WIFI_ICON( 1118): WifiActivity: 2
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  375): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
D/NetworkPolicy(  906): updateScreenOn: false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4264 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  906): acquireWL(42c93e98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42c93e98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42c96098): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42c96098): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1746): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1746): onScreenOn: 1454593040375
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1746): onScreenOn: 1454593040375
W/ContextImpl( 4264): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4292d2b8
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4292d2b8, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@4297e590
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(42dab9e0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,I/FeedHostManager( 1273): [onPause]
,I/FeedProviderManager( 1273): onPause
,D/SmartSyncUtils( 4264): isEpsOn(), nState = 0
I/SocialFeedProvider( 1273): +onPause
,I/SocialFeedProvider( 1273): -onPause
,D/PMS     (  906): acquireWL(42c45018): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4264 1000 null
,I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@421cd4e8
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20298 mDataStallAlarmIntent=PendingIntent{42c39798: PendingIntentRecord{42a145e8 android broadcastIntent}}
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): SET_SCREEN_ON:Off
I/wpa_supplicant( 1185): htc_wext_set_keepalive +
I/wpa_supplicant( 1185): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1185): getPrivFuncNum +	
I/wpa_supplicant( 1185): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1185): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1185): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1185): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  375): ParamSet string: screen_state=off
D/PMS     (  906): acquireWL(42c58da0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
D/PMS     (  906): releaseWL(42dab9e0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/PMS     (  906): releaseWL(42c45018): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/NetworkPolicy(  906): updateScreenOn: false
,D/ContactMessageStore( 1245): start background delete task...
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4264): getMobilePolicyEnabled, result = true
,W/ContextImpl( 4264): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4264): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4264): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4264): isEpsOn(), nState = 0
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4297e590
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/WifiService(  906): New client listening to asynchronous messages
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4297e590, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4297e590, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4297e590
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424b7e98 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424b7e98 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/DotMatrix( 1554): [EventService] getTotalRam: 1873 Mb
D/PMS     (  906): releaseWL(42c58da0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/PMS     (  906): acquireWL(42da5310): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42da5310): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42d3ff30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42d3ff30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1746): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1746): onScreenOff
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1746): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1746): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1746): onScreenOff
,D/AutoSetting( 1327): service - mHandler: cancel location update
,D/AutoSetting( 1327): service -           changes count: 0
,D/AutoSetting( 1513): service - handleMessage() stop self
,D/AutoSetting( 1513): service - onDestroy() END
,D/AutoSetting( 1513): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=2165
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2165:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2165
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=3835
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3835:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3835
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42d37f98 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  906): acquireWL(42d30720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
D/PMS     (  906): releaseWL(42d30720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(42d692e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{42579f98: PendingIntentRecord{42c54c58 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123192, Int=0
,D/PMS     (  906): releaseWL(42d692e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42cd43f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(42c6c670): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42c6c670): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42cd43f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42c3a5b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,D/PMS     (  906): releaseWL(42c3a5b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42c9cea8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42dc96d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ChimeraCfgMgr( 2192): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2192): Loading module APK com.google.android.play.games
,D/PMS     (  906): acquireWL(42da82f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42c9cea8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 2192): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 2192): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
,W/dalvikvm( 2192): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,W/dalvikvm( 2192): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,I/GamesSyncServiceMain( 2192): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 2192): Failed to execute periodic sync, missing client context - aborting
D/PMS     (  906): releaseWL(42dc96d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42c7bae0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,D/PMS     (  906): releaseWL(42c7bae0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d7ab40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(42da82f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d7ab40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d81600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,D/PMS     (  906): releaseWL(42d81600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42dc2f40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42dc2f40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42dc0038): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42d41100): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1223): Vacuum at: now=1454593057727 tag=VacuumService
,D/PMS     (  906): acquireWL(42d48378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d41100): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42dc0038): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d48378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d55dc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,D/PMS     (  906): releaseWL(42d55dc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d59df8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,D/PMS     (  906): releaseWL(42d59df8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d5dc40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(42d5dc40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d93cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42d93cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42d95540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{425a6df0: PendingIntentRecord{42b98968 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136839, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
,D/PMS     (  906): releaseWL(42d95540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d98488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,D/PMS     (  906): acquireWL(42da11e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1327): service - handleMessage() stop self
,D/AutoSetting( 1327): service - handleMessage() quit looper
,D/AutoSetting( 1327): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=4111
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4111:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4111
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(42d98488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1223): Scheduling Phenotype for one-off execution 12623 seconds from now (1454593071001)
,D/GetConfigurationSnapshotOperation( 1223): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1223): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1223): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
,D/libc    ( 1223): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =adf4 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8,
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=10 [10][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(42da11e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42df9b48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,D/PMS     (  906): releaseWL(42df9b48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42e00660): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,D/PMS     (  906): releaseWL(42e00660): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42e084c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42927d70: PendingIntentRecord{429272a8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141747, Int=0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(42e097c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(42e084c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =bb54 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): acquireWL(42e3cc00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=146293, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e3cc00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): releaseWL(42e097c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42e43038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10027}
,V/AlarmManager(  906): sending alarm PendingIntent{42549b30: PendingIntentRecord{42b70b90 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=172822, Int=0
,D/PMS     (  906): releaseWL(42e43038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1245): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(42e45318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e45318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42e46b70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=206293, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e46b70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =cffb +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo_proxy-, success,
D/PMS     (  906): acquireWL(42e492e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{428c3e48: PendingIntentRecord{4294d6e8 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=186130, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4315 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{42a5ddd0: PendingIntentRecord{42a53808 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454593146101, Int=10800000
,D/PMS     (  906): releaseWL(42e492e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10049}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,I/IntentController( 1118): receive(android.intent.action.TIME_SET,4,false)
,D/DotMatrix( 1554): [EventService] EVENT_RESET_THEME_TIMESTAMP
,I/FeedActionBar( 1273): updateLastUpdatedTime(in String) LAST UPDATED 14:36
,D/DotMatrix( 1554): [EventService] isTheSameDay:false,timestamp is early than today:true
,D/AlertReceiver( 4192): beginStartingService
D/PMS     (  906): acquireWL(42e557f0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 4192 10013 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4315/10049)
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4332 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,D/AlertService( 4192): start to updateAlertNotification!
,W/WeatherRequest( 1118): request cur loc, but there is no sys cur
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,D/AlertService( 4192): No fired or scheduled alerts
,D/HtcAlertUtils( 4192): -- cancelReminderNotification --
,D/HtcAlertUtils( 4192): broadcastExistReminder!
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AlertReceiver( 4192): stopSelfResult true
D/PMS     (  906): releaseWL(42e557f0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,D/Process (  906): killProcessQuiet, pid=4065
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4065:com.google.android.talk/u0a111 (adj 15): empty #17
,D/PMS     (  906): acquireWL(42e655f0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3436 10071 null
,D/PMS     (  906): acquireWL(42e65da8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3436 10071 null
,D/PMS     (  906): releaseWL(42e655f0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  906): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4350 uid=10090 gids={50090, 3003, 5012, 1028}
,D/TodoTaskshortcut( 3436): update TASK shortcut>
,I/TodoTaskNotifyService( 3436): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/WeatherUtility( 4332): can't get weather sync account
,I/TodoTaskNotifyService( 3436): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 3436): stopSelfResult true
D/PMS     (  906): releaseWL(42e65da8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/WeatherRequest( 4332): request cur loc, but there is no sys cur
,W/Settings( 4332): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1273): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1273): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  906): Recipient 4065
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WorldClock.Global( 4350): isHtcDevice = true
,I/RemoteViews.Performance( 1273): com.htc.widget.weatherclock 2 12 17
,I/WorldClock.Global( 4350): isHtcDevice = true
W/ContextImpl( 4206): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 4350): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmUtils( 4350): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 4350): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/ActivityManager(  906): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4366 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/IntentController( 1118): receive(android.intent.action.ALARM_CHANGED,1,false)
,D/Process (  906): killProcessQuiet, pid=3999
,I/ActivityManager(  906): Killing 3999:com.google.android.apps.plus/u0a160 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 3999
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TimeService( 4366): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454593146542
,D/PMS     (  906): acquireWL(42cfe850): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2192 10029 WorkSource{10029 com.google.android.gms},
,D/PMS     (  906): acquireWL(42cf35d8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42cfe850): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2192): Checkin interval check for package: unspecified last checkin: 1454592989559 min interval config: 0 actual interval: 157055
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,D/PMS     (  906): releaseWL(42cf35d8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42ce68e0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 2192 10029 null
,D/PMS     (  906): acquireWL(42ce4828): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,D/PMS     (  906): releaseWL(42ce68e0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/Process (  906): killProcessQuiet, pid=3790
D/PMS     (  906): releaseWL(42ce4828): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Killing 3790:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/PMS     (  906): acquireWL(42c8a580): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3436 10071 null
,D/PMS     (  906): acquireWL(42c730f0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3436 10071 null
,E/TodoTaskNotifyService( 3436): java.lang.NullPointerException
,W/System.err( 3436): java.lang.NullPointerException
W/System.err( 3436): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3436): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3436): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3436): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3436): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  906): releaseWL(42c8a580): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  906): acquireWL(42c65f90): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3436 10071 null
,D/PMS     (  906): releaseWL(42c730f0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 3436): stopSelfResult true
D/PMS     (  906): acquireWL(42c5b670): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3436 10071 null
,E/TodoTaskNotifyService( 3436): java.lang.NullPointerException
W/System.err( 3436): java.lang.NullPointerException
W/System.err( 3436): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
,W/System.err( 3436): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3436): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3436): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3436): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3436): stopSelfResult true
D/PMS     (  906): releaseWL(42c65f90): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  906): releaseWL(42c5b670): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  906): Recipient 3790
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  906): Client com.google.android.music (pid 3790): Died!
,D/Process (  906): killProcessQuiet, pid=4170
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4170:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4170
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,D/ContactMessageStore( 1245): notify MmsSms
,D/AccFlag ( 1245): sense_version=6.0
,D/AccFlag ( 1245): sku_id=99
D/PMS     (  906): acquireWL(42c18ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029}
V/AlarmManager(  906): sending alarm PendingIntent{42c1e730: PendingIntentRecord{42b0ac20 com.google.android.gms startService}}, i=com.google.android.gms.icing.proxy.action.SMS_CHANGED, t=2, cnt=1, w=5000, Int=0
D/PMS     (  906): releaseWL(42c18ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 64
,D/AccFlag ( 1245): sku_id=99
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 63
,D/AccFlag ( 1245): sku_id=99
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 64
,D/AccFlag ( 1245): sku_id=99
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 63
,D/AccFlag ( 1245): sku_id=99
,D/PMS     (  906): acquireWL(42bdcfa8): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42bdcfa8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42bc85d8): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.android.phone ] tid: 38
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4388 uid=10041 gids={50041}
,D/SMSBackup( 4240): Got a database change event
,I/Icing   ( 2192): Indexing 9EC334276810E6DA9F550691EDBF16BE1CDE9A62 from com.google.android.gms
,I/Icing   ( 2192): Indexing done 9EC334276810E6DA9F550691EDBF16BE1CDE9A62
D/PMS     (  906): releaseWL(42bc85d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  906): killProcessQuiet, pid=3763
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3763:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3763
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4292c668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10014}
,V/AlarmManager(  906): sending alarm PendingIntent{4269e5c8: PendingIntentRecord{42e553c8 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=217479, Int=0
,D/PMS     (  906): acquireWL(4239a460): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1513 10014 null
,D/PMS     (  906): releaseWL(4292c668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10014}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,D/PMS     (  906): releaseWL(4239a460): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(42a8d730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42a8d730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(428d2220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{421acaf8: PendingIntentRecord{42aba128 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=242297, Int=0
,D/PMS     (  906): acquireWL(42b51e80): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42c92bb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(428d2220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=17 [58][10][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(42cf24b0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 906 1000 WorkSource{10160}
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=4403 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0],
,D/PMS     (  906): acquireWL(42e3c460): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 906 1000 WorkSource{10029}
,D/PMS     (  906): releaseWL(42b51e80): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(42c92bb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42c89068): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42c89068): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42d71cd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42d71cd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,D/PMS     (  906): acquireWL(42d13a30): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4403 10160 null
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360242618
,W/AlarmManager(  906): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{42a194e8: PendingIntentRecord{42b85e10 com.google.android.gms startService}}) : type=2 triggerAtTime=315360242618 win=-1 tElapsed=315360242618 maxElapsed=551880242615 interval=0 standalone=false
,D/PMS     (  906): acquireWL(42c858d0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4403 10160 null
,D/PMS     (  906): releaseWL(42d13a30): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4403/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4403/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42d69870): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42d69870): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(42c858d0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42c62938): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42cf24b0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
,D/PMS     (  906): releaseWL(42c62938): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/Process (  906): killProcessQuiet, pid=3960
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3960:com.google.android.gm/u0a107 (adj 15): empty #17
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42d3eb60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42e3c460): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  906): releaseWL(42d3eb60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  906): Recipient 3960
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(42d29af8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42d29af8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(42d3be80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=266581, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42d3be80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42d2fa48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{421acaf8: PendingIntentRecord{42aba128 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=272442, Int=0
,D/PMS     (  906): acquireWL(42e09d28): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42d2fa48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42e623c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(42db3360): PARTIAL_WAKE_LOCK  *sync*/com.htc.showme/com.htc.showme/***** 0x1 906 1000 WorkSource{10083}
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Start proc com.htc.showme for service com.htc.showme/.sync.SyncService: pid=4430 uid=10083 gids={50083, 3003, 5012, 1028, 1015}
D/PMS     (  906): acquireWL(42b9cc08): PARTIAL_WAKE_LOCK  *sync*/subscribedfeeds/com.google/***** 0x1 906 1000 WorkSource{10029}
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42e09d28): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(42e623c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42d4bc00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(42d4bc00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42d6f3e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42d6f3e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42e3d898): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42e3d898): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,I/[AppShowMeDebug]SyncAdapter( 4430): onPerformSync() 
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.showme (4430/10083)
,I/GoogleURLConnFactory( 2192): Using platform SSLCertificateSocketFactory
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,I/[AppShowMeDebug]CheckUpdateTask( 4430): check and download urlSKUBased = http://showme.htctouch.com/prod/LU15A_CTH=401/; urlDeviceBased = http://showme.htctouch.com/prod/LU15A_CTH/; urlSKUTestDeviceBased = http://showme-test.htc.com.tw/testpub/LU15A_CTH=401/; urlTestDeviceBased = http://showme-test.htc.com.tw/testpub/LU15A_CTH/
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 2192): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2192): [NET] getaddrinfo-,err=8
D/libc    ( 2192): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2192): [NET] getaddrinfo-, 1
,D/libc    ( 2192): [NET] getaddrinfo_proxy+
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8eef +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 2192): [NET] getaddrinfo_proxy-, success
D/libc    ( 4430): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 4
D/libc    ( 4430): [NET] getaddrinfo-,err=8
D/libc    ( 4430): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 1024
D/libc    ( 4430): [NET] getaddrinfo-, 1
,D/libc    ( 4430): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =1fc0 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL,
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5,
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5,
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [4][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=246
D/libc    (  364): [NET]res_queryN: exit 3, ancount=6
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4430): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0],
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50,
I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/libc    ( 2192): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4,
,D/libc    ( 2192): [NET] getaddrinfo-,err=8
,D/libc    ( 2192): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2192): [NET] getaddrinfo-,err=8,
,D/libc    ( 4430): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 4
D/libc    ( 4430): [NET] getaddrinfo-,err=8
D/libc    ( 4430): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 1024
D/libc    ( 4430): [NET] getaddrinfo-, 1
,D/libc    ( 4430): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =4da7 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=6
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4430): [NET] getaddrinfo_proxy-, success,
,I/[AppShowMeDebug]SyncAdapter( 4430): Sync task finished
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42d2c2a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [11][0][0]
,D/PMS     (  906): releaseWL(42db3360): PARTIAL_WAKE_LOCK  *sync*/com.htc.showme/com.htc.showme/***** 0x1 WorkSource{10083}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL,
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(42c4ffa8): PARTIAL_WAKE_LOCK  *sync*/gmail-ls/com.google/***** 0x1 906 1000 WorkSource{10107}
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=4459 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
D/PMS     (  906): releaseWL(42d2c2a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0,
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42d1f4f8): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d1f4f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/GAV2    ( 4459): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42d526a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): acquireWL(42e40c10): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d526a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/Gmail   ( 4459): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4459): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/PMS     (  906): releaseWL(42e40c10): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42e6c770): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,I/Gmail   ( 4459): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4459): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gm (4459/10107)
,I/Gmail   ( 4459): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 16257, normalSync: true
,D/PMS     (  906): releaseWL(42e6c770): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4459): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 4459): [NET] getaddrinfo-,err=8
D/libc    ( 4459): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4459): [NET] getaddrinfo-, 1
,D/libc    ( 4459): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =cf95 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4459): [NET] getaddrinfo_proxy-, success
,I/global  ( 4459): call createSocket() return a new socket.
D/libc    ( 4459): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4459): [NET] getaddrinfo-, SUCCESS
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42e3a070): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42b9cc08): PARTIAL_WAKE_LOCK  *sync*/subscribedfeeds/com.google/***** 0x1 WorkSource{10029}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [8][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [4][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL,
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0,
,D/PMS     (  906): acquireWL(42bd0400): PARTIAL_WAKE_LOCK  *sync*/com.android.calendar/com.google/***** 0x1 906 1000 WorkSource{10108},
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=4492 uid=10108 gids={50108, 3003, 5012}
,D/PMS     (  906): releaseWL(42e3a070): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    ( 4459): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 4459): [NET] getaddrinfo-,err=8
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
W/AbstractGoogleClient( 4492): Application name is not set. Call Builder#setApplicationName.
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(429a8210): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(429a8210): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1361): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1361): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
,W/dalvikvm( 1361): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,W/dalvikvm( 1361): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1361): [NET] getaddrinfo-, 1
,D/libc    ( 1361): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =c004 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1361): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
,D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
,D/libc    ( 4492): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4492): [NET] getaddrinfo-,err=8
D/libc    ( 4492): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4492): [NET] getaddrinfo-, 1
,D/libc    ( 4492): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =f228 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=86
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4492): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [23][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(42b29628): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/,WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/CalendarSyncAdapter( 4492): Found 0 events marked dirty & lastSynced
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(42b29628): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42dc2f60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/Process (  906): killProcessQuiet, pid=4027
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42bd0400): PARTIAL_WAKE_LOCK  *sync*/com.android.calendar/com.google/***** 0x1 WorkSource{10108}
,I/ActivityManager(  906): Killing 4027:com.android.vending/u0a74 (adj 15): empty #17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNativ,e-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(42c28c80): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts/com.google/***** 0x1 906 1000 WorkSource{10029}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  906): releaseWL(42dc2f60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42d86c60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42d86c60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4027
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gm (4459/10107)
,I/Gmail   ( 4459): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 16321, normalSync: true
,I/Gmail   ( 4459): lowestBackward conversation id 0
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  906): acquireWL(42e68f80): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42e68f80): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42cc21b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1361): [NET] getaddrinfo-, 1
D/libc    ( 1361): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =4071 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1361): [NET] getaddrinfo_proxy-, success
,I/global  ( 1361): call createSocket() return a new socket.
D/libc    ( 1361): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-, SUCCESS
D/PMS     (  906): releaseWL(42c4ffa8): PARTIAL_WAKE_LOCK  *sync*/gmail-ls/com.google/***** 0x1 WorkSource{10107}
,D/Process (  906): killProcessQuiet, pid=4264
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  906): killProcessQuiet, pid=3711
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
I/ActivityManager(  906): Killing 4264:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Killing 3711:com.android.settings/1000 (adj 15): empty #18
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
,D/PMS     (  906): acquireWL(42e440c8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.plus.action/com.google/***** 0x1 906 1000 WorkSource{10029}
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(42cc21b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNativ,e-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3711
D/WifiService(  906): Client connection lost with reason: 4
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4264
,W/BaseAppContext( 2192): Using Auth Proxy for data requests.
,W/BaseAppContext( 2192): Using Auth Proxy for data requests.
,W/BaseAppContext( 2192): Using Auth Proxy for data requests.
,W/BaseAppContext( 2192): Using Auth Proxy for data requests.
,W/BaseAppContext( 2192): Using Auth Proxy for data requests.
,D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
,W/BaseAppContext( 2192): Using Auth Proxy for data requests.
,W/BaseAppContext( 2192): Using Auth Proxy for data requests.
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42caba58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42caba58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42d471a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42e440c8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.plus.action/com.google/***** 0x1 WorkSource{10029}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [9][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(42d99480): PARTIAL_WAKE_LOCK  *sync*/com.google.android.videos.sync/com.google/***** 0x1 906 1000 WorkSource{10165}
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=4525 uid=10165 gids={50165, 3003, 5012, 1028, 1015, 3002}
,D/PMS     (  906): releaseWL(42d471a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.videos (4525/10165)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42d81228): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42c28c80): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts/com.google/***** 0x1 WorkSource{10029}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185),: send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  906): acquireWL(42d6f558): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.cloudprint.cloudprintprovider/com.google/***** 0x1 906 1000 WorkSource{10097},
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PlayMovies( 4525): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50,
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50,
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  906): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=4545 uid=10097 gids={50097, 3003, 5012, 1028}
,D/PMS     (  906): releaseWL(42d81228): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50,
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,V/com.google.android.apps.common.multidex.Tracer( 4545): Checking if extracted archive /data/data/com.google.android.apps.cloudprint/files/secondary0.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4545): Extracted file last modified: Aug 23, 2015 4:22:5.0
V/com.google.android.apps.common.multidex.Tracer( 4545): Package last updated: Nov 17, 2014 15:54:26.0
,V/com.google.android.apps.common.multidex.Tracer( 4545): Checking if extracted archive /data/data/com.google.android.apps.cloudprint/files/secondary1.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4545): Extracted file last modified: Aug 23, 2015 4:22:5.0
V/com.google.android.apps.common.multidex.Tracer( 4545): Package last updated: Nov 17, 2014 15:54:26.0
,V/com.google.android.apps.common.multidex.Tracer( 4545): Attempting to patch the classloader using the following patchers [com.google.android.apps.common.multidex.KlpClassLoaderExtender@420d5718, com.google.android.apps.common.multidex.IcsClassLoaderExtender@420d6488, com.google.android.apps.common.multidex.PreIcsClassLoaderExtender@420d67e0]
,V/com.google.android.apps.common.multidex.Tracer( 4545): Trying com.google.android.apps.common.multidex.KlpClassLoaderExtender@420d5718.
,V/com.google.android.apps.common.multidex.Tracer( 4545): Patching was successful.
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/MediaRouterService(  906): Client com.google.android.videos (pid 4525): Registered
,D/PMS     (  906): acquireWL(42d1dd00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42d1dd00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,I/MediaRouter( 4525): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/ActivityManager(  906): Start proc com.google.android.apps.cloudprint for content provider com.google.android.apps.cloudprint/.printdialog.database.CloudPrintContentProvider: pid=4567 uid=10097 gids={50097, 3003, 5012, 1028}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.videos (4525/10165)
D/PlayMovies( 4525): MediaRouteManager.maybeRestoreRoute:188 sessionRestore routeId: 
,D/PlayMovies( 4525): MediaRouteManager.onRouteSelected:149 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,V/com.google.android.apps.common.multidex.Tracer( 4567): Checking if extracted archive /data/user/0/com.google.android.apps.cloudprint/files/secondary0.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4567): Extracted file last modified: Aug 23, 2015 4:22:5.0
V/com.google.android.apps.common.multidex.Tracer( 4567): Package last updated: Nov 17, 2014 15:54:26.0
,V/com.google.android.apps.common.multidex.Tracer( 4567): Checking if extracted archive /data/user/0/com.google.android.apps.cloudprint/files/secondary1.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4567): Extracted file last modified: Aug 23, 2015 4:22:5.0
V/com.google.android.apps.common.multidex.Tracer( 4567): Package last updated: Nov 17, 2014 15:54:26.0
,D/PlayMovies( 4525): TransferService.onCreate:52 creating transfer service
V/com.google.android.apps.common.multidex.Tracer( 4567): Attempting to patch the classloader using the following patchers [com.google.android.apps.common.multidex.KlpClassLoaderExtender@420d9b98, com.google.android.apps.common.multidex.IcsClassLoaderExtender@420da908, com.google.android.apps.common.multidex.PreIcsClassLoaderExtender@420dac60]
,V/com.google.android.apps.common.multidex.Tracer( 4567): Trying com.google.android.apps.common.multidex.KlpClassLoaderExtender@420d9b98.
,V/com.google.android.apps.common.multidex.Tracer( 4567): Patching was successful.
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42c4ecc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42c4ecc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.videos (4525/10165)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.videos (4525/10165)
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=com.google.android.videos.pinning.TransferService$Receiver, state=1, flag=1, pid=4525, uid=10165, userID:0
W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/MediaRouter( 4525): getSelectedRoute
V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PlayMovies( 4525): MediaRouteManager.onRouteAdded:140 new route added android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE
,D/PlayMovies( 4525): MediaRouteManager.onRouteSelected:149 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4525): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.videos/files/Movies
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.videos (4525/10165)
,D/PMS     (  906): acquireWL(42d9f2a0): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.videos (4525/10165)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.videos (4525/10165)
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=com.google.android.videos.pinning.TransferService$Receiver, state=2, flag=1, pid=4525, uid=10165, userID:0
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360242618
,D/PMS     (  906): releaseWL(42d9f2a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42e30a98): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1361): [NET] getaddrinfo-, 1
,D/libc    ( 1361): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =1962 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1361): [NET] getaddrinfo_proxy-, success
,D/PMS     (  906): releaseWL(42e30a98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1361): [NET] getaddrinfo-, 1
D/libc    ( 1361): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3e06 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1361): [NET] getaddrinfo_proxy-, success
D/PMS     (  906): acquireWL(42e1b138): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
,D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/PMS     (  906): releaseWL(42e1b138): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42e1cf60): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
,D/PMS     (  906): releaseWL(42e1cf60): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/PMS     (  906): acquireWL(42e1ea00): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42e1ea00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 4545): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4545): [NET] getaddrinfo-,err=8
,D/libc    ( 4545): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4545): [NET] getaddrinfo-, 1
D/libc    ( 4545): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =54b7 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 81
D/libc    (  364): [NET]res_nsend:resplen=48
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4545): [NET] getaddrinfo_proxy-, success
,I/PlayMovies( 4525): SyncService.syncAllPurchasesAndWishlist:149 Starting sync for 515013DC511638B0584069811EF28701C0771BF5
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4525): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4525): [NET] getaddrinfo-,err=8
D/libc    ( 4525): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4525): [NET] getaddrinfo-, 1
,D/libc    ( 4525): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =4bd0 +++++
,D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4525): [NET] getaddrinfo_proxy-, success
,I/global  ( 4525): call createSocket() return a new socket.
D/libc    ( 4525): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4525): [NET] getaddrinfo-, SUCCESS
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PlayMovies( 4525): SyncService.waitForCompletion:175 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 purchases
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PlayMovies( 4525): SyncService.waitForCompletion:175 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 wishlist
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42e6c838): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42d99480): PARTIAL_WAKE_LOCK  *sync*/com.google.android.videos.sync/com.google/***** 0x1 WorkSource{10165}
,D/Process (  906): killProcessQuiet, pid=4315
,I/ActivityManager(  906): Killing 4315:com.htc.aurora/u0a49 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/AccTypeManager( 1345): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=4 [45][2][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.backuptransport (1566/10029)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Recipient 4315
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1345): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1345): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv, error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(42c49760): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.magazines/com.google/***** 0x1 906 1000 WorkSource{10151}
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/ExternalAccountType( 1345): Unsupported attribute readOnly
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
I/ActivityManager(  906): Start proc com.google.android.apps.magazines for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService: pid=4592 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
D/PMS     (  906): releaseWL(42e6c838): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42be08e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data mis,sing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(42be08e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNativ,e-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4592): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4592): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4592): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4592): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4592): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42deea48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42d6f558): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.cloudprint.cloudprintprovider/com.google/***** 0x1 WorkSource{10097}
,D/Process (  906): killProcessQuiet, pid=1327
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  906): killProcessQuiet, pid=4192
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 1327:com.htc.sense.hsp/u0a55 (adj 15): empty #17
,I/ActivityManager(  906): Killing 4192:com.htc.calendar/u0a13 (adj 15): empty #18
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Recipient 4192
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): env,ironment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(42d493d8): PARTIAL_WAKE_LOCK  *sync*/com.htc.cloudstorage.drive.db/com.google/***** 0x1 906 1000 WorkSource{10069}
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL,
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
I/ActivityManager(  906): Start proc com.htc.cloudstorage.drive for service com.htc.cloudstorage.drive/.SyncService: pid=4611 uid=10069 gids={50069, 3003, 5012, 1028, 1015}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4592/10151)
,D/PMS     (  906): releaseWL(42deea48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
V/WebViewChromiumFactoryProvider( 4592): Binding Chromium to main looper Looper (main, tid 1) {420c4088}
I/LibraryLoader( 4592): Expected native library version number "",actual native library version number ""
I/chromium( 4592): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4592): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4592): BLUETOOTH permission is missing!
D/PMS     (  906): acquireWL(42c920a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 375 1013 null
D/PMS     (  906): acquireWL(42dfa698): PARTIAL_WAKE_LOCK  AudioMix 0x1 375 1013 null
D/PMS     (  906): releaseWL(42c920a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4592): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4592): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4592): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4592): Local Branch: 
I/Adreno-EGL( 4592): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4592): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4592):                  aa63bbd948f41d15fc72f585e
I/ActivityManager(  906): Recipient 1327
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/NSApplication( 4592): Starting up...
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42cfaba8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,I/SyncAdapterService( 4592): Ignoring sync request for non-current account
D/PMS     (  906): releaseWL(42cfaba8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/CloudStorageManager( 4611): [getInstance] googledrive version: 6
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42e51990): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4592/10151)
,I/ActivityManager(  906): Start proc com.htc.sense.hsp for content provider com.htc.sense.hsp/.opensense.pluginmanager.PluginProvider: pid=4642 uid=10055 gids={50055, 1023, 3003, 5012}
,D/Process (  906): killProcessQuiet, pid=4332
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  906): releaseWL(42c49760): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.magazines/com.google/***** 0x1 WorkSource{10151}
,I/ActivityManager(  906): Killing 4332:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4332,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50,
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
I/GAV2    ( 4459): Thread[GAThread,5,main]: No campaign data found.
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5,
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(42c84ae8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 906 1000 WorkSource{10096}
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  906): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4656 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/PMS     (  906): releaseWL(42e51990): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42c6f048): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/DelayedSyncController( 4656): Delaying sync.
D/PMS     (  906): releaseWL(42c6f048): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42e61880): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PluginProvider( 4642): PluginProvider onCreate
,D/Process (  906): killProcessQuiet, pid=4350
D/PMS     (  906): releaseWL(42c84ae8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,I/ActivityManager(  906): Killing 4350:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PluginProvider( 4642): current plugin count: 18
,D/HtcAppUPService( 4642): HtcUPDataProvider onCreate()
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Recipient 4350
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): acquireWL(42e383e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.docs/com.google/***** 0x1 906 1000 WorkSource{10100}
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  906): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=4671 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0,
D/PMS     (  906): releaseWL(42e61880): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42d140d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/Process (  906): killProcessQuiet, pid=4206
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Killing 4206:com.android.settings:remote/1000 (adj 15): empty #17
D/PMS     (  906): releaseWL(42d140d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  906): Recipient 4206
,W/MyGoogleDrive( 4611): [4683][GoogleDriveThreadedSyncAdapter] [onPerformSync]*Sync ABORT* Account not found(never cached)
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/Process (  906): killProcessQuiet, pid=4366
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42cdaec8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42d493d8): PARTIAL_WAKE_LOCK  *sync*/com.htc.cloudstorage.drive.db/com.google/***** 0x1 WorkSource{10069}
,I/ActivityManager(  906): Killing 4366:com.qualcomm.timeservice/1000 (adj 15): empty #17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  906): Recipient 4366
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(42e20f88): PARTIAL_WAKE_LOCK  *sync*/com.htc.task.dm/com.google/***** 0x1 906 1000 WorkSource{10068}
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=4684 uid=10068 gids={50068, 3003, 5012}
D/PMS     (  906): releaseWL(42cdaec8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42d4f868): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42d4f868): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42c9a578): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42e20f88): PARTIAL_WAKE_LOCK  *sync*/com.htc.task.dm/com.google/***** 0x1 WorkSource{10068}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/TodoTaskshortcut( 3436): update TASK shortcut>
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(42db4e10): PARTIAL_WAKE_LOCK  *sync*/com.google.android.location.reporting/com.google/***** 0x1 906 1000 WorkSource{10029}
,D/PMS     (  906): releaseWL(42c9a578): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/Process (  906): killProcessQuiet, pid=4388
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4388:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
I/ActivityManager(  906): Recipient 4388
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(42d2e8c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42d2e8c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,W/BaseAppContext( 1223): Using Auth Proxy for data requests.
,E/BaseAppContext( 1223): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4671/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4671/10100)
,W/GAV2    ( 4671): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/PMS     (  906): acquireWL(42dbf260): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42dbf260): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(42cce160): PARTIAL_WAKE_LOCK  SyncManager 0x1 4671 10100 null
,D/WifiService(  906): acquireWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@42cce7c0}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42e12660): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(42e12660): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1361): [NET] getaddrinfo-, 1
D/libc    ( 1361): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =cabb +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1361): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 4671): [NET] getaddrinfo+,hn 15(0x73736c2e677374),sn(),family 0,flags 4
D/libc    ( 4671): [NET] getaddrinfo-,err=8
D/libc    ( 4671): [NET] getaddrinfo+,hn 15(0x73736c2e677374),sn(),family 0,flags 1024
D/libc    ( 4671): [NET] getaddrinfo-, 1
D/libc    ( 4671): [NET] getaddrinfo_proxy+,
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x73736c2e677374),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
D/libc    (  364): [NET] +++++ res_nsend xid =f64a +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4,
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 1361): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 12
D/libc    (  364): [NET]res_nsend:resplen=49
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4671): [NET] getaddrinfo_proxy-, success
I/global  ( 4671): call createSocket() return a new socket.
D/libc    ( 4671): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4671): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
,D/libc    ( 1223): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3843 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1223): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
,D/libc    ( 4671): [NET] getaddrinfo+,hn 15(0x646f63732e676f),sn(),family 0,flags 4
D/libc    ( 4671): [NET] getaddrinfo-,err=8
D/libc    ( 4671): [NET] getaddrinfo+,hn 15(0x646f63732e676f),sn(),family 0,flags 1024
D/libc    ( 4671): [NET] getaddrinfo-, 1
,D/libc    ( 4671): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x646f63732e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =1f07 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=49
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4671): [NET] getaddrinfo_proxy-, success
I/global  ( 4671): call createSocket() return a new socket.
D/libc    ( 4671): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4671): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
,I/GCoreUlr( 1223): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1223): DispatchingService.onCreate()
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42e41460): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=2 [44][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(42db4e10): PARTIAL_WAKE_LOCK  *sync*/com.google.android.location.reporting/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42c78668): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 906 1000 WorkSource{10029}
,D/PMS     (  906): releaseWL(42e41460): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42d1d418): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42d1d418): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(42d2afb8): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42e36140): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(42c78668): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/PMS     (  906): acquireWL(421c8fe0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.reminders/com.google/***** 0x1 906 1000 WorkSource{10029}
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(42e36140): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/GCoreUlr( 1223): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1223): Unbound from all location providers
,I/GCoreUlr( 1223): Place inference reporting - stopped
D/PMS     (  906): acquireWL(42c9d058): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42c9d058): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d2afb8): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42d82a18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
I/GCoreUlr( 1223): DispatchingService.onDestroy()
,I/GCoreUlr( 1223): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1223): Unbound from all location providers
,I/GCoreUlr( 1223): Place inference reporting - stopped
D/PMS     (  906): releaseWL(42d82a18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  906): acquireWL(42dd79c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42dd79c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42e5bc78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=3 [30][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(421c8fe0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.reminders/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(42d340a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 906 1000 WorkSource{10029}
D/PMS     (  906): releaseWL(42e5bc78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42d09ba8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42d09ba8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/Auth.Api.Credentials( 2192): [CredentialSyncAdapter] Unknown sync event.
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42a153a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42d340a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(42532258): PARTIAL_WAKE_LOCK  *sync*/com.android.calendar/com.google/***** 0x1 906 1000 WorkSource{10108}
,D/PMS     (  906): releaseWL(42a153a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(424a76f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(424a76f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4671/10100)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4671/10100)
,W/GAV2    ( 4671): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/WifiService(  906): releaseWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@42cce7c0}
D/PMS     (  906): releaseWL(42cce160): PARTIAL_WAKE_LOCK  SyncManager 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42b1a978): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42e383e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.docs/com.google/***** 0x1 WorkSource{10100}
D/PMS     (  906): releaseWL(42b1a978): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,V/CalendarSyncAdapter( 4492): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2017-02-23T00:00:00.000Z, updatedMin=2015-11-18T16:31:02.459Z}
,D/CalendarSyncAdapter( 4492): Found 0 events marked dirty & lastSynced
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42af6498): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42532258): PARTIAL_WAKE_LOCK  *sync*/com.android.calendar/com.google/***** 0x1 WorkSource{10108}
,D/PMS     (  906): releaseWL(42af6498): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/Process (  906): killProcessQuiet, pid=4240
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4240:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4240
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(42dfa698): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,V/PeopleApp( 1345): Start ReQuery PreLoadCursor
,I/PeopleApp( 1345): Preload all people cursor with - displayOnlyPhones: false
,I/GAV2    ( 4592): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2192/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2192/10029)
,I/GAV2    ( 4671): Thread[GAThread,5,main]: No campaign data found.
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.google.android.videos
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1345): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1273): AllAppsMgr addApps, already exist: ApplicationInfo(id=24, title=Play Movies & TV, componentNameComponentInfo{com.google.android.videos/com.google.android.youtube.videos.EntryPoint} appsContainer=<ALLAPPS>)
,I/[PluginManager]RegisterService( 4642): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.videos
,I/[PluginManager]RegisterService( 4642): handle notify Blinkfeed plugin client changed
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,W/AccTypeManager( 1345): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1345): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
,I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsUpdated
,I/IcingCorporaProvider( 2821): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
D/PMS     (  906): acquireWL(42d61398): PARTIAL_WAKE_LOCK  AsyncService 0x1 4403 10160 null
,I/ActivityManager(  906): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=4758 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,E/ExternalAccountType( 1345): Unsupported attribute readOnly
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
D/PMS     (  906): releaseWL(42d61398): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/IcingCorporaProvider( 2821): UpdateCorporaTask done [took 141 ms] updated apps [took 141 ms] 
,W/PackageManager(  906): Unable to load service info ResolveInfo{42d3b1a8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/HtcFingerPrintQuickLaunchProvider( 4758): -onCreate()
,V/Settings:HtcSettingsApplication( 4758): [4758/4758] onCreate()
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4773 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=4430
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 4430:com.htc.showme/u0a83 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4430
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4773): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/Settings:HtcWirelessFeatureFlags( 4758): id/is att sku: 99/false
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4773, uid=10074, userID:0
,W/SystemReader( 4758): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 4758): Cannot find support_harman, use default value instead
,W/SystemReader( 4758): Cannot find effect_manager_id, use default value instead
,D/Finsky  ( 4773): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4773/10074)
,E/Settings:HtcWrapHeaderInfo( 4758): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4758): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4758): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4758): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4758): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4758): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4758): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4758): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4758): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4758): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4758): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4758): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4758): [supportHomeButton]support         :false
,W/FingerprintManager( 4758): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 4758): isSupportVoWifi: null
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4758): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 4773): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 4773): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4773/10074)
,D/Finsky  ( 4773): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4773): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 4773): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4773): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4773): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4773): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4773): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,W/dalvikvm( 4773): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4773, uid=10074, userID:0
,D/Ads     ( 4773): Skipping gmscore version check
,D/Finsky  ( 4773): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4773): [1] Libraries$2.run: Finished loading 1 libraries.
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4758): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4758): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4758): isSupportMusicChannel(): false
,D/Finsky  ( 4773): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4758): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4758): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4758): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4758): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4758): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4758): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4758): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4758): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4758): [supportHomeButton]support         :false
,W/FingerprintManager( 4758): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 4758): isSupportVoWifi: null
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 4758): Failed to find provider info for com.htc.vowifi
W/dalvikvm( 4773): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 4773): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 2192): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,D/PMS     (  906): acquireWL(42db3008): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2192, uid=10029, userID:0
,D/PMS     (  906): releaseWL(42db3008): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  906): killProcessQuiet, pid=4459
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4459:com.google.android.gm/u0a107 (adj 15): empty #17
,D/PMS     (  906): acquireWL(42d9e9e8): PARTIAL_WAKE_LOCK  Icing 0x1 2192 10029 WorkSource{10029 com.google.android.gms}
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4459
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2192/10029)
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@42154c70 +
,I/Prism.WidgetManager( 1273): onLoadItems() +
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2192/10029)
,D/libc    ( 2192): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 4
D/libc    ( 2192): [NET] getaddrinfo-,err=8
D/libc    ( 2192): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 1024
D/libc    ( 2192): [NET] getaddrinfo-, 1
,D/libc    ( 2192): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =fb16 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 61
D/libc    (  364): [NET]res_nsend:resplen=102
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2192): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2192): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 4
,D/libc    ( 2192): [NET] getaddrinfo-,err=8
,I/Icing   ( 2192): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360242618
,E/Prism.WidgetManager( 1273): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1273): onLoadItems() -
,I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@42154c70 -
,I/Icing   ( 2192): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  906): releaseWL(42d9e9e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1245): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1245): -- N1 =0
,D/PhoneApp( 1245): -- N2 =0
,D/PhoneApp( 1245): -- N3 =0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42d33188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{421acaf8: PendingIntentRecord{42aba128 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=302838, Int=0
,D/PMS     (  906): acquireWL(42c038e0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/PMS     (  906): releaseWL(42d33188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42ca7df8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42c038e0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(42ca7df8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(42d51d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42d51d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/IcingInternalCorpora( 2192): getNumBytesRead when not calculated.
,D/PMS     (  906): acquireWL(42e50f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=326581, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e50f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(421cbbb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/PMS     (  906): acquireWL(42c1b150): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{421acaf8: PendingIntentRecord{42aba128 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=339801, Int=0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42e0fa80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(421cbbb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [29][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0,
,D/PMS     (  906): acquireWL(42c4f000): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.docs/com.google/***** 0x1 906 1000 WorkSource{10100}
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(42c1b150): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(42e0fa80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42c943f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42c943f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42e58be0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42c4f000): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.docs/com.google/***** 0x1 WorkSource{10100}
,D/PMS     (  906): releaseWL(42e58be0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42d7bd60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{421acaf8: PendingIntentRecord{42aba128 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=369859, Int=0
,D/PMS     (  906): acquireWL(42ca8430): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42d7bd60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42d79ae0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42ca8430): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(42d79ae0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(42d8e630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42d8e630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(42d9bed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=386581, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42d9bed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/ClearcutLoggerApiImpl( 1361): disconnect managed GoogleApiClient
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42d89cb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42d89cb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42d47068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=446581, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42d47068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42e12000): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e12000): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(42c7f100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=506581, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42c7f100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42d50918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42d50918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42dfc118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(42dfc118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42e26420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=566581, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e26420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e02f28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e02f28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1245): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1245): sku_id=99
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1245): start background delete task...
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
,D/PMS     (  906): acquireWL(42dd1780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=626581, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42dd1780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e248b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(42e248b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=4828 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/ContextImpl( 4828): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4758): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4758): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4758): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 4758): Cust_ConnectToPC   : spcsc>false
D/        ( 4758): Cust_ConnectToPC   : IPT>true
,D/        ( 4758): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 4758): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4758): Index of the first 1 = 3
,W/ContextImpl( 4758): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 4758): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4758): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4758): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4758): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4758): [ACC]android_networking:tethering_guard_support=false
,D/Process (  906): killProcessQuiet, pid=4525
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  906): Killing 4525:com.google.android.videos/u0a165 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  906): Client com.google.android.videos (pid 4525): Died!
,I/ActivityManager(  906): Recipient 4525
,D/PMS     (  906): acquireWL(42dd7f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42dd7f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42e1e0c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=686581, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e1e0c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e38ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e38ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42dea748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42dea748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42d9fb58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=746581, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42d9fb58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e31550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e31550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42de5570): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42de5570): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/PowerUI ( 1118): closing low battery warning: level=100
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42e19958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=806581, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e19958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42dd51e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42dd51e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42e9bdb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e9bdb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/PowerUI ( 1118): closing low battery warning: level=100
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42ea19b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=866581, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42ea19b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42ea3430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(42ea3430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42eaaaa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(42eaaaa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42eb05f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=926581, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42eb05f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42eb2088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42eb2088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42eb7d88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{422b0dd8: PendingIntentRecord{42a53dd8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=783381, Int=0
V/AlarmManager(  906): sending alarm PendingIntent{42c12090: PendingIntentRecord{42c44ec0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=947073, Int=0
V/AlarmManager(  906): sending alarm PendingIntent{42b54d60: PendingIntentRecord{42bb8980 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454593866469, Int=900000
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/PMS     (  906): acquireWL(42ec6720): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): releaseWL(42ec6720): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4828): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4828): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4828): MY_DEBUG = false
D/PMS     (  906): releaseWL(42eb7d88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(42ed1ea8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024216
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024451
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024455
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024458
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024463
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026169
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026211
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029911
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360242618
,D/PMS     (  906): releaseWL(42ed1ea8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(42cc7408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42cc7408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42d347a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=986581, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42d347a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e65298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(42e65298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42df3700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{421d9c30: PendingIntentRecord{42d69b28 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454593940491, Int=0
,D/PMS     (  906): acquireWL(42cc82b8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4828 1000 null
,D/SmartSyncUtils( 4828): isEpsOn(), nState = 0
,D/PMS     (  906): releaseWL(42df3700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): releaseWL(42cc82b8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  906): acquireWL(42de7da0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4828 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4828): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4828): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4828): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4828): SettingOnTime = 1454652000000, randomSettingOnTime = 1454649946000
,D/SmartSyncScreenOnOffTimeReceiver( 4828): SettingOffTime = 1454637600000, randomSettingOffTime = 1454638518000
,D/SmartSyncScreenOnOffTimeReceiver( 4828): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4828): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4828): bNightModeTurnOffOnce = false
,D/PMS     (  906): releaseWL(42de7da0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  906): acquireWL(42aee7a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42aee7a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42e34b80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1046581, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e34b80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42c6e100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42c6e100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42da4e78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42da4e78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PowerUI ( 1118): closing low battery warning: level=100
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42f07440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1106581, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42f07440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e717f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e717f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42d122a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42d122a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42d73448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1166581, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42d73448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42d2da88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42d2da88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42c16bb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/PowerUI ( 1118): closing low battery warning: level=100
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(42c16bb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  906): acquireWL(42dd99d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428ab5f0: PendingIntentRecord{42314f40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1226581, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42dd99d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e56880): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/PMS     (  906): releaseWL(42e56880): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4872): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4872): ====startRecUseTime====
D/htc.customization.log.level( 4872):  is 
W/CustomizationLogLevel( 4872): Level value is invalid, use default level 2
D/CustomizationManager( 4872):  Read ACC file spent 0.108 (s)
D/CIDMapFileReader( 4872): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4872): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4872): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4872): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4872): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4872): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4872): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4872): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4872): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4872): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4872): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4872): Parsing tag category name = system
I/CustomizationCIDLoader( 4872): Parsing tag category name = application
I/CustomizationCIDLoader( 4872): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4872): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4872): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4872): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4872): Parsing tag category name = Settings
D/CustomizationManager( 4872):  Read CID file spent 0.158 (s)
D/CustomizationManager( 4872):  All configurations done spent 0.159 (s)
W/HtcNativeFlag( 4872): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4872): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4872): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4872): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4872, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  906): Skipping PackageSetting{42781a60 com.example.hello/10397} due to missing metadata
W/PackageSettings(  906): Skipping PackageSetting{42798c68 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
W/PackageManager(  906): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  906): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1554): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1554): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1554): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  906): acquireWL(42f38258): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1345): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1223): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): releaseWL(42f38258): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1301): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/[PluginManager]RegisterService( 4642): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 4642): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
W/AccTypeManager( 1345): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1345): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/IcingCorporaProvider( 2821): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
E/ExternalAccountType( 1345): Unsupported attribute readOnly
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4888 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/IcingCorporaProvider( 2821): UpdateCorporaTask done [took 121 ms] updated apps [took 120 ms] 
D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
W/ContextImpl( 4888): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4903 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4888): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4888): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4888): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4888): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4888): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4888): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4888): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4888): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4888): threadid=10: thread exiting with uncaught exception (group=0x41c91e30)
E/AndroidRuntime( 4888): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4888): Process: com.android.keychain, PID: 4888
E/AndroidRuntime( 4888): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4888): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4888): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4888): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4888): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4888): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4888): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  906): App crashed! Process: com.android.keychain
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4903): getInstance(Context context)
D/AppTag  ( 4903): getInstance(Context context)
D/Process ( 4888): killProcess, pid=4888
D/Process ( 4888): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/AppTag  ( 4903): onCreate()
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454594202084.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Recipient 4888
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.keychain (pid 4888) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/PMS     (  906): acquireWL(42c1e198): PARTIAL_WAKE_LOCK  AsyncService 0x1 4403 10160 null
D/PMS     (  906): releaseWL(42c1e198): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/ActivityManager(  906): Killing 4567:com.google.android.apps.cloudprint/u0a97 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=4567
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
W/dalvikvm( 4773): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2192): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2192): Clearing selected account for com.test.thalitest
D/Process (  906): killProcessQuiet, pid=4545
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4567
I/ActivityManager(  906): Killing 4545:com.google.android.apps.cloudprint:sync/u0a97 (adj 15): depends on provider com.google.android.apps.cloudprint/.printdialog.database.CloudPrintContentProvider in dying proc com.google.android.apps.cloudprint
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeDyingProviderLocked:13474 com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked:13550 
D/ChimeraCfgMgr( 2192): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2192): Module APK com.google.android.play.games already loaded
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4545
I/LocationSettingsChecker( 2192): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 2192): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
I/ActivityManager(  906): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 2192): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2192): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x656948c0
E/SQLiteDatabase( 2192): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2192): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2192): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2192): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2192): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2192): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2192): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2192): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2192): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2192): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2192): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2192): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2192): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2192): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2192): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2192): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2192): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2192): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2192): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2192): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2192): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2192): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2192): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2192): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2192): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2192): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2192): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2192): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2192): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2192): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2192): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DriveAsyncService( 2192): disk I/O error (code 3850)
E/DriveAsyncService( 2192): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2192): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2192): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2192): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2192): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2192): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2192): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2192): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2192): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2192): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2192): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2192): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2192): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2192): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2192): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2192): 	at java.lang.Thread.run(Thread.java:864)
D/ChimeraCfgMgr( 2192): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2192): Module APK com.google.android.play.games already loaded
E/SQLiteDatabase( 2192): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2192): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2192): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2192): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2192): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2192): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2192): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2192): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2192): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2192): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2192): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2192): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2192): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 2192): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2192): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2192): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2192): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2192): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2192): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2192): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2192): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2192): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2192): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2192): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2192): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2192): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2192): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2192): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2192): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2192): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2192): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2192): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2192): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2192): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2192): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2192): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BaseAppContext( 2192): Using Auth Proxy for data requests.
W/SQLiteOpenHelper( 2192): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 2192): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 2192): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 2192): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 2192): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 2192): threadid=48: thread exiting with uncaught exception (group=0x41c91e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2192): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 2192): Process: com.google.android.gms, PID: 2192
E/AndroidRuntime( 2192): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 2192): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2192): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 2192): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2192): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2192): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 2192): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 2192): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 2192): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2192): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2192): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2192): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2192): killProcess, pid=2192
W/BaseAppContext( 2192): Using Auth Proxy for data requests.
D/Process ( 2192): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
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
I/ActivityManager(  906): Recipient 2192
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.gms (pid 2192) has died.
D/WifiService(  906): Client connection lost with reason: 4
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
I/ActivityManager(  906): Resuming delayed broadcast
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
E/SQLiteLog( 1361): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1361): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x6403f290
W/dalvikvm( 1361): threadid=1: thread exiting with uncaught exception (group=0x41c91e30)
W/PackageManager(  906): Unable to load service info ResolveInfo{429f3820 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/AndroidRuntime( 1361): FATAL EXCEPTION: main
E/AndroidRuntime( 1361): Process: com.google.process.gapps, PID: 1361
E/AndroidRuntime( 1361): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1361): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1361): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1361): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1361): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1361): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1361): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1361): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1361): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1361): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1361): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1361): 	... 10 more
E/ActivityManager(  906): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 1361): killProcess, pid=1361
D/Process ( 1361): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4932 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4932): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4932 dbg=false s=true
I/DeviceManagement( 4932): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4932): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4932): WorkflowService: Starting workflow service
I/DeviceManagement( 4932): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@420f3418] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4932): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4932): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4932): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4932): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  906): Recipient 1361
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
I/ActivityManager(  906): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4946 uid=10099 gids={50099, 3003, 5012}
I/ActivityManager(  906): Process com.google.process.gapps (pid 1361) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
I/DeviceManagement( 4932): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4932): SessionStateController: Checking invariants...
D/Documents( 4946): Loading roots for com.android.providers.downloads.documents
D/Documents( 4946): Loading roots for com.android.externalstorage.documents
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@42154c70 +
I/Prism.WidgetManager( 1273): onLoadItems() +

```
