#### Test 57659382b63fd0b_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/Prism.ItemManager( 3709): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 3709): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
--------- beginning of /dev/log/system
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "sms"
I/ActivityManager(  913): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "smsto"
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.music (3874/10154)
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
I/NetworkMonitor( 3874): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  913): Resuming delayed broadcast
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=9 [72][7][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,E/ExternalAccountType( 1343): Unsupported attribute readOnly
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mmsto"
D/Process (  913): killProcessQuiet, pid=3572
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
I/ActivityManager(  913): Killing 3572:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
I/ActivityManager(  913): Recipient 3572
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PhoneApp( 1250): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/TelephonyReceiver( 1250): bind: true
I/ActivityManager(  913): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3900 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
D/GenericMessagesProvider( 3729): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 3729): (14) cannot open file at line 30190 of [00bb9c9ce4]
E/SQLiteLog( 3729): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 3729): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 3729): DB info: errno = 2, errno message = No such file or directory
D/MediaRouter( 3874): getSelectedRoute
E/SQLiteDatabase( 3729): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 3729): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 3729): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3729): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3729): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3729): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3729): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3729): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3729): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3729): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3729): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3729): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 3729): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 3729): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3729): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3729): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 3729): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 3729): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 3729): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 3729): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3729): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 3729): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 3729): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 3729): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 3729): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 3729): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 3729): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 3729): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 3729): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 3729): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 3729): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 3729): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 3729): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 3729): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err( 3729): 	at dalvik.system.NativeStart.run(Native Method)
I/NetworkMonitor( 3874): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/TelephonyReceiver( 1250): switchBindHtcMsgCursor: null
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.google.android.music (3874/10154)
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/DFPI.PIReciver( 3900): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
D/Messaging( 3729): mNeedToUpdateDate2 start
D/ReportIndicatorCache( 3729): startAsyncQueryReports ---
I/Messaging( 3729): mccmnc> 
D/MmsAsyncWorkHandler( 3729): 
D/MmsAsyncWorkHandler( 3729): HM tk = 20001
D/ReportIndicatorCache( 3729): MSG_QUERY_REPORTS >>
D/DraftCache( 3729): [DraftCache/1] DraftCache.constructor
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
I/DFPI.ApkInstallService( 3900): onHandleIntent
I/DFPI.ApkInstallService( 3900): Media Scan Finished Case 
D/DraftCache( 3729): [DraftCache/1] refresh
D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/MmsSmsV2Provider( 1250):  phoneType = -1
D/MmsSmsV2Provider( 1250): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/MmsConfig( 3729): networkCode: 
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
I/ActivityManager(  913): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
V/AlarmManager(  913): sending alarm PendingIntent{4270f198: PendingIntentRecord{4270f118 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1454082571400, Int=0
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3874, uid=10154, userID:0
D/Messaging( 3729): ViewCache CreatePreloadOnlyConversationList
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/DFPI.ApkInstallService( 3900): check CID = HTC__032
I/DFPI.ApkInstallService( 3900): There is no Demo.apk in sd card or phone storage
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/AccFlag ( 1250): sku_id=99
I/ActivityManager(  913): Resuming delayed broadcast
D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1250):  phoneType = -1
D/MmsSmsV2Provider( 1250): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 3729): [DraftCache/358] rebuildCache
I/ActivityManager(  913): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3922 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
D/Process (  913): killProcessQuiet, pid=3411
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 3411:com.htc.calendar/u0a13 (adj 15): empty #17
D/PhoneStorageUtil( 3729): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 3729): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 3729): createReceiver
D/Messaging( 3729): mNeedToUpdateDate2: false
D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/MmsSmsV2Provider( 1250):  phoneType = -1
D/MmsSmsV2Provider( 1250): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/MessageCustFlag( 3729): sense_version=6.0
D/Jerry   ( 3729): start to preload cursor >>>>>>>
I/ActivityManager(  913): Recipient 3411
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/Jerry   ( 1250): URI_DRAFT
D/TelephUtils( 1250): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
V/MmsProvider( 1250): Update uri=content://mms, match=0
V/MmsProvider( 1250): selection=st=129 AND m_type!=134
D/Process (  913): killProcessQuiet, pid=3651
I/ActivityManager(  913): Killing 3651:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/DraftCache( 3729): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 3729): [DraftCache/358] rebuildCache time: 3
D/MmsAsyncWorkHandler( 3729): 
D/MmsAsyncWorkHandler( 3729): HM tk = 20002
D/Messaging( 3729): Reset downloading state: 0
V/MmsSystemEventReceiver( 3729): TransactionService is going to be woken up.
W/PackageManager(  913): Unable to load service info ResolveInfo{427f95c8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  913): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  913): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  913): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  913): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  913): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  913): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  913): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  913): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  913): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  913): 	at dalvik.system.NativeStart.main(Native Method)
D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/MmsSmsV2Provider( 1250):  phoneType = -1
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Recipient 3651
V/TransactionService( 3729): 1-Creating TransactionService
D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1250):  phoneType = -1
D/MmsSmsV2Provider( 1250): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/Messaging( 3729): ViewCache CreatePreload
D/Messaging( 3729): ViewCache CreatePreloadOnlyMultipleOpsList
V/TransactionService( 3729): onStartCommand: 1
D/MmsSystemEventReceiver( 3729): unRegisterForConnectionStateChanges
V/TransactionService( 3729): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 3729): Loading previous transactions.
D/Cust_MMSMS( 3729): _has_set_default_values_2=true
I/ActivityManager(  913): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
D/MsgPreferenceUtils( 3729): def_index: 0
D/MsgPreferenceUtils( 3729): globalIndex = 1
D/MsgPreferenceUtils( 3729): phone state: true
D/MsgPreferenceUtils( 3729): sd state: false
D/MsgPreferenceUtils( 3729): vIndex = 0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.musicenhancer (3922/10053)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.musicenhancer (3922/10053)
W/BroadcastQueue(  913): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{428222c0 u0 ReceiverList{42822260 3922 com.htc.musicenhancer/10053/u0 remote:42821f68}}
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3922): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/AccFlag ( 1250): sku_id=99
D/Messaging( 3729): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/AccFlag ( 1250): device_type: 1
E/cutils-trace( 3905): Error opening trace file: No such file or directory (2)
D/TransactionService( 3729): Force set service start id to 1
V/TransactionService( 3729): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 3729): unRegisterForConnectionStateChanges
D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/AccFlag ( 1250): sku_id=99
V/TransactionService( 3729): Destroying TransactionService
I/ActivityManager(  913): Resuming delayed broadcast
D/TransactionService( 3729): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 3729): 4-Handling incoming message: { when=-13ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
I/ActivityManager(  913): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3965 uid=10081 gids={50081, 5001, 1028, 1015}
I/SoundPicker( 3965): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3965): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3965): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3965): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3965): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3965): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  913): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3965): MODE_GSM access default DB
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3965): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3965): MODE_GSM access default DB
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
D/CustomizationManager( 3905): ====startRecUseTime====
D/htc.customization.log.level( 3905):  is 
W/CustomizationLogLevel( 3905): Level value is invalid, use default level 2
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  913): Resuming delayed broadcast
D/Process (  913): killProcessQuiet, pid=3112
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 3112:com.android.settings:remote/1000 (adj 15): empty #17
D/DFPI.PIReciver( 3900): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DFPI.ApkInstallService( 3900): onHandleIntent
I/DFPI.ApkInstallService( 3900): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3900): check CID = HTC__032
I/DFPI.ApkInstallService( 3900): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  913): Recipient 3112
I/ActivityManager(  913): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  913): Resuming delayed broadcast
I/SoundPicker( 3965): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3965): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3965): SoundPickerReceiver [onReceive] startService
I/ActivityManager(  913): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3965): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3965): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3965): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3965): MODE_GSM access default DB
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3965): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3965): MODE_GSM access default DB
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
D/CustomizationManager( 3905):  Read ACC file spent 0.080 (s)
D/CIDMapFileReader( 3905): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3905): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3905): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3905): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3905): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3905): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3905): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3905): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3905): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3905): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3905): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3905): Parsing tag category name = system
I/CustomizationCIDLoader( 3905): Parsing tag category name = application
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/CustomizationCIDLoader( 3905): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3905): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3905): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3905): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3905): Parsing tag category name = Settings
D/CustomizationManager( 3905):  Read CID file spent 0.140 (s)
D/CustomizationManager( 3905):  All configurations done spent 0.140 (s)
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/HtcModeClient( 1528): handler message = 4011
E/HtcModeClient( 1528): Check connection and retry 5 times.
W/HtcNativeFlag( 3905): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3905): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3905): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3905): Fail to get flag for type 'language', use default value: -1
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/Adreno-EGL( 3743): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3743): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3743): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3743): Local Branch: 
I/Adreno-EGL( 3743): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3743): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3743):                  aa63bbd948f41d15fc72f585e
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  913): Resuming delayed broadcast
I/ActivityManager(  913): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3905
I/ActivityManager(  913): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  913): Resuming delayed broadcast
I/ActivityManager(  913): Delay finish: com.htc.task/.TodoTaskReceiver
I/WVCdm   (  371): CdmEngine::OpenSession
I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
I/ActivityManager(  913): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3989 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
I/ActivityManager(  913): Resuming delayed broadcast
D/DFPI.PIReciver( 3900): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
D/WVCdm   (  371): PrepareKeyRequest: nonce=2394948651
I/DFPI.ApkInstallService( 3900): onHandleIntent
I/DFPI.ApkInstallService( 3900): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3900): check CID = HTC__032
I/DFPI.ApkInstallService( 3900): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  913): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  913): Resuming delayed broadcast
I/SoundPicker( 3965): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3965): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3965): SoundPickerReceiver [onReceive] startService
I/ActivityManager(  913): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/EASAppSvc( 3989): [ NA ]- onCreate()
I/SoundPicker( 3965): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3965): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3965): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3965): MODE_GSM access default DB
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3965): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3965): MODE_GSM access default DB
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/EASAppSvc( 3989): [ NA ]> onUpgrade: version = 63
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/WVCdm   (  371): CdmEngine::CloseSession
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/ORMLib  ( 3460): put()
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/EASAppSvc( 3989): [ NA ]- onDestroy()
I/EASAppSvc( 3989): [ NA ]> uninitEASService
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
D/WifiService(  913): New client listening to asynchronous messages
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.htc.android.mail (3989/10064)
D/ConnectivityService(  913): getNetworkInfo networkType=0 called by com.htc.android.mail (3989/10064)
D/ConnectivityService(  913): getNetworkInfo networkType=55 called by com.htc.android.mail (3989/10064)
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/Adreno-EGL( 3743): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3743): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3743): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3743): Local Branch: 
I/Adreno-EGL( 3743): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3743): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3743):                  aa63bbd948f41d15fc72f585e
I/ActivityManager(  913): Resuming delayed broadcast
I/ActivityManager(  913): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/Adreno-EGL( 3743): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3743): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3743): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3743): Local Branch: 
I/Adreno-EGL( 3743): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3743): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3743):                  aa63bbd948f41d15fc72f585e
D/AutoSetting( 1319): service - mRequestRunnable: screen on delay 10s, request NLP now
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1319): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1319): service - requestNLP() NetworkLocationProvider not enabled
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1117): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  913):    returned true
I/EASRequestController( 3989): [ NA ]release
I/EASAppSvc( 3989): [ NA ]< uninitEASService
I/EASAppSvc( 3989): [ NA ]- onCreate()
I/EASAppSvc( 3989): [ NA ]> onUpgrade: version = 63
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.htc.android.mail (3989/10064)
I/MediaStoreImporter( 3874): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
D/Process (  913): killProcessQuiet, pid=3666
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  913): getNetworkInfo networkType=0 called by com.htc.android.mail (3989/10064)
D/ConnectivityService(  913): getNetworkInfo networkType=55 called by com.htc.android.mail (3989/10064)
I/ActivityManager(  913): Resuming delayed broadcast
I/ActivityManager(  913): Killing 3666:com.qualcomm.timeservice/1000 (adj 15): empty #17
I/ActivityManager(  913): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/DFPI.PIReciver( 3900): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  913): Resuming delayed broadcast
D/ORMLib  ( 3460): put()
I/DFPI.ApkInstallService( 3900): onHandleIntent
I/DFPI.ApkInstallService( 3900): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3900): check CID = HTC__032
I/DFPI.ApkInstallService( 3900): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  913): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  913): Resuming delayed broadcast
I/ActivityManager(  913): Recipient 3666
I/SoundPicker( 3965): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 3965): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3965): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3965): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3965): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3965): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3965): MODE_GSM access default DB
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3965): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3965): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3965): MODE_GSM access default DB
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/ActivityManager(  913): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/EASAppSvc( 3989): [ NA ]- onDestroy()
I/EASAppSvc( 3989): [ NA ]> uninitEASService
I/EASRequestController( 3989): [ NA ]release
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/EASAppSvc( 3989): [ NA ]< uninitEASService
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/ActivityManager(  913): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=4031 uid=10068 gids={50068, 3003, 5012}
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
W/Settings( 3743): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (3743/10029)
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3965): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
D/RemoteDisplayProvider(  913): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  913): start
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3965): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3965): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3965): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/CheckinRequestBuilder( 2184): Classify the device as Phone.
I/ActivityManager(  913): Resuming delayed broadcast
D/ORMLib  ( 3460): put()
I/GCoreNlp( 1230): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41b99cb0 +
I/Prism.WidgetManager( 1277): onLoadItems() +
I/ActivityManager(  913): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
I/Prism.ItemManager( 3709): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3709): loadItems() com.htc.launcher.pageview.WidgetManager@41b79d78 +
I/Prism.WidgetManager( 3709): onLoadItems() +
D/PMS     (  913): acquireWL(4263d8f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 913 1000 null
D/PMS     (  913): releaseWL(4263d8f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/LocationProviderProxy(  913): applying state to connected service
D/PMS     (  913): acquireWL(426b9da0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(426b9da0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/LocationProviderProxy(  913): applying state to connected service
D/PMS     (  913): acquireWL(42746790): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(42746790): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(427f3ea0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(427f3ea0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2184): [NET] getaddrinfo-,err=8
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2184): [NET] getaddrinfo-, 1
D/libc    ( 2184): [NET] getaddrinfo_proxy+
D/PMS     (  913): acquireWL(4276e620): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =3efb +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2184): [NET] getaddrinfo_proxy-, success
D/PMS     (  913): releaseWL(4276e620): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/MediaStoreImporter( 3874): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2184): [NET] getaddrinfo-,err=8
D/Process (  913): killProcessQuiet, pid=3709
I/ActivityManager(  913): Resuming delayed broadcast
I/ActivityManager(  913): Killing 3709:com.htc.sense.news/u0a76 (adj 15): empty #17
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  913): acquireWL(42752cc0): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1528 10014 null
I/ActivityManager(  913): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2184): [NET] getaddrinfo-,err=8
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2184): [NET] getaddrinfo-,err=8
D/PMS     (  913): releaseWL(42752cc0): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
D/TelephonyReceiver( 1250): bind: false
D/TelephonyReceiver( 1250): switchBindHtcMsgCursor: null
I/ActivityManager(  913): Resuming delayed broadcast
,I/CheckinTask( 2184): Sending checkin request (12248 bytes)
I/ActivityManager(  913): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4053 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,I/ActivityManager(  913): Recipient 3709
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  913): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4066 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/Process (  913): killProcessQuiet, pid=3762
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  913): Killing 3762:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 3762
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  913): releaseWL(424d6af0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,E/Prism.WidgetManager( 1277): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1277): onLoadItems() -
,I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41b99cb0 -
,D/PMS     (  913): acquireWL(42597d30): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42597d30): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/GAV2    ( 4066): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  913): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  913): acquireWL(42534898): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42534898): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(426af988): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(426af988): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/RemoteViews( 1122): com.htc.updater (true,33751552)
D/NotificationService(  913): notification sound not played, stream=5 volume=0 always=false
,D/OnDemandProgressBar( 1122): release indeterminate drawable android.widget.OnDemandProgressBar{41e40ae0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1122): com.htc.updater 2 7 0 10
,I/RemoteViews( 1122): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1122): release indeterminate drawable android.widget.OnDemandProgressBar{41e16ff0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/Process (  913): killProcessQuiet, pid=3781
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/RemoteViews.Performance( 1122): com.htc.updater 1 6 0 10
I/ActivityManager(  913): Resuming delayed broadcast
D/PMS     (  913): acquireWL(42623220): PARTIAL_WAKE_LOCK  NetworkStats 0x1 913 1000 null
I/ActivityManager(  913): Killing 3781:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 3781
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiDataStallTracker(  913): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  913): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  913): updateDataStallInfo: mDataStallTxRxSum={txSum=148 rxSum=142} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  913): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  913): onDataStallAlarm: tag=22750 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  913): startDataStallAlarm: tag=22751 delay=15s
,D/PMS     (  913): releaseWL(42623220): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/Gmail   ( 4066): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4066): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ActivityManager(  913): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4101 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Gmail   ( 4066): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4066): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/PhoneApp( 1250): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1250): -- N1 =0
,D/PhoneApp( 1250): -- N2 =0
,D/PhoneApp( 1250): -- N3 =0
I/Babel   ( 4101): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 4101): MmsConfig.loadMmsSettings
,W/dalvikvm( 4101): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4101): VFY: unable to resolve instance field 36
,W/dalvikvm( 4101): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4101): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MmsCustomizationProvider( 3729): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 3729): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4101): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4101): MmsConfig.loadFromDatabase
,E/Babel   ( 4101): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4101): MmsConfig.loadFromResources
,E/Babel   ( 4101): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4101): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4101, uid=10111, userID:0
,W/Settings( 4101): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4101, uid=10111, userID:0
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4101, uid=10111, userID:0
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4101, uid=10111, userID:0
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4101, uid=10111, userID:0
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4101, uid=10111, userID:0
D/PMS     (  913): acquireWL(4269b6a0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4101 10111 null
I/ActivityManager(  913): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 4101): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  913): releaseWL(4269b6a0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  913): Resuming delayed broadcast
,D/PMS     (  913): acquireWL(42699988): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4101 10111 null
,I/ActivityManager(  913): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  913): releaseWL(42699988): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  913): Resuming delayed broadcast
,D/Process (  913): killProcessQuiet, pid=3613
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 3613:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,I/[PluginManager]RegisterService( 1319): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1319): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2826): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  913): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  913): acquireWL(4263c478): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(4263c478): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(42699c60): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42699c60): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  913): Recipient 3613
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  913): acquireWL(42666410): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42666410): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4280c040): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(4280c040): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(427f0b50): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(427f0b50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(425239e8): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(425239e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(42471628): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42471628): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(426af5c0): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(426af5c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(425977b8): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(425977b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(426f7d60): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(426f7d60): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2826): UpdateCorporaTask done [took 326 ms] updated apps [took 326 ms] 
I/ActivityManager(  913): Resuming delayed broadcast
,I/ActivityManager(  913): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4143 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/CheckinResponseProcessor( 2184): From server: 1 gservices updates and 0 deletes
,I/ActivityManager(  913): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  913): acquireWL(42621230): PARTIAL_WAKE_LOCK  AsyncService 0x1 4143 10160 null
,D/PMS     (  913): releaseWL(42621230): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  913): Resuming delayed broadcast
,D/PMS     (  913): acquireWL(427e2278): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4143 10160 null
,I/ActivityManager(  913): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4169 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  913): killProcessQuiet, pid=3796
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  913): Killing 3796:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 3796
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  913): acquireWL(4263ce40): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4143 10160 null
,D/WifiService(  913): Client connection lost with reason: 4
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=17 [17][3][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  913): releaseWL(427e2278): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.plus (4143/10160)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.plus (4143/10160)
,I/CertBlacklister(  913): Certificate blacklist changed, updating...
,I/CertBlacklister(  913): Certificate blacklist updated
,D/PMS     (  913): releaseWL(4263ce40): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,I/GservicesProvider( 1372): main difference update completed
,I/CheckinRequestBuilder( 2184): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  913): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2184): Failed to find provider info for com.google.android.wearable.settings
,W/dalvikvm( 4169): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/Settings:HtcWirelessFeatureFlags( 3823): id/is att sku: 99/false
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4169, uid=10074, userID:0
,W/SystemReader( 3823): Cannot find devicepolicy_lower_fp_quality, use default value instead
,D/Finsky  ( 4169): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/SystemReader( 3823): Cannot find support_harman, use default value instead
,W/SystemReader( 3823): Cannot find effect_manager_id, use default value instead
D/ConnectivityService(  913): getAllNetworkInfo called by com.android.vending (4169/10074)
,E/Settings:HtcWrapHeaderInfo( 3823): no such activity!
,I/SensorManager(  913): mEventCount = 450
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3823): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3823): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3823): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3823): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3823): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3823): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3823): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3823): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3823): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3823): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3823): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3823): [supportHomeButton]support         :false
,W/FingerprintManager( 3823): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,W/dalvikvm( 4169): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 4169): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  913): getAllNetworkInfo called by com.android.vending (4169/10074)
,D/Finsky  ( 4169): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4169): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 4169): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4169): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4169): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4169): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4169): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,I/ActivityManager(  913): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 3823): isSupportVoWifi: null
E/ActivityThread( 3823): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 4169): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4169, uid=10074, userID:0
,D/Ads     ( 4169): Skipping gmscore version check
,D/Finsky  ( 4169): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4169): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4169): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ConnectivityService(  913): getNetworkInfo networkType=9 called by com.google.android.gms (2184/10029)
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,W/dalvikvm( 4169): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 4169): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  913): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
I/ActivityManager(  913): Resuming delayed broadcast
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3823): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3823): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3823): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3823): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3823): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3823): [supportRecentAppsButton]support         :false
,D/PackageBroadcastService( 2184): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
,D/PMS     (  913): acquireWL(4276a090): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4101 10111 null
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3823): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3823): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3823): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3823): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3823): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3823): [supportHomeButton]support         :false
,W/FingerprintManager( 3823): hasFingerprint() - sSensorCode = 0
,D/Process (  913): killProcessQuiet, pid=3682
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  913): releaseWL(4276a090): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  913): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
I/ActivityManager(  913): Resuming delayed broadcast
I/ActivityManager(  913): Killing 3682:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  913): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 3823): isSupportVoWifi: null
E/ActivityThread( 3823): Failed to find provider info for com.htc.vowifi
D/PMS     (  913): acquireWL(42727558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  913): Recipient 3682
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
D/PMS     (  913): acquireWL(427099e0): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  913): releaseWL(42727558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(426afe88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
W/GCoreFlp( 1230): No location to return for getLastLocation()
,W/FusedLocationProvider( 1230): location=null
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/PMS     (  913): acquireWL(425defb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(425defb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(424248c0): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
D/PMS     (  913): releaseWL(426afe88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinRequestBuilder( 2184): Classify the device as Phone.
,W/dalvikvm( 2184): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2184): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2184): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2184): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2184): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
,W/dalvikvm( 2184): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 2184): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2184, uid=10029, userID:0
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/PeopleDatabaseHelper( 2184): cleanUpNonGplusAccounts done.
,D/PMS     (  913): acquireWL(4276ddc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,I/CheckinTask( 2184): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
D/PMS     (  913): releaseWL(4276ddc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(4238b2e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
D/PMS     (  913): releaseWL(424248c0): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
I/CheckinService( 2184): Checking schedule, now: 1454082574598 next: 1454605511583
,I/CheckinService( 2184): active receiver: disabled
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
,D/CheckinService( 2184): Recording last checkin time for package unspecified as 1454082574615
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  913): releaseWL(4238b2e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(426f4980): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
D/PMS     (  913): releaseWL(4267a580): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
,D/PMS     (  913): releaseWL(426f4980): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  913): acquireWL(42769d28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
D/PMS     (  913): releaseWL(42769d28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): acquireWL(4277b568): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4225 uid=10041 gids={50041}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
,D/PMS     (  913): releaseWL(4277b568): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(425666f0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3460 10071 null
,D/PMS     (  913): acquireWL(42621dc8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3460 10071 null
,D/Process (  913): killProcessQuiet, pid=3695
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  913): Killing 3695:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
I/ActivityManager(  913): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
,D/PMS     (  913): releaseWL(425666f0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 3460): java.lang.NullPointerException
W/System.err( 3460): java.lang.NullPointerException
W/System.err( 3460): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3460): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3460): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3460): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3460): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3460): stopSelfResult true
D/PMS     (  913): releaseWL(42621dc8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  913): Resuming delayed broadcast
D/ConnectivityService(  913): Sampling interval elapsed, updating statistics ..
I/ActivityManager(  913): Recipient 3695
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  913): acquireWL(426aa0d8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3460 10071 null
I/SocialFeedProvider( 1277): +disConnect socialManager
,I/SocialFeedProvider( 1277): disconnect socialManager
,I/SocialFeedProvider( 1277): -disConnect socialManager
E/TodoTaskNotifyService( 3460): java.lang.NullPointerException
,W/System.err( 3460): java.lang.NullPointerException
W/System.err( 3460): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
D/PMS     (  913): acquireWL(424cb0f0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3460 10071 null
D/PMS     (  913): releaseWL(426aa0d8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/ConnectivityService(  913): Done.
D/ConnectivityService(  913): Setting timer for 720seconds
,I/ActivityManager(  913): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
W/System.err( 3460): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3460): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3460): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3460): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3460): stopSelfResult true
D/PMS     (  913): releaseWL(424cb0f0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  913): Resuming delayed broadcast
D/PMS     (  913): acquireWL(42745488): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3460 10071 null
D/PMS     (  913): acquireWL(42463420): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3460 10071 null
,D/PMS     (  913): releaseWL(42745488): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 3460): java.lang.NullPointerException
W/System.err( 3460): java.lang.NullPointerException
W/System.err( 3460): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3460): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3460): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3460): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3460): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  913): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  913): releaseWL(42463420): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  913): Resuming delayed broadcast
W/NotifyReceiver( 3460): stopSelfResult true
,D/LocationInitializer( 2184): Restart initialization of location
,D/WearableService( 1230): callingUid 10029, callindPid: 1230
,E/MDM     ( 1230): [110] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1372): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1372): Proximity feature is not enabled.
,W/GCoreFlp( 1230): No location to return for getLastLocation()
,W/FusedLocationProvider( 1230): location=null
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  913): acquireWL(42660f68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(42660f68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
D/PMS     (  913): acquireWL(4270a0d0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4101 10111 null
I/ActivityManager(  913): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  913): releaseWL(4270a0d0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  913): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1319): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms,
,I/[PluginManager]RegisterService( 1319): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2826): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  913): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  913): Resuming delayed broadcast
I/ActivityManager(  913): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2826): UpdateCorporaTask done [took 180 ms] updated apps [took 180 ms] 
I/ActivityManager(  913): Resuming delayed broadcast
,I/ActivityManager(  913): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  913): acquireWL(42656158): PARTIAL_WAKE_LOCK  AsyncService 0x1 4143 10160 null
,D/PMS     (  913): releaseWL(42656158): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  913): Resuming delayed broadcast
,D/PackageBroadcastService( 2184): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2184): Null package name or gms related package.  Ignoreing.
,I/WSP     ( 1319): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1319): Weather sync is On
,I/Icing   ( 2184): updateResources: need to parse f{com.google.android.gms}
D/PMS     (  913): releaseWL(41f2e318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10055}
,I/WSP     ( 1319): [Receiver] next auto-sync alarm event is 60 mins later, at time: Fri Jan 29 17:49:35 CET 2016
D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.sense.hsp (1319/10055)
I/ActivityManager(  913): Delay finish: com.htc.task/.TodoReceiver
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.sense.hsp (1319/10055)
,D/PMS     (  913): acquireWL(427415c8): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1319 10055 null
,D/TodoTaskshortcut( 3460): update TASK shortcut>
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1117): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,I/Icing   ( 2184): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/WIFI_ICON( 1122): WifiActivity: 1
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/Icing   ( 2184): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2184): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  913): acquireWL(42626200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42626200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1122): closing low battery warning: level=100
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  913): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=4264 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,D/PMS     (  913): acquireWL(426a93c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10055}
,V/AlarmManager(  913): sending alarm PendingIntent{4238b748: PendingIntentRecord{4268c090 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1454082575822, Int=0
,D/PMS     (  913): releaseWL(426a93c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10055}
,I/ImageRamCache( 4264): create image Cache, size: 31457280.
I/ImageRamCache( 4264): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4264): create image Cache, size: 12582912.
,I/FeedSettings( 4264): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4264): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4264): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4264): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4264): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4264): loadGridSize() with Alternative
,I/SocialManager[SocialBiLogHelper]( 4264): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 4264): last commit ulog time 1454047590799
,I/SocialManager[SocialBiLogHelper]( 4264): skip commit this time
,D/Process (  913): killProcessQuiet, pid=3839
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 3839:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 3839
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Icing   ( 2184): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2184): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  913): releaseWL(427099e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  913): acquireWL(42748120): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b1efb0: PendingIntentRecord{42508610 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=63223, Int=0
,D/Process (  913): killProcessQuiet, pid=3426
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  913): Killing 3426:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
I/HtcModeClient( 1528): handler message = 4011
E/HtcModeClient( 1528): Check connection and retry 6 times.
,I/ActivityManager(  913): Recipient 3426
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1122): WifiActivity: 0
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/Process (  913): killProcessQuiet, pid=3989
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 3989:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 3989
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  913): Client connection lost with reason: 4
,V/AlarmManager(  913): sending alarm PendingIntent{42497728: PendingIntentRecord{42493aa8 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1454082577928, Int=0
,I/GAV2    ( 4066): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 4101): Thread[GAThread,5,main]: No campaign data found.
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1117): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
D/WifiStateMachine(  913): [ScoreAP] + current TXpacket:198, mTXpacketCount:74, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  913): [ScoreAP] + TX packet increase one time, don't update TX rate in DB
,D/WIFI_ICON( 1122): WifiActivity: 1
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1122): WifiActivity: 0
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/AlarmManager(  913): sending alarm PendingIntent{425b2818: PendingIntentRecord{4257a2b8 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1454082579640, Int=0
,W/SQLiteConnectionPool( 2184): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
V/AlarmManager(  913): sending alarm PendingIntent{42552408: PendingIntentRecord{4254a400 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1454082579705, Int=0
,I/iu.UploadsManager( 2184): End new media; added: 0, uploading: 0, time: 88 ms
,I/CalendarProvider2( 1528): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1528): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  913): Resuming delayed broadcast
,I/ActivityManager(  913): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  913): Resuming delayed broadcast
,I/ActivityManager(  913): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4288 uid=10016 gids={50016, 3003, 5012, 2001}
,W/ContextImpl( 4288): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4288): Update started
,I/ActivityManager(  913): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/ActivityManager(  913): Resuming delayed broadcast
,D/ConnectivityService(  913): getAllNetworkInfo called by  (1938/10021)
,E/UpdateRequestReceiver( 4288): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ContextImpl( 4288): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4288): Update started
,I/DownloadManager( 1938): Download 303 starting
D/PMS     (  913): acquireWL(42828488): PARTIAL_WAKE_LOCK  DownloadManager 0x1 1938 10021 WorkSource{10016}
I/ActivityManager(  913): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
D/ConnectivityService(  913): getAllNetworkInfo called by  (1938/10021)
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1938/10021)
W/ActivityThread( 1938): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  913): Resuming delayed broadcast
E/UpdateRequestReceiver( 4288): Received malformed URL while handling Gservices.CHANGED_ACTION
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  913): getAllNetworkInfo called by  (1938/10021)
E/UpdateRequestReceiver( 4288): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4288): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/DownloadManager( 1938): Download 304 starting
D/PMS     (  913): acquireWL(42686c30): PARTIAL_WAKE_LOCK  DownloadManager 0x1 1938 10021 WorkSource{10016}
,I/ActivityManager(  913): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4319 uid=10032 gids={50032, 3003, 5012}
,D/Process (  913): killProcessQuiet, pid=3900
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  913): Killing 3900:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
D/ConnectivityService(  913): getAllNetworkInfo called by  (1938/10021)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1938/10021)
D/libc    ( 1938): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 1938): [NET] getaddrinfo-,err=8
D/libc    ( 1938): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 1938): [NET] getaddrinfo-, 1
D/libc    ( 1938): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    ( 1938): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    (  363): [NET] +++++ res_nsend xid =7338 +++++
D/libc    ( 1938): [NET] getaddrinfo-,err=8
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
D/libc    ( 1938): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 1938): [NET] getaddrinfo-, 1
D/libc    ( 1938): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =e938 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
I/ActivityManager(  913): Recipient 3900
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [2][0][0]
,I/ActivityManager(  913): Delay finish: com.google.android.partnersetup/.GservicesChangedReceiver
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 46
D/libc    (  363): [NET]res_nsend:resplen=49
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1938): [NET] getaddrinfo_proxy-, success
,D/libc    (  363): [NET]res_nsend:resplen=49
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1938): [NET] getaddrinfo_proxy-, success
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.youtube, clsName=null, state=1, flag=0, pid=4319, uid=10032, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=4319, uid=10032, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.apps.magazines, clsName=null, state=1, flag=0, pid=4319, uid=10032, userID:0
,D/PMS     (  913): acquireWL(422d9520): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1122): WifiActivity: 3
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.apps.books, clsName=null, state=1, flag=0, pid=4319, uid=10032, userID:0
,D/PMS     (  913): releaseWL(422d9520): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=null, state=1, flag=0, pid=4319, uid=10032, userID:0
,D/PMS     (  913): acquireWL(42679ab0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42679ab0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4227f6d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
I/DownloadManager( 1938): Ignoring Content-Length since Transfer-Encoding is also defined
,D/PMS     (  913): releaseWL(4227f6d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(425d7520): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(425d7520): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=9 [11][1][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1938/10021)
,D/PMS     (  913): acquireWL(42657668): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/PMS     (  913): releaseWL(42657668): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(424e7370): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(424e7370): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(42499838): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42499838): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Resuming delayed broadcast
,D/Process (  913): killProcessQuiet, pid=3856
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 3856:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/DownloadManager( 1938): Ignoring Content-Length since Transfer-Encoding is also defined
,I/DownloadManager( 1938): Download 304 finished with status SUCCESS
I/ActivityManager(  913): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.GservicesChangedReceiver: pid=4348 uid=10079 gids={50079, 3003, 5012}
D/PMS     (  913): releaseWL(42686c30): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=25 [4][1][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1938/10021)
,E/PhoneMonitor( 4348): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4348): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/Process (  913): killProcessQuiet, pid=3965
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  913): Killing 3965:com.htc.sdm/u0a81 (adj 15): empty #17
,I/ContactAccountLoggerTas( 2826): canRun() : Opted Out
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.setupwizard (4348/10079)
I/ActivityManager(  913): Recipient 3856
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.setupwizard (4348/10079)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.setupwizard (4348/10079)
,I/Search.GservicesUpdateTask( 2826): Updating Gservices keys
D/PMS     (  913): acquireWL(424e8e70): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(42459800): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(424e8e70): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/DownloadManager( 1938): Download 303 finished with status SUCCESS
,I/CheckinService( 2184): Checkin interval check for package: unspecified last checkin: 1454082574615 min interval config: 0 actual interval: 6256
D/PMS     (  913): releaseWL(42828488): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/CheckinService( 2184): Checking schedule, now: 1454082580887 next: 1454082604583
,I/CheckinService( 2184): active receiver: disabled
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
I/ActivityManager(  913): Delay finish: com.google.android.apps.plus/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
D/PMS     (  913): releaseWL(42459800): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=4143, uid=10160, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=4143, uid=10160, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=4143, uid=10160, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=4143, uid=10160, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=4143, uid=10160, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=4143, uid=10160, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=4143, uid=10160, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=4143, uid=10160, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=4143, uid=10160, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=4143, uid=10160, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=4143, uid=10160, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=4143, uid=10160, userID:0
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ContactAccountLoggerTas( 2826): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2826): canRun() : Opted Out
I/ActivityManager(  913): Recipient 3965
,I/ContactAccountLoggerTas( 2826): canRun() : Opted Out
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 1372): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1372): [NET] getaddrinfo-,err=8
D/libc    ( 1372): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1372): [NET] getaddrinfo-, 1
,D/libc    ( 1372): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =31d +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1372): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1372): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1372): [NET] getaddrinfo-,err=8
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2184, uid=10029, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2184, uid=10029, userID:0
,I/CheckinService( 2184): Done disabling old GoogleServicesFramework version
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2184, uid=10029, userID:0
,D/libc    ( 1372): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1372): [NET] getaddrinfo-,err=8
D/libc    ( 1372): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1372): [NET] getaddrinfo-,err=8
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [8][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1117): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,I/ContactAccountLoggerTas( 2826): canRun() : Opted Out
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
I/ActivityManager(  913): Resuming delayed broadcast
,D/PMS     (  913): acquireWL(42815238): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Delay finish: com.google.android.gms/.checkin.CheckinService$Receiver
,D/PMS     (  913): acquireWL(42769800): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2184): Checkin interval check for package: unspecified last checkin: 1454082574615 min interval config: 0 actual interval: 6927
,D/PMS     (  913): releaseWL(42815238): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2184): Checking schedule, now: 1454082581546 next: 1454082604583
,I/CheckinService( 2184): active receiver: disabled
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
I/ActivityManager(  913): Resuming delayed broadcast
D/PMS     (  913): releaseWL(42769800): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
,I/SystemUpdateService( 2184): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 2184): onCreate
,D/SystemUpdateService( 2184): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
D/PMS     (  913): acquireWL(42716328): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  913): Delay finish: com.google.android.gms/.update.SystemUpdateService$Receiver
,I/SystemUpdateService( 2184): cancelUpdate (empty URL)
,I/SystemUpdateService( 2184): active receiver: disabled
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
,D/SystemUpdateService( 2184): onDestroy
I/ActivityManager(  913): Resuming delayed broadcast
D/PMS     (  913): releaseWL(42716328): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 2184): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,E/DynamiteModule( 2184): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 2184): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1.apk", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip"],nativeLibraryDirectories=[/data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /vendor/lib, /system/lib]]
E/DynamiteModule( 2184): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 2184): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/DynamiteModule( 2184): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/DynamiteModule( 2184): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 2184): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 2184): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 2184): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 2184): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 2184): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 2184): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/DynamiteModule( 2184): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/DynamiteModule( 2184): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/DynamiteModule( 2184): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 2184): 	at android.os.Looper.loop(Looper.java:157)
E/DynamiteModule( 2184): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DynamiteModule( 2184): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DynamiteModule( 2184): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DynamiteModule( 2184): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DynamiteModule( 2184): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DynamiteModule( 2184): 	at dalvik.system.NativeStart.main(Native Method)
I/DynamiteModule( 2184): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 2184): Selected local version of com.google.android.gms.flags
,I/ActivityManager(  913): Delay finish: com.google.android.gms/.icing.service.SystemEventReceiver
,D/PMS     (  913): acquireWL(4273b7b0): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
,I/HtcModeClient( 1528): handler message = 4011
,E/HtcModeClient( 1528): Check connection and retry 7 times.
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
,D/PMS     (  913): releaseWL(4273b7b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Resuming delayed broadcast
,I/ActivityManager(  913): Delay finish: com.google.android.gms/.security.snet.SnetReceiver
,D/SystemEventReceiver( 2184): Received GSERVICES_CHANGED broadcast
I/ActivityManager(  913): Resuming delayed broadcast
,I/OcrUtils( 2184): Updating ocr activity enabled=false
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=2184, uid=10029, userID:0
,I/ActivityManager(  913): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
,D/PMS     (  913): acquireWL(42777a88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 913 1000 null
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  913): Resuming delayed broadcast
,D/PMS     (  913): acquireWL(426dc370): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 913 1000 WorkSource{10029}
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,I/IntentController( 1122): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  913): releaseWL(42777a88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/PMS     (  913): acquireWL(42768130): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 913 1000 null
D/PMS     (  913): releaseWL(42768130): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.social.location.service.LocationSharingSettingInjectorService, state=2, flag=1, pid=1230, uid=10029, userID:0
,W/ActivityManager(  913): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=2184, uid=10029, userID:0
,D/OcrModelManager( 2184): Updating downloaded model state (gservices changed)
,D/GCM     ( 1372): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,D/PhoneStatusBar( 1122): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,I/ActivityManager(  913): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,I/ActivityManager(  913): Resuming delayed broadcast
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
,D/PMS     (  913): acquireWL(42320770): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 913 1000 null
,D/PMS     (  913): releaseWL(426dc370): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
,I/IntentController( 1122): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  913): releaseWL(42320770): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1122): removeIcon slot=sync_active index=7 viewIndex=0
,E/dalvikvm( 1230): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.contextmanager.m.a.az.i
,W/dalvikvm( 1230): VFY: unable to resolve check-cast 57 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/contextmanager/m/a/az;
,W/dalvikvm( 1230): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/PMS     (  913): acquireWL(4277cfa0): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
,W/AlarmManager(  913): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{423d7c28: PendingIntentRecord{427f1d58 com.google.android.gms startService}}) : type=2 triggerAtTime=315360069107 win=-1 tElapsed=315360069107 maxElapsed=551880069107 interval=0 standalone=false
,D/WIFI_ICON( 1122): WifiActivity: 1
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/GCoreUlr( 1230): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1230): DispatchingService.onCreate()
,D/PMS     (  913): acquireWL(42828488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
,W/GeofencerStateMachine( 1230): Ignoring removeGeofence because network location is disabled.
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
D/PMS     (  913): acquireWL(428277e8): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(4280e048): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(4280e048): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): releaseWL(42828488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/ctxmgr  ( 1230): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,I/GCoreUlr( 1230): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,D/PMS     (  913): acquireWL(42754ea8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  913): releaseWL(42754ea8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,W/ctxmgr  ( 1230): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10029, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1230): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
D/PMS     (  913): releaseWL(4277cfa0): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(42717338): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/PMS     (  913): releaseWL(42717338): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  913): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=4397 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/GCoreUlr( 1230): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/PMS     (  913): acquireWL(425a8f10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 4397): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3823): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3823): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3823): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3823): Cust_ConnectToPC   : spcsc>false
D/        ( 3823): Cust_ConnectToPC   : IPT>true
,D/        ( 3823): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3823): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3823): Index of the first 1 = -1
I/GCoreUlr( 1230): Unbound from all location providers
,I/GCoreUlr( 1230): Place inference reporting - stopped
W/Settings( 3823): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3823): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3823): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3823): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3823): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  913): releaseWL(425a8f10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 3823): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  913): releaseWL(428277e8): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
D/SmartNS_Utility( 3823): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  913): acquireWL(42599720): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3874 10154 null
,I/ActivityManager(  913): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3874): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3874, uid=10154, userID:0
,I/MusicLeanback( 3874): Conditions not met for autocaching.
,I/MusicLeanback( 3874): Stop autocaching.
,D/PMS     (  913): releaseWL(42599720): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/GCoreUlr( 1230): DispatchingService.onDestroy()
,I/GCoreUlr( 1230): Stopping handler for UlrDispSvcFast
,W/ContextImpl( 3874): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/ActivityManager(  913): Resuming delayed broadcast
D/PMS     (  913): acquireWL(4254bc20): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 913 1000 null
,I/ActivityManager(  913): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMReceiver: pid=4414 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,D/PMS     (  913): acquireWL(4242e8c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
,D/PMS     (  913): acquireWL(4232f3b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 913 1000 null
,D/PMS     (  913): releaseWL(4242e8c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/GCoreUlr( 1230): Unbound from all location providers
,I/GCoreUlr( 1230): Place inference reporting - stopped
D/PMS     (  913): releaseWL(4254bc20): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
D/PMS     (  913): releaseWL(4232f3b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/Process (  913): killProcessQuiet, pid=4031
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4031:com.htc.task.gtask/u0a68 (adj 15): empty #17
D/PMS     (  913): acquireWL(424cba40): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(424cba40): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Recipient 4031
D/PMS     (  913): acquireWL(4248bb98): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(4248bb98): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 4414): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  913): Resuming delayed broadcast
,I/ActivityManager(  913): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4435 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/Process (  913): killProcessQuiet, pid=4053
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4053:com.htc.updater/u0a85 (adj 15): empty #17
,D/SyncApplication( 4435): Loading default preferences
,W/Resources( 4435): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
I/ActivityManager(  913): Recipient 4053
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  913): New client listening to asynchronous messages
,D/SyncApplication( 4435): Overriding preferences with custom values
,D/SyncApplication( 4435): Updating preferences succeeded
,E/SyncApplication( 4435): Application created.
D/VolumeInfo( 4435): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4435): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4435): Found 0 mount point(s)
,V/VolumeInfo( 4435): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4435): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4435): getNewCalendarAuthority()...
,D/SyncApplication( 4435): enableAppOperation()+
,D/VolumeInfo( 4435): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 4435): Can not create volume ID for unmounted volume null
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4435, uid=10008, userID:0
W/PackageManager(  913): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4435, uid=10008, userID:0
,W/PackageManager(  913): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 4435): enableAppOperation()-
D/HTCUtilities( 4435): isNeorSinged() + 
,D/HTCUtilities( 4435): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4435): isNeorSinged() return false
,D/CDMountReceiver( 4435): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4435): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4435): enable CD Auto-mount: true
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 4435): enable auto-mount
,D/HTCUtilities( 4435): enable auto-mount
,I/ActivityManager(  913): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,I/RemoteViews( 1122): com.nero.android.htc.sync (false,0)
D/MountService(  913): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  913): Resuming delayed broadcast
D/PMS     (  913): releaseWL(42748120): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,D/MountService(  913): mountISO: /system/etc/PCTOOL.ISO
,D/OnDemandProgressBar( 1122): release indeterminate drawable android.widget.OnDemandProgressBar{41caab98 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1122): com.nero.android.htc.sync 2 11 4 11
D/Process (  913): killProcessQuiet, pid=3729
I/RemoteViews( 1122): com.nero.android.htc.sync (false,0)
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4456 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  913): Killing 3729:com.htc.sense.mms/u0a65 (adj 15): empty #17
,D/OnDemandProgressBar( 1122): release indeterminate drawable android.widget.OnDemandProgressBar{41cb80b8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1122): com.nero.android.htc.sync 1 11 2 16
,D/CalendarApplication( 4456): onCreate
D/ProviderChangeReceiver( 4456): ---------------------------------------------------
,D/ProviderChangeReceiver( 4456): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4456): start to updateAlertNotification!
,D/Process (  913): killProcessQuiet, pid=4225
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  913): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4470 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  913): Killing 4225:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,D/AlertService( 4456): No fired or scheduled alerts
,D/HtcAlertUtils( 4456): -- cancelReminderNotification --
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  913): Recipient 4225
D/HtcAlertUtils( 4456): broadcastExistReminder!
,I/ActivityManager(  913): Recipient 3729
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4470): [4470/4470] onCreate()
W/ContextImpl( 4470): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  913): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  913): Resuming delayed broadcast
,W/ContextImpl( 4288): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
I/ActivityManager(  913): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/ActivityManager(  913): Resuming delayed broadcast
,D/ConnectivityService(  913): getAllNetworkInfo called by  (1938/10021)
,W/ContextImpl( 4288): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/DownloadManager( 1938): Download 305 starting
D/PMS     (  913): acquireWL(42828488): PARTIAL_WAKE_LOCK  DownloadManager 0x1 1938 10021 WorkSource{10016}
I/ActivityManager(  913): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
D/ConnectivityService(  913): getAllNetworkInfo called by  (1938/10021)
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1938/10021)
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [1][0][0]
,I/ActivityManager(  913): Resuming delayed broadcast
,I/DownloadManager( 1938): Ignoring Content-Length since Transfer-Encoding is also defined
D/ConnectivityService(  913): getAllNetworkInfo called by  (1938/10021)
,D/Process (  913): killProcessQuiet, pid=4101
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  913): Killing 4101:com.google.android.talk/u0a111 (adj 15): empty #17
,I/DownloadManager( 1938): Download 306 starting
D/PMS     (  913): acquireWL(41bdf760): PARTIAL_WAKE_LOCK  DownloadManager 0x1 1938 10021 WorkSource{10016}
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getAllNetworkInfo called by  (1938/10021)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1938/10021)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1938/10021)
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=10 [10][1][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): acquireWL(4231ec58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
,D/PMS     (  913): releaseWL(4231ec58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4236b780): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
,D/PMS     (  913): releaseWL(4236b780): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4247a7a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4492 uid=10041 gids={50041}
,I/ActivityManager(  913): Recipient 4101
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
I/DownloadManager( 1938): Download 305 finished with status SUCCESS
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/PMS     (  913): releaseWL(42828488): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
,D/PMS     (  913): releaseWL(4247a7a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4288): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/ActivityManager(  913): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
I/UpdateFetcherService( 4288): Update downloaded, starting installation
I/UpdateFetcherService( 4288): Started installation
,I/ActivityManager(  913): Resuming delayed broadcast
,I/DownloadManager( 1938): Ignoring Content-Length since Transfer-Encoding is also defined
,D/Process (  913): killProcessQuiet, pid=4169
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  913): Killing 4169:com.android.vending/u0a74 (adj 15): empty #17
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [8][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1938/10021)
,I/DownloadManager( 1938): Download 306 finished with status SUCCESS
D/PMS     (  913): releaseWL(41bdf760): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
I/ActivityManager(  913): Recipient 4169
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4288): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4288): Update downloaded, starting installation
,I/UpdateFetcherService( 4288): Started installation
I/ActivityManager(  913): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/ActivityManager(  913): Resuming delayed broadcast
,I/ConfigUpdateInstallReceiver(  913): Not installing, new version is <= current version
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [22][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1117): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,D/WIFI_ICON( 1122): WifiActivity: 3
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  913): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4513 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "sms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
,I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1277): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
I/PackageManager(  913):   Scheme: "smsto"
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "mms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "mmsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
,W/SystemReader( 1262): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "sms"
W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "smsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
,I/Prism.ItemManager( 4264): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 4264): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "mms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "mmsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
,E/ExternalAccountType( 1343): Unsupported attribute readOnly
,D/PhoneApp( 1250): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4513): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4513): MmsConfig.loadMmsSettings
,W/dalvikvm( 4513): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4513): VFY: unable to resolve instance field 36
,W/dalvikvm( 4513): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4513): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  913): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4536 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4513, uid=10111, userID:0
,W/Settings( 4513): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4513, uid=10111, userID:0
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4513, uid=10111, userID:0
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4513, uid=10111, userID:0
,I/SensorManager(  913): mEventCount = 600
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4513, uid=10111, userID:0
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4513, uid=10111, userID:0
D/PMS     (  913): acquireWL(42746a08): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4513 10111 null
,D/MessageFrequencyProvider( 4536): onCreate
I/ActivityManager(  913): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,V/GetPrviateResource( 4536): GetPrviateResource
,V/GetPrviateResource( 4536): GetPrviateResource
,D/MmsCustomizationProvider( 4536): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/Process (  913): killProcessQuiet, pid=3460
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,I/ActivityManager(  913): Killing 3460:com.htc.task/u0a71 (adj 15): empty #17
D/MmsCustomizationProvider( 4536): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4513): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 4513): MmsConfig.loadFromDatabase
,E/Babel   ( 4513): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4513): MmsConfig.loadFromResources
,E/Babel   ( 4513): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4513): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/Process (  913): killProcessQuiet, pid=4264
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  913): releaseWL(42746a08): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  913): Resuming delayed broadcast
I/ActivityManager(  913): Killing 4264:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/[PluginManager]RegisterService( 1319): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1319): handle notify Blinkfeed plugin client changed
I/ActivityManager(  913): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  913): Recipient 4264
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Resuming delayed broadcast
,W/PackageManager(  913): Unable to load service info ResolveInfo{42732cf8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  913): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  913): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  913): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  913): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  913): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  913): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  913): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  913): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  913): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  913): 	at dalvik.system.NativeStart.main(Native Method)
,I/IcingCorporaProvider( 2826): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  913): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/MessageCustFlag( 4536): sense_version=6.0
,D/BTAccessoryUtil( 4536): createReceiver
,D/BTAccessoryUtil( 4536): registerReceiver return intent = null
D/MessageCustFlag( 4536): sku_id=99
,W/SystemReader( 4536): Cannot find message_ambs_application_id, use default value instead
I/ActivityManager(  913): Recipient 3460
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ProviderInstaller( 4513): Installed default security provider GmsCore_OpenSSL
D/Messaging( 4536): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4536): networkCode: 
D/MessageCustFlag( 4536): sku_id=99
D/MmsConfig( 4536): SIE smsPri: null
,D/MmsConfig( 4536): networkCode: 
D/PMS     (  913): acquireWL(427687b8): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(427687b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4275abb8): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
D/HtcTelephonyCapability( 4536): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4536): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4536): getRATByHtcTelephonyCapability:1
W/SystemReader( 4536): Cannot find qct_8960_interface, use default value instead
,D/PMS     (  913): releaseWL(427415c8): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/PMS     (  913): releaseWL(4275abb8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Resuming delayed broadcast
,D/PMS     (  913): acquireWL(427e7f60): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  913): acquireWL(427e9960): PARTIAL_WAKE_LOCK  AsyncService 0x1 4143 10160 null
,D/PMS     (  913): releaseWL(427e9960): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  913): releaseWL(427e7f60): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Resuming delayed broadcast
,I/ActivityManager(  913): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  913): acquireWL(42793a00): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42793a00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Resuming delayed broadcast
,I/ActivityManager(  913): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4563 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/PMS     (  913): acquireWL(4279a1d8): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4279ab78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4279ab78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): releaseWL(4279a1d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4279fc70): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(4279fc70): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(427a1bb0): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(427a1bb0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(427a3668): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(427a3668): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 4563): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4563, uid=10074, userID:0
,D/RemoteDisplayProvider(  913): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  913): start
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/Finsky  ( 4563): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/IcingCorporaProvider( 2826): UpdateCorporaTask done [took 257 ms] updated apps [took 257 ms] 
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1122): closing low battery warning: level=100
,D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/ConnectivityService(  913): getAllNetworkInfo called by com.android.vending (4563/10074)
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/GCoreNlp( 1230): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  913): applying state to connected service
D/PMS     (  913): acquireWL(4283b428): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/LocationProviderProxy(  913): applying state to connected service
D/PMS     (  913): releaseWL(4283b428): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4283cd78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(4283cd78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4563): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
D/PMS     (  913): acquireWL(4283ea70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(4283ea70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(4283ff30): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4563): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/PMS     (  913): releaseWL(4283ff30): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getAllNetworkInfo called by com.android.vending (4563/10074)
,D/Finsky  ( 4563): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4563): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 4563): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4563): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4563): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4563): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4563): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4563): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4563, uid=10074, userID:0
,D/Ads     ( 4563): Skipping gmscore version check
,D/Finsky  ( 4563): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4563): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4563): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 4563): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/WIFI_ICON( 1122): WifiActivity: 1
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/Finsky  ( 4563): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/Process (  913): killProcessQuiet, pid=3743
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/PackageBroadcastService( 2184): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2184): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  913): Killing 3743:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,D/PMS     (  913): acquireWL(427d6230): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2184): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  913): Recipient 3743
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV2    ( 4143): Thread[GAThread,5,main]: No campaign data found.
,I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41b99cb0 +
,I/Prism.WidgetManager( 1277): onLoadItems() +
,E/Prism.WidgetManager( 1277): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1277): onLoadItems() -
,I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41b99cb0 -
I/ActivityManager(  913): Waited long enough for: ServiceRecord{4281cea8 u0 com.htc.musicenhancer/.EnhancerService}
,D/WIFI_ICON( 1122): WifiActivity: 3
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/Icing   ( 2184): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 2184): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2184): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  913): releaseWL(427d6230): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1250): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1250): -- N1 =0
,D/PhoneApp( 1250): -- N2 =0
,D/PhoneApp( 1250): -- N3 =0
,I/HtcModeClient( 1528): handler message = 4011
,E/HtcModeClient( 1528): Check connection and retry 8 times.
,D/Messaging( 4536): mNeedToUpdateDate2 start
,D/MmsConfig( 4536): packageName: com.htc.vvm.att does not exist
,D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/MmsSmsV2Provider( 1250):  phoneType = -1
,D/MmsSmsV2Provider( 1250): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/ReportIndicatorCache( 4536): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4536): 
D/MmsAsyncWorkHandler( 4536): HM tk = 20001
,D/ReportIndicatorCache( 4536): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4536): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b0f2d0
,I/Messaging( 4536): mccmnc> 
,D/DraftCache( 4536): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4536): [DraftCache/1] refresh
,D/MmsConfig( 4536): networkCode: 
,D/Messaging( 4536): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1250): sku_id=99
,D/PhoneStorageUtil( 4536): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4536): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4536): createReceiver
,D/DraftCache( 4536): [DraftCache/451] rebuildCache
,D/MessageCustFlag( 4536): sense_version=6.0
,D/Jerry   ( 4536): start to preload cursor >>>>>>>
,D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1250):  phoneType = -1
,D/MmsSmsV2Provider( 1250): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1250): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
V/MmsProvider( 1250): Update uri=content://mms, match=0
,V/MmsProvider( 1250): selection=st=129 AND m_type!=134
,D/Messaging( 4536): Reset downloading state: 0
V/MmsSystemEventReceiver( 4536): TransactionService is going to be woken up.
,D/Messaging( 4536): mNeedToUpdateDate2: false
D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/Jerry   ( 1250): URI_DRAFT
,V/TransactionService( 4536): 1-Creating TransactionService
D/DraftCache( 4536): hasDraft() = false mNeedNotifyChange = true
V/TransactionService( 4536): onStartCommand: 1
,D/MmsSystemEventReceiver( 4536): unRegisterForConnectionStateChanges
V/TransactionService( 4536): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4536): Loading previous transactions.
D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1250):  phoneType = -1
,D/DraftCache( 4536): [DraftCache/451] rebuildCache time: 4
,D/MmsAsyncWorkHandler( 4536): 
D/MmsAsyncWorkHandler( 4536): HM tk = 20002
,D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/MmsSmsV2Provider( 1250):  phoneType = -1
,D/MmsSmsV2Provider( 1250): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/Messaging( 4536): ViewCache CreatePreload
,D/Messaging( 4536): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1250): device_type: 1
,D/Cust_MMSMS( 4536): _has_set_default_values_2=true
D/TransactionService( 4536): Force set service start id to 1
V/TransactionService( 4536): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4536): unRegisterForConnectionStateChanges
,D/TransactionService( 4536): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4536): Destroying TransactionService
,D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/AccFlag ( 1250): sku_id=99
,V/TransactionService( 4536): 4-Handling incoming message: { when=-1ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MsgPreferenceUtils( 4536): def_index: 0
,D/MsgPreferenceUtils( 4536): globalIndex = 1
D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/MmsSmsV2Provider( 1250):  phoneType = -1
,D/MmsSmsV2Provider( 1250): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/MsgPreferenceUtils( 4536): phone state: true
D/MsgPreferenceUtils( 4536): sd state: false
,D/MsgPreferenceUtils( 4536): vIndex = 0
,D/Messaging( 4536): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1250): sku_id=99
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1117): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,D/WIFI_ICON( 1122): WifiActivity: 0
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiDataStallTracker(  913): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  913): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  913): updateDataStallInfo: mDataStallTxRxSum={txSum=218 rxSum=206} preTxRxSum={txSum=148 rxSum=142}
D/WifiDataStallTracker(  913): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  913): onDataStallAlarm: tag=22751 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  913): startDataStallAlarm: tag=22752 delay=15s
D/PMS     (  913): acquireWL(4270c8b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
V/AlarmManager(  913): sending alarm PendingIntent{426883d0: PendingIntentRecord{42401290 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=74801, Int=0
D/PMS     (  913): releaseWL(4270c8b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1122): WifiActivity: 1
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/GAV4    ( 4513): Thread[GAThread,5,main]: No campaign data found.
,D/Finsky  ( 4563): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4563): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  913): acquireWL(426ee108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10074}
V/AlarmManager(  913): sending alarm PendingIntent{425c11d0: PendingIntentRecord{42573f60 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454082590442, Int=0
D/PMS     (  913): releaseWL(426ee108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.android.vending (4563/10074)
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4563): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4563): [NET] getaddrinfo-,err=8
D/libc    ( 4563): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4563): [NET] getaddrinfo-, 1
D/libc    ( 4563): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =fc9a +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4563): [NET] getaddrinfo_proxy-, success
I/global  ( 4563): call createSocket() return a new socket.
D/libc    ( 4563): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4563): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1117): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,D/WIFI_ICON( 1122): WifiActivity: 3
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/libc    ( 4563): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4563): [NET] getaddrinfo-,err=8
,W/PackageSettings(  913): Skipping PackageSetting{41fd2c98 com.example.hello/10397} due to missing metadata
,W/PackageSettings(  913): Skipping PackageSetting{41becdc8 com.test.thalitest/10389} due to missing metadata
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4563): untagSocket(69) failed with errno -22
,D/Finsky  ( 4563): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4563): untagSocket(69) failed with errno -22
,I/HtcModeClient( 1528): handler message = 4011
,E/HtcModeClient( 1528): Check connection and retry 9 times.
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4563): untagSocket(69) failed with errno -22
,D/ConnectivityService(  913): getNetworkInfo networkType=0 called by com.android.vending (4563/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4563/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4563/10074),
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4563/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4563/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4563/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4563/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4563/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4563/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4563/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4563/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4563/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4563/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4563/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4563/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4563/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4563/10074)
,D/Finsky  ( 4563): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  913): acquireWL(426d7920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10074}
,V/AlarmManager(  913): sending alarm PendingIntent{427b32d8: PendingIntentRecord{4267af38 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1454082592665, Int=0
,D/WearableService( 1230): callingUid 10029, callindPid: 1230
,D/Finsky  ( 4563): [482] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1230): client connected with version: 8296000
D/PMS     (  913): acquireWL(42637818): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4563 10074 null
D/PMS     (  913): releaseWL(426d7920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 4563): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4563): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4563): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4563): [NET] getaddrinfo-,err=8
D/libc    ( 4563): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4563): [NET] getaddrinfo-, 1
,D/libc    ( 4563): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =bfba +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 37
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4563): [NET] getaddrinfo_proxy-, success
,I/SensorManager(  913): mEventCount = 750
,D/PMS     (  913): releaseWL(42637818): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=8 [73][6][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1117): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
D/WifiStateMachine(  913): [ScoreAP] + current TXpacket:351, mTXpacketCount:198, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  913): [ScoreAP] + fetchRssiAndLinkSpeedNative: Update RSSI:-51 and linkspeed:72 in database
,D/WifiApDatabaseHandler(  913): updateConnectedAP...
,D/WIFI_ICON( 1122): WifiActivity: 1
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1117): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,I/HtcModeClient( 1528): handler message = 4011
,E/HtcModeClient( 1528): Check connection and retry 10 times.
,D/WIFI_ICON( 1122): WifiActivity: 0
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/AutoSetting( 1319): service - has update message, not stop
,D/AutoSetting( 1319): service - mHandler: update timezone
,D/AutoSetting( 1528): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1528): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  913): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  913): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1528): service - onCreate()
,D/AutoSetting( 1528): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1528): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1528): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1528): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1528): service - mHandler: update timezone
,D/AutoSetting( 1528): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1528): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1528): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1528): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1122): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1122): release indeterminate drawable android.widget.OnDemandProgressBar{41f2f2f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1122): com.htc.htclocationservice 2 7 2 11
,D/WIFI_ICON( 1122): WifiActivity: 1
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1117): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,D/ContactMessageStore( 1250): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1250): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  913): acquireWL(42734770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=86555, Int=0
I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,I/ClockThread( 1122): now=1454082600034 next=59966
,D/PMS     (  913): releaseWL(42734770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1122): WifiActivity: 0
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WIFI_ICON( 1122): WifiActivity: 1
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1528): handler message = 4011
,E/HtcModeClient( 1528): Check connection and retry 11 times.
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1117): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,D/PMS     (  913): acquireWL(42624020): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42624020): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(427243e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
D/WifiDataStallTracker(  913): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  913): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  913): updateDataStallInfo: mDataStallTxRxSum={txSum=291 rxSum=272} preTxRxSum={txSum=218 rxSum=206}
D/WifiDataStallTracker(  913): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  913): onDataStallAlarm: tag=22752 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  913): startDataStallAlarm: tag=22753 delay=15s
V/AlarmManager(  913): sending alarm PendingIntent{426ec5c8: PendingIntentRecord{42401290 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=89808, Int=0
D/PMS     (  913): releaseWL(427243e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1122): WifiActivity: 0
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1122): WifiActivity: 1
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1117): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,I/SensorManager(  913): mEventCount = 900
,W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/HtcModeClient( 1528): handler message = 4011
,E/HtcModeClient( 1528): Check connection and retry 12 times.
,D/WIFI_ICON( 1122): WifiActivity: 0
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1117): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,D/WifiStateMachine(  913): [ScoreAP] + current TXpacket:352, mTXpacketCount:351, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  913): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1122): WifiActivity: 1
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1117): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,I/HtcModeClient( 1528): handler message = 4011
,E/HtcModeClient( 1528): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1528): Don't start project servcice
,D/HtcModeClient( 1528): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1528): connectState: CONNECTION_READY = false
,D/SilentMusic( 1528): call stop
,D/HtcModeClient( 1528): close connection
,W/HtcModeClient( 1528): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1528): read the terminate packet, so break
,D/PMS     (  913): acquireWL(4276a148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10029}
,V/AlarmManager(  913): sending alarm PendingIntent{427f5318: PendingIntentRecord{425d6408 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454082604583, Int=522937000
,V/AlarmManager(  913): sending alarm PendingIntent{42576090: PendingIntentRecord{427f1df8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454082607019, Int=0
,D/PMS     (  913): acquireWL(42708b30): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4653 uid=10078 gids={50078}
,V/AlarmManager(  913): sending alarm PendingIntent{425d2e70: PendingIntentRecord{42561858 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454082612766, Int=60000
,D/PMS     (  913): releaseWL(4276a148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  913): acquireWL(4275aea8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2184): Checkin interval check for package: unspecified last checkin: 1454082574615 min interval config: 0 actual interval: 38197
D/PMS     (  913): releaseWL(42708b30): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2184): Checking schedule, now: 1454082612822 next: 1454082604583
,I/CheckinService( 2184): active receiver: enabled
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2184, uid=10029, userID:0
,I/ActivityManager(  913): Waited long enough for: ServiceRecord{426d5730 u0 com.htc.htclocationservice/.AutoSettingService}
,I/CheckinService( 2184): Preparing to send checkin request
,I/EventLogService( 2184): Accumulating logs since 1454082567944
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/SMSBackup( 4653): SMSBackupAgentService started
,D/SMSBackup( 4653): Checking restore status
,D/SMSBackup( 4653): Restore complete
,D/SMSBackup( 4653): cancelCheckAlarm
,D/SMSBackup( 4653): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
,I/CheckinRequestBuilder( 2184): Checkin reason type: 3 attempt count: 1
I/ActivityManager(  913): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2184): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  913): getNetworkInfo networkType=9 called by com.google.android.gms (2184/10029)
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  913): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4669 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/Finsky  ( 4563): [473] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,W/dalvikvm( 4669): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/Finsky  ( 4563): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  913): killProcessQuiet, pid=4319
,W/dalvikvm( 4669): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/MultiDex( 4669): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4669): install
,I/MultiDex( 4669): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/ActivityManager(  913): Killing 4319:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/MultiDex( 4669): loading existing secondary dex files
,I/MultiDex( 4669): load found 3 secondary dex files
,I/MultiDex( 4669): install done
I/ActivityManager(  913): Recipient 4319
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4669): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4669): VFY: unable to resolve instance field 36
,W/dalvikvm( 4669): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4669): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/LightsService(  913): setLight #0: color=#25
,I/ProviderInstaller( 4669): Installed default security provider GmsCore_OpenSSL
V/LightsService(  913): setLight #0: color=#21
,D/WearableService( 1230): callingUid 10029, callindPid: 1230
,E/MDM     ( 1230): [126] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2184): Restart initialization of location
D/AuthorizationBluetoothService( 1372): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/dalvikvm( 4669): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,E/AuthorizationBluetoothService( 1372): Proximity feature is not enabled.
,W/dalvikvm( 4669): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 4669): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/dalvikvm( 4669): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4669): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4669): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4669): Link of class 'Lcom/google/android/gms/common/j/c;' failed
V/LightsService(  913): setLight #0: color=#1b
,W/GCoreFlp( 1230): No location to return for getLastLocation()
,W/FusedLocationProvider( 1230): location=null
D/PMS     (  913): acquireWL(42752cc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(42752cc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
V/LightsService(  913): setLight #0: color=#14
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4669): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  371): PrepareKeyRequest: nonce=3908225494
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/Adreno-EGL( 4669): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4669): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4669): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4669): Local Branch: 
I/Adreno-EGL( 4669): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4669): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4669):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=1794136760
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/Adreno-EGL( 4669): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4669): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4669): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4669): Local Branch: 
I/Adreno-EGL( 4669): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4669): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4669):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4669): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4669): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4669): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4669): Local Branch: 
I/Adreno-EGL( 4669): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4669): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4669):                  aa63bbd948f41d15fc72f585e
,D/WIFI_ICON( 1122): WifiActivity: 0
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/Settings( 4669): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (4669/10029)
,I/CheckinRequestBuilder( 2184): Classify the device as Phone.
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2184): [NET] getaddrinfo-,err=8
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2184): [NET] getaddrinfo-, 1
,D/libc    ( 2184): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/libc    (  363): [NET] +++++ res_nsend xid =37af +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2184): [NET] getaddrinfo_proxy-, success
D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1117): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  913):    returned true
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2184): [NET] getaddrinfo-,err=8
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2184): Sending checkin request (12143 bytes)
,I/CheckinRequestBuilder( 2184): Checkin reason type: 3 attempt count: 1
I/ActivityManager(  913): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2184): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  913): getNetworkInfo networkType=9 called by com.google.android.gms (2184/10029)
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=23 [17][4][0]
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,I/CheckinRequestBuilder( 2184): Classify the device as Phone.
,I/CheckinTask( 2184): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2184): Checking schedule, now: 1454082615480 next: 1454605552475
,I/CheckinService( 2184): active receiver: disabled
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
,D/CheckinService( 2184): Recording last checkin time for package unspecified as 1454082615498
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
,D/PMS     (  913): releaseWL(4275aea8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WIFI_ICON( 1122): WifiActivity: 3
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1122): WifiActivity: 1
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/SensorManager(  913): mEventCount = 1050
,D/WIFI_ICON( 1122): WifiActivity: 0
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1117): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,D/WifiDataStallTracker(  913): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  913): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  913): acquireWL(423fe5d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
V/AlarmManager(  913): sending alarm PendingIntent{427227b0: PendingIntentRecord{42401290 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=104816, Int=0
,D/PMS     (  913): releaseWL(423fe5d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/WifiDataStallTracker(  913): updateDataStallInfo: mDataStallTxRxSum={txSum=308 rxSum=288} preTxRxSum={txSum=291 rxSum=272}
D/WifiDataStallTracker(  913): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  913): onDataStallAlarm: tag=22753 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  913): startDataStallAlarm: tag=22754 delay=15s
,D/Process (  913): killProcessQuiet, pid=4348
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4348:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 4348
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PMS     (  913): Going to sleep due to screen timeout...
,I/SensorManager(  913): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4221e5b8
D/WirelessDisplayService(  913): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  913): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  913): disable: get sensor name = CM36282 Light sensor
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 2
W/SensorService(  913): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  913): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  913): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4221e5b8, eanble = 0, strlen(mName) = 59
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  913): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4237bce0
W/SensorService(  913): Listener[1] = com.htc.smartdim.sensor_eye@4273d950
,W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  913): mWirelessDisplayManager is null
W/BatSI   (  913): Couldn't get kernel wake lock stats
V/LightsService(  913): setLight #2: color=#0
D/qdlights(  913): set_light_buttons_func: on=0 brightness=0
V/LightsService(  913): setLight #0: color=#0
,D/SurfaceControl(  913): Excessive delay in blankDisplay() while turning screen off: 314ms
,W/PnPMgr  (  350): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  913): nativeSetInteractive:false
D/PMS     (  913): nativeSetInteractive:false done
D/PMS     (  913): nativeSetAutoSuspend:true
D/PMS     (  913): nativeSetAutoSuspend:true done
D/HABCtrl (  913): TPE algorithm. remove timeout.
D/PMS     (  913): OOBE c monitor 11
D/NfcService( 1262): ScreenObserver: OFF
,D/NfcService( 1262): applyRouting - 0
V/KeyguardServiceDelegate(  913): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42816da0)
,D/NfcService( 1262): applyRouting -2
I/InputManager(  913): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  913): screenObserver, isScreenOn=false
I/InputMethodManagerService(  913): Disable input method client, pid=1277
D/PMS     (  913): acquireWL(426d5280): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1262 1027 null
D/PMN     (  913): wakingUp
D/PMS     (  913): releaseWL(426d5280): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  913): **** SHOWN CALLED ****
,I/IntentController( 1122): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/WindowManager(  913): No lock screen! windowToken=null
D/PMN     (  913): onScreenOn
D/PMS     (  913): acquireWL(4269bfc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
D/PMS     (  913): releaseWL(4269bfc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
W/XT9_C   ( 1216): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1216): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1216): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1216): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WirelessDisplayService(  913): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/MtpService( 1938): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/WirelessDisplayService(  913): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  913): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  913): BroadcastReceiver::onReceive-
,D/NfcService( 1262): applyRouting - 0
,D/MtpService( 1938): [MTP][onReceive]-
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
,I/HtcPowerSaver(  913): >> updateStatus
,D/AutoSetting( 1319): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1262): applyRouting -2
,D/AutoSetting( 1319): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/PMS     (  913): acquireWL(4282d940): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1262 1027 null
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
D/PMS     (  913): releaseWL(4282d940): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AlarmManager(  913): ACTION_SCREEN_ON
I/AlarmManager(  913): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  913): [AlarmQueuing] done recovering
I/AlarmManager(  913): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  913): [AlarmQueuing] done EPS screen off alarm recovering
D/TetherSettings( 3823): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3823): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3823): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3823): Cust_ConnectToPC   : spcsc>false
D/        ( 3823): Cust_ConnectToPC   : IPT>true
D/        ( 3823): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3823): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3823): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3823): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3823): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3823): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3823): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WirelessDisplayService(  913): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  913): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  913): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  913): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  913): startDataStallAlarm: tag=22755 delay=15s
,I/SmartNS_PSService( 3823): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3823): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3823):  defaultType:0
,I/ClockThread( 1122): stop update clock
,D/WifiNative-wlan0(  913): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
V/NotificationService(  913): batLight: Full, plugged
V/LightsService(  913): setLight #8: color=#c8c800
D/qdlights(  913): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  913): setLight #8: color=#c800
D/qdlights(  913): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
I/wpa_supplicant( 1117): SET_SCREEN_ON:On
I/wpa_supplicant( 1117): htc_wext_set_keepalive +
I/wpa_supplicant( 1117): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1117): getPrivFuncNum +	
I/wpa_supplicant( 1117): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1117): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1117): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1117): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1117): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  913):    returned true
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
V/NotificationService(  913): batLight: Full, plugged
V/LightsService(  913): setLight #8: color=#c8c800
D/qdlights(  913): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  913): setLight #8: color=#c800
D/qdlights(  913): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  371): ParamSet string: screen_state=on
D/WirelessDisplayService(  913): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  913): updateScreenOn: false
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1117): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  913):    returned true
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4397): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1117): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  913):    returned true
D/WifiStateMachine(  913): [ScoreAP] + current TXpacket:374, mTXpacketCount:352, avgLinkspeed:72,mAvgTxRate72
D/SmartSyncUtils( 4397): isEpsOn(), nState = 0
D/WifiStateMachine(  913): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
D/PMS     (  913): acquireWL(42710160): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4397 1000 null
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/SmartSyncUtils( 4397): getMobilePolicyEnabled, result = true
D/PMS     (  913): releaseWL(42710160): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PMS     (  913): acquireWL(426aff88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(426aff88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(426a95a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(426a95a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1766): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1766): onScreenOn: 1454082620886
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1766): onScreenOn: 1454082620886
,I/SensorManager(  913): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4237bce0
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  913): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 2
W/SensorService(  913): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  913): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  913): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4237bce0, eanble = 0, strlen(mName) = 91
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  913): Listener[0] = com.htc.smartdim.sensor_eye@4273d950
,W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/FeedHostManager( 1277): [onPause]
,I/FeedProviderManager( 1277): onPause
I/FeedHostManager( 1277): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bf4f80
I/SocialFeedProvider( 1277): +onPause
,I/SocialFeedProvider( 1277): -onPause
D/PMN     (  913): goingToSleep
D/PMS     (  913): acquireWL(42796e28): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 913 1000 null
D/WifiDataStallTracker(  913): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  913): stopDataStallAlarm: current tag=22755 mDataStallAlarmIntent=PendingIntent{4245d668: PendingIntentRecord{42401290 android broadcastIntent}}
,D/WifiNative-wlan0(  913): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  913): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1117): SET_SCREEN_ON:Off
I/wpa_supplicant( 1117): htc_wext_set_keepalive +
I/wpa_supplicant( 1117): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1117): getPrivFuncNum +	
I/wpa_supplicant( 1117): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1117): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1117): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1117): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1117): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  913):    returned true
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/AlarmManager(  913): ACTION_SCREEN_OFF
I/AlarmManager(  913): [AlarmQueuing] screen off now: 
I/AlarmManager(  913): [AlarmQueuing] data connection: true
I/AlarmManager(  913): [AlarmQueuing] wifi connection: true
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
D/PMS     (  913): acquireWL(4261e248): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 913 1000 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  913): releaseWL(42796e28): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/ContextImpl( 4397): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/NetworkPolicy(  913): updateScreenOn: false
,D/SmartSyncUtils( 4397): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4397): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4397): getMobilePolicyEnabled, result = true
,D/wpa_supplicant( 1117): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
I/SensorManager(  913): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4273d950
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
D/WifiService(  913): New client listening to asynchronous messages
,W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  913): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 1
W/SensorService(  913): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  913): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4273d950, eanble = 0, strlen(mName) = 36
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  913): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 0
W/SensorService(  913): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4273d950, eanble = 0, strlen(mName) = 36
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WifiNative-wlan0(  913):    returned true
I/SensorManager(  913): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4273d950
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  913): releaseWL(4261e248): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
E/ActivityThread(  913): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4273e050 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  913): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4273e050 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  913): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  913): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  913): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  913): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  913): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  913): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  913): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  913): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  913): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  913): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  913): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  913): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  913): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  913): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  913): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  913): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  913): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  913): 	at dalvik.system.NativeStart.main(Native Method)
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/ContactMessageStore( 1250): start background delete task...
D/ContactMessageStore( 1250): size: 0 , 0
,D/ContactMessageStore( 1250): Background delete complete
,D/AutoSetting( 1319): service - mHandler: cancel location update
,D/AutoSetting( 1319): service -           changes count: 0
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] getTotalRam: 1873 Mb
D/PMS     (  913): acquireWL(42773408): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(42773408): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(42644ee8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1766): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1766): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1766): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1766): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1766): onScreenOff
D/PMS     (  913): releaseWL(42644ee8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/SystemReader( 1262): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/PMS     (  913): acquireWL(427ef120): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4513 10111 null
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "sms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "smsto"
W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
I/dalvikvm-heap( 1277): Grow heap (frag case) to 13.257MB for 53840-byte allocation
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1277): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "mms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
,I/Launcher( 1277): Deferring update until onResume
,D/Launcher( 1277): waitUntilResume // bindAppsUpdated
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "mmsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
,D/PMS     (  913): releaseWL(427ef120): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "sms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
,E/ExternalAccountType( 1343): Unsupported attribute readOnly
,I/[PluginManager]RegisterService( 1319): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1319): handle notify Blinkfeed plugin client changed
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "smsto"
,I/IcingCorporaProvider( 2826): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "mms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "mmsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
,D/PhoneApp( 1250): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/PMS     (  913): acquireWL(4278d0a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4143 10160 null
,D/PMS     (  913): releaseWL(4278d0a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  913): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,I/ActivityManager(  913): Resuming delayed broadcast
,D/PMS     (  913): acquireWL(4278f2f0): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(4278f2f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(42792090): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2184): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  913): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/PackageBroadcastService( 2184): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2184): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  913): Resuming delayed broadcast
,W/PackageManager(  913): Unable to load service info ResolveInfo{428805c8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  913): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  913): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  913): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  913): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  913): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  913): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  913): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  913): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  913): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  913): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  913): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  913): start
,I/GCoreNlp( 1230): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/IcingCorporaProvider( 2826): UpdateCorporaTask done [took 560 ms] updated apps [took 560 ms] 
,D/LocationProviderProxy(  913): applying state to connected service
D/PMS     (  913): acquireWL(428ea208): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(428ea208): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  913): applying state to connected service
D/PMS     (  913): acquireWL(428eb830): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(428eb830): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(428ed4e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(428ed4e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2184): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41b99cb0 +
,I/Prism.WidgetManager( 1277): onLoadItems() +
,I/Icing   ( 2184): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  913): releaseWL(42792090): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1277): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1277): onLoadItems() -
,I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41b99cb0 -
,D/PhoneApp( 1250): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1250): -- N1 =0
,D/PhoneApp( 1250): -- N2 =0
,D/PhoneApp( 1250): -- N3 =0
,D/AutoSetting( 1528): service - handleMessage() stop self
,D/AutoSetting( 1528): service - onDestroy() END
,D/AutoSetting( 1528): service - handleMessage() quit looper
,D/Process (  913): killProcessQuiet, pid=3874
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 3874:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 3874
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  913): Client com.google.android.music (pid 3874): Died!
,D/ContactMessageStore( 1250): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1250): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  913): killProcessQuiet, pid=3922
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 3922:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 3922
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  913): acquireWL(42910a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  913): sending alarm PendingIntent{4267fa38: PendingIntentRecord{425ff580 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=121171, Int=0
,D/PMS     (  913): releaseWL(42910a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(42912798): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): acquireWL(42918b20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42918b20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42912798): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4291e698): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
,D/PMS     (  913): releaseWL(4291e698): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(42922c48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/PMS     (  913): acquireWL(4292c0b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(42934138): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1230): Vacuum at: now=1454082634904 tag=VacuumService
,D/PMS     (  913): releaseWL(42922c48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(4292c0b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4293e8f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
D/PMS     (  913): releaseWL(42934138): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/PMS     (  913): releaseWL(4293e8f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(42946598): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
,D/PMS     (  913): releaseWL(42946598): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4294ab48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
,D/PMS     (  913): releaseWL(4294ab48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4294f0f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): releaseWL(4294f0f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4266e450): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): acquireWL(42622098): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42622098): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(42620208): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(4266e450): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(42616e58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
,D/PMS     (  913): releaseWL(42616e58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1230): Scheduling Phenotype for one-off execution 7637 seconds from now (1454082635733)
,D/GetConfigurationSnapshotOperation( 1230): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1230): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1230): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1230): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1230): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1230): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1230): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  913): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
,E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1230): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1230): [NET] getaddrinfo-,err=8
D/libc    ( 1230): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1230): [NET] getaddrinfo-, 1
,D/libc    ( 1230): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4346 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1230): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0],
,D/libc    ( 1230): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1230): [NET] getaddrinfo-,err=8
D/libc    ( 1230): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1230): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  913): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=9 [11][1][0]
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  913): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1230/10029),
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  913): releaseWL(42620208): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(42454c90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
,D/PMS     (  913): releaseWL(42454c90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(42572bf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1117): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1117): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1117): nl80211: survey data missing!
E/wpa_supplicant( 1117): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1117): environment dirty rate=0 [0][0][0]
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
,D/PMS     (  913): releaseWL(42572bf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(426ed148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/PMS     (  913): releaseWL(426ed148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
,D/PowerUI ( 1122): closing low battery warning: level=100
D/UsbnetService(  913): onReceive BATTERY_CHANGED
I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  913): acquireWL(427440d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  913): sending alarm PendingIntent{425475c8: PendingIntentRecord{426c0010 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137578, Int=0
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
,D/PMS     (  913): releaseWL(427440d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1319): service - handleMessage() stop self
,D/AutoSetting( 1319): service - onDestroy() END
,D/AutoSetting( 1319): service - handleMessage() quit looper
,D/Process (  913): killProcessQuiet, pid=4414
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4414:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 4414
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  913): acquireWL(4289efb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42432320: PendingIntentRecord{424322e8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=144798, Int=0
,D/GpsLocationProvider(  913): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  913): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  913): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  913): acquireWL(425e1fe0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 913 1000 null
D/PMS     (  913): releaseWL(4289efb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  913): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  913): [NET] getaddrinfo-,err=8
D/libc    (  913): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  913): [NET] getaddrinfo-, 1
,D/libc    (  913): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =84d5 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE,
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 35,
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10,
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  913): [NET] getaddrinfo_proxy-, success
I/global  (  913): call createSocket() return a new socket.,
D/libc    (  913): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  913): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  913): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  913): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  913):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  913): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  913): acquireWL(41b47128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=146555, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(41b47128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  913): releaseWL(425e1fe0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  913): acquireWL(427e93d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(427e93d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): >> updateStatus
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  913): acquireWL(426931d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10027}
,V/AlarmManager(  913): sending alarm PendingIntent{425ff6f0: PendingIntentRecord{42606900 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174796, Int=0
,D/PMS     (  913): releaseWL(426931d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/PMS     (  913): acquireWL(427ec1f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(427ec1f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1250): switchBindHtcMsgCursor: null
,D/PMS     (  913): acquireWL(428930a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(428930a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  913): acquireWL(4289b4d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=206554, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4289b4d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClearcutLoggerApiImpl( 1372): disconnect managed GoogleApiClient
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  913): acquireWL(428b7100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(428b7100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  913): acquireWL(425a76a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=266554, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(425a76a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  913): acquireWL(426dafd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(426dafd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(426b0f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=326554, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(426b0f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  913): killProcessQuiet, pid=4435
,I/ActivityManager(  913): Killing 4435:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  913): Recipient 4435
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  913): Client connection lost with reason: 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  913): acquireWL(42673160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42673160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1122): closing low battery warning: level=100
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  913): acquireWL(426a4638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(426a4638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  913): acquireWL(4265c2f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=386554, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4265c2f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  913): acquireWL(427f8a30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(427f8a30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  913): acquireWL(426bc548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PMS     (  913): releaseWL(426bc548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(426e2d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=446554, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(426e2d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  913): acquireWL(4281c790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4281c790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  913): acquireWL(42815ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  913): releaseWL(42815ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1122): closing low battery warning: level=100
,D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  913): BroadcastReceiver::onReceive-
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  913): acquireWL(42634200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=506554, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42634200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  913): acquireWL(42707f10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42707f10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  913): acquireWL(42638fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42638fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(4277b8c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=566554, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4277b8c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42770430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42770430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1250): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1250): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1250): sku_id=99
,D/ContactMessageStore( 1250): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1250): start background delete task...
D/ContactMessageStore( 1250): size: 0 , 0
,D/ContactMessageStore( 1250): Background delete complete
,D/PMS     (  913): acquireWL(428aa6d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=626554, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(428aa6d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42887e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42887e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(4261ee20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=686554, Int=0
I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4261ee20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(4282ce70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4282ce70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(42828ee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=746554, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42828ee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42734b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42734b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(42804018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=806554, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42804018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(4283a448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4283a448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(42652900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=866554, Int=0
I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42652900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(428dbdb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(428dbdb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(4264f528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=926554, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4264f528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42820b78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
V/AlarmManager(  913): sending alarm PendingIntent{41c18aa0: PendingIntentRecord{42496640 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=781317, Int=0
,V/AlarmManager(  913): sending alarm PendingIntent{423dbb68: PendingIntentRecord{426a5600 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=949577, Int=0
,I/ActivityManager(  913): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4765 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001},
V/AlarmManager(  913): sending alarm PendingIntent{4266e480: PendingIntentRecord{4272dac8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454082728663, Int=10800000
,V/AlarmManager(  913): sending alarm PendingIntent{4254cd90: PendingIntentRecord{423874f8 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454082729601, Int=1800000
,V/AlarmManager(  913): sending alarm PendingIntent{421978b8: PendingIntentRecord{423b86c8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454083449008, Int=900000
,D/ConnectivityService(  913): Sampling interval elapsed, updating statistics ..
,D/PMS     (  913): acquireWL(42797028): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42797028): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): Done.
,D/ConnectivityService(  913): Setting timer for 720seconds
,D/PMS     (  913): acquireWL(428a50a8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4275ad28): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(428a50a8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4397): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4397): call getInstance()
,D/PMS     (  913): releaseWL(42820b78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PowerUsageList:PowerUsageHelper( 4397): MY_DEBUG = false
I/EventLogService( 2184): Aggregate from 1454082612876 (log), 1454080929435 (data)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.aurora (4765/10049),
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107
,D/PMS     (  913): releaseWL(4275ad28): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,D/Process (  913): killProcessQuiet, pid=4456
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4456:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 4456
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  913): acquireWL(42979ce8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  913): reportInetCondition for net 1, percentage: 100 by  (1372/10029)
D/ConnectivityService(  913): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  913): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1372/10029)
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027335
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027482
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027570
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027575
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027579
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027587
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029302
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029322
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360032732
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033913
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360069107,
,D/PMS     (  913): releaseWL(42979ce8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  913): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  913): acquireWL(4294aa88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4294aa88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(4294a2b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=986554, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4294a2b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42949fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,D/SmartSyncUtils( 4397): isEpsOn(), nState = 0
V/AlarmManager(  913): sending alarm PendingIntent{426ca438: PendingIntentRecord{42645f58 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454083520939, Int=0
,D/SmartSyncScreenOnOffTimeReceiver( 4397): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4397): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/PMS     (  913): acquireWL(42949cb8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4397 1000 null
,D/PMS     (  913): releaseWL(42949fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4397): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4397): SettingOnTime = 1454133600000, randomSettingOnTime = 1454130826000
D/SmartSyncScreenOnOffTimeReceiver( 4397): SettingOffTime = 1454119200000, randomSettingOffTime = 1454122062000
D/SmartSyncScreenOnOffTimeReceiver( 4397): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4397): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4397): bNightModeTurnOffOnce = false
D/PMS     (  913): releaseWL(42949cb8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  913): acquireWL(42949840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42949840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(42949540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1046554, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42949540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(429484e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(429484e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(42946910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1106554, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42946910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(4291f430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4291f430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(428e54b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1166555, Int=0
I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(428e54b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(428a0a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(428a0a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  913): acquireWL(42888d00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b813d8: PendingIntentRecord{41be08d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1226554, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42888d00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4783): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4783): ====startRecUseTime====
D/htc.customization.log.level( 4783):  is 
W/CustomizationLogLevel( 4783): Level value is invalid, use default level 2
D/CustomizationManager( 4783):  Read ACC file spent 0.106 (s)
D/CIDMapFileReader( 4783): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4783): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4783): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4783): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4783): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4783): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4783): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4783): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4783): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4783): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4783): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4783): Parsing tag category name = system
I/CustomizationCIDLoader( 4783): Parsing tag category name = application
I/CustomizationCIDLoader( 4783): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4783): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4783): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4783): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4783): Parsing tag category name = Settings
D/CustomizationManager( 4783):  Read CID file spent 0.157 (s)
D/CustomizationManager( 4783):  All configurations done spent 0.158 (s)
W/HtcNativeFlag( 4783): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4783): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4783): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4783): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  913): deletePackageAsUser: pkg=com.test.thalitest, pid=4783, uid=2000 user=0
I/ActivityManager(  913): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  913): Skipping PackageSetting{41fd2c98 com.example.hello/10397} due to missing metadata
W/PackageSettings(  913): Skipping PackageSetting{41becdc8 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  913): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/DotMatrix( 1565): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1565): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver replacing:false
W/PackageManager(  913): Package source /data/app/com.test.thalitest-1.apk does not exist.
W/PackageManager(  913): Couldn't delete native library directory /data/app-lib/com.test.thalitest-1
D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1230): Ignoring removeGeofence because network location is disabled.
D/PMS     (  913): acquireWL(429a45f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1305): Cleaning up data for package: com.test.thalitest
D/PMS     (  913): releaseWL(429a45f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/SystemReader( 1262): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "sms"
I/[PluginManager]RegisterService( 1319): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1319): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1277): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "smsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mms"
I/InputMethodManagerService(  913): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mmsto"
I/IcingCorporaProvider( 2826): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "sms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
I/ActivityManager(  913): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4798 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/ExternalAccountType( 1343): Unsupported attribute readOnly
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "smsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
I/IcingCorporaProvider( 2826): UpdateCorporaTask done [took 84 ms] updated apps [took 84 ms] 
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mmsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
D/PhoneApp( 1250): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
W/PackageManager(  913): Unable to load service info ResolveInfo{426728f0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  913): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  913): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  913): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  913): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  913): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  913): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  913): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  913): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  913): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  913): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4798): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4798): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4798): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4798): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4798): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4798): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4798): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4798): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4798): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4798): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4798): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4798): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4798): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4798): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4798): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4798): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4798): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4798): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4798): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4798): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4798): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4798): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4798): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4798): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4798): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4798): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4798): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4798): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4798): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4798): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4798): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4798): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4798): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4798): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4798): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4798): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4798): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4798): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4798): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4798): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4798): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4798): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4798): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4798): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4798): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4798): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4798): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4798): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4798): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4798): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4798): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4798): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4798): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4798): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4798): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4798): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4798): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4798): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4798): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4798): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4798): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4798): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4798): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4798): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4798): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4798): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4798): threadid=11: thread exiting with uncaught exception (group=0x416d4e30)
E/ActivityManager(  913): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4798): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4798): Process: com.google.android.apps.docs, PID: 4798
E/AndroidRuntime( 4798): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4798): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4798): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4798): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4798): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4798): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4798): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4798): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4798): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4798): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4798): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4798): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4798): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4798): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4798): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  913): Can't write: system_app_crash
E/DropBoxManagerService(  913): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  913): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  913): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  913): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  913): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  913): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  913): 	... 5 more
D/RemoteDisplayProvider(  913): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
E/SQLiteDatabase( 4798): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4798): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4798): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4798): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4798): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4798): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4798): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4798): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4798): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4798): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4798): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4798): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4798): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4798): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4798): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4798): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4798): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4798): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4798): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4798): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4798): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4798): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4798): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4798): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4798): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4798): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4798): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4798): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4798): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4798): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4798): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4798): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4798): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4798): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4798): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4798): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4798): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4798): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4798): Opened ClientFlag.db in read-only mode
D/RemoteDisplayProvider(  913): start
D/Process ( 4798): killProcess, pid=4798
D/Process ( 4798): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
W/AtomicFile(  913): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
I/ActivityManager(  913): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4816 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/AppWidgetServiceImpl(  913): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager(  913): Recipient 4798
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Process com.google.android.apps.docs (pid 4798) has died.
D/PMS     (  913): acquireWL(427608d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
D/PMS     (  913): releaseWL(427608d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
W/ContextImpl( 4816): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4816): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4816): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4816): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4816): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4816): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4816): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4816): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4816): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4816): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4816): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4816): threadid=10: thread exiting with uncaught exception (group=0x416d4e30)
I/ActivityManager(  913): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4830 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  913): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4816): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4816): Process: com.android.keychain, PID: 4816
E/AndroidRuntime( 4816): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4816): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4816): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4816): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4816): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4816): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4816): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4816): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4816): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  913): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4816): killProcess, pid=4816
D/Process ( 4816): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  913): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  913): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454083785362.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  913): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  913): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  913): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  913): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  913): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  913): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  913): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  913): 	... 4 more
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Recipient 4816
I/ActivityManager(  913): Process com.android.keychain (pid 4816) has died.
W/ActivityManager(  913): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4830): getInstance(Context context)
D/AppTag  ( 4830): getInstance(Context context)
D/AppTag  ( 4830): onCreate()
D/PMS     (  913): acquireWL(427be658): PARTIAL_WAKE_LOCK  AsyncService 0x1 4143 10160 null
D/PMS     (  913): releaseWL(427be658): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4563): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2184): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2184): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2184): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 2184): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 2184): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
E/SQLiteDatabase( 2184): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2184): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2184): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2184): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2184): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2184): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2184): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2184): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2184): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2184): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2184): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 2184): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 2184): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 2184): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
W/dalvikvm( 2184): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
I/GMPM-SVC( 2184): App measurement is starting up, version: 8489
I/GMPM-SVC( 2184): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/SQLiteLog( 2184): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2184): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5cae1460
E/DriveAsyncService( 2184): disk I/O error (code 3850)
E/DriveAsyncService( 2184): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2184): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2184): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2184): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  913): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteDatabase( 2184): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 2184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2307)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 2184): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 2184): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/GMPM-SVC( 2184): Opening the database failed, dropping and recreating it
E/SQLiteDatabase( 2184): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2184): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2184): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2184): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2184): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 2184): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2184): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/pluscontacts.db, handle = 0x65b620c0
E/SQLiteOpenHelper( 2184): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2184): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2184): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2184): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2184): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2184): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2184): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2184): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2184): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 2184): threadid=50: thread exiting with uncaught exception (group=0x416d4e30)
W/SQLiteOpenHelper( 2184): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 2184): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 2184): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 2184): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 2184): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 2184): threadid=48: thread exiting with uncaught exception (group=0x416d4e30)
E/SQLiteDatabase( 2184): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 2184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 2184): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 2184): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/GMPM-SVC( 2184): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
D/PMS     (  913): acquireWL(4275f748): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
E/AndroidRuntime( 2184): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 2184): Process: com.google.android.gms, PID: 2184
E/AndroidRuntime( 2184): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2184): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 2184): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 2184): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 2184): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 2184): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2184): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2184): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2184): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Icing   ( 2184): doRemovePackageData com.test.thalitest
W/GMPM-SVC( 2184): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/GMPM-SVC( 2184): Task exception on worker thread: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2184): Module APK com.google.android.play.games already loaded
E/ActivityManager(  913): App crashed! Process: com.google.android.gms
W/GMPM-SVC( 2184): Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
E/GMPM-SVC( 2184): Error querying app: com.test.thalitest, android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
D/Process ( 2184): killProcess, pid=2184
D/Process ( 2184): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/AndroidRuntime_2_crash( 2184): crash in the same process: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime_2_crash( 2184): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime_2_crash( 2184): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime_2_crash( 2184): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime_2_crash( 2184): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime_2_crash( 2184): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime_2_crash( 2184): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime_2_crash( 2184): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime_2_crash( 2184): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime_2_crash( 2184): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime_2_crash( 2184): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime_2_crash( 2184): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime_2_crash( 2184): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  913): releaseWL(4275f748): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
E/DropBoxManagerService(  913): Can't write: system_app_crash
E/DropBoxManagerService(  913): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  913): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  913): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  913): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  913): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  913): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  913): 	... 5 more
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41b99cb0 +
I/Prism.WidgetManager( 1277): onLoadItems() +
I/ActivityManager(  913): Recipient 2184
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Process com.google.android.gms (pid 2184) has died.
D/WifiService(  913): Client connection lost with reason: 4
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.AppsMonitorIntentService in 1000ms
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 11000ms
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10999ms
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 10998ms
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20998ms
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 20997ms
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 30997ms

```
