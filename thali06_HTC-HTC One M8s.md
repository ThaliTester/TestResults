#### Test 50388019c82294c_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/ContactMessageStore( 1475): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1475): MSG_NOTIFY_CS_TO_SYNC <<
D/MdScSimSt( 4714): [61c.1.2.] qry 118: 0+1 running 0
--------- beginning of system
I/ActivityManager(  956): Recipient 4120
I/ActivityManager(  956): Killing 4144:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  956): killProcessQuiet, pid=4144
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
I/art     (  956): Explicit concurrent mark sweep GC freed 9811(473KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.415ms total 167.005ms
D/PMS     (  956): acquireWL(2d848866): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1864 10024 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  956): Recipient 4144
D/MtpReceiver( 3634): [MTP][handleUsbStateAsync]+
I/ActivityManager(  956): Killing 4167:com.android.smith/1000 (adj 15): empty #17
D/MtpReceiver( 3634): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3634): [MTP][handleUsbState]+
D/Process (  956): killProcessQuiet, pid=4167
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  956): Recipient 4167
I/ActivityManager(  956): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4793 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
D/MtpReceiver( 3634): [MTP][scanExternalVolumeIfNeed] scan external volume
D/PMS     (  956): releaseWL(2d848866): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/MtpReceiver( 3634): [MTP][handleUsbState]-
D/MtpService( 3634): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpReceiver( 3634): [MTP][handleMessage]-
D/MtpDatabase( 3634): TotalSize=1886532,MediaCacheLimit=6000
D/MtpService( 3634): [isMtpConnected] connected: true
D/SyncApplication( 4793): Loading default preferences
E/MediaScannerService( 3634): [onStartCommand] --- Should not be here, redirect request. ----
E/MediaScannerService( 3634): [handleMessage] --- Should not be here, ignore request. ----
W/Resources( 4793): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
E/WifiTrafficPoller(  956): ADD_CLIENT: 7
D/WifiService(  956): New client listening to asynchronous messages
D/SyncApplication( 4793): Overriding preferences with custom values
E/MediaScannerServiceEx( 3634): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3634): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 3634): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3634): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3634): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3634): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3634): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3634): [AliveExtStorageRows]+65537, 11223344
D/MediaProvider( 3634): [update][6]#0#
D/MediaProvider( 3634): [update][1]#0#
D/SyncApplication( 4793): Updating preferences succeeded
D/MediaProvider( 3634): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3634): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 3634): [update][5]#1#
D/MediaScannerServiceEx( 3634): [AliveExtStorageRows]-0, 0
E/SyncApplication( 4793): Application created.
D/PMS     (  956): acquireWL(c04e9ec): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3634 10017 null
D/MediaScanner( 3634): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
W/VolumeInfo( 4793): Unable to read mount points
W/VolumeInfo( 4793): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4793): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 4793): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 4793): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 4793): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 4793): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 4793): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 4793): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 4793): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 4793): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 4793): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 4793): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 4793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 4793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 4793): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 4793): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4793): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 4793): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 4793): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 4793): 	... 13 more
V/VolumeInfo( 4793): Found 0 mount point(s)
V/VolumeInfo( 4793): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
I/CalendarDefines( 4793): getNewCalendarAuthority()...
I/PackageManager(  956):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4793, uid=10005, userID:0
W/PackageManager(  956): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  956):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4793, uid=10005, userID:0
W/PackageManager(  956): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 4793): enableAppOperation()+
D/VolumeInfo( 4793): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/SyncApplication( 4793): enableAppOperation()-
D/HTCUtilities( 4793): isNeorSinged() + 
D/VolumeInfo( 4793): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
W/VolumeInfo( 4793): Can not create volume ID for unmounted volume null
D/HTCUtilities( 4793): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 4793): isNeorSinged() return false
D/CDMountReceiver( 4793): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 4793): USB connected to PC
D/FOTAReceiver( 4793): onReceive() enter 
D/FOTAReceiver( 4793): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/TetherSettings( 4098): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4098): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4098): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4098): Cust_ConnectToPC   : spcsc>false
D/        ( 4098): Cust_ConnectToPC   : IPT>true
D/        ( 4098): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4098): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4098): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4098): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4098): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 4098): usb_cable_connect = 1
D/SmartNS_Utility( 4098): usb_denied = 0
I/SmartNS_NSReceiver( 4098): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 4098): USB = true hasTethered = false isNSOpening: false
I/PSReceiver( 4098): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/ContextImpl( 4098): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 
I/SmartNS_PSService( 4098): onReceive:com.htc.intent.action.USB_CONNECT2PC
D/PMS     (  956): acquireWL(15f0004a): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1864 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1864): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1864): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1864): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1864): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1864): [NET] android_getaddrinfo_proxy+
D/libc    ( 1864): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1864): [NET] android_getaddrinfo_proxy-, NODATA
W/Settings( 4098): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4098):  defaultType:0
I/SmartNS_PSService( 4098): fail notificaiton:false
D/SmartNS_Utility( 4098): usb_cable_connect = 1
D/SmartNS_Utility( 4098): usb_denied = 0
I/SmartNS_PSService( 4098): usb notificaiton:true
E/WifiStateMachine(  956): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  956): releaseWL(15f0004a): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  956): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4826 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 4
D/SmartNS_Utility( 4098): usb_cable_connect = 1
D/SmartNS_Utility( 4098): usb_denied = 0
I/SmartNS_PSService( 4098): usb notificaiton:true
E/WifiStateMachine(  956): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1218): reapply : com.android.settings 2 36
,D/SmartNS_Utility( 4098): usb_cable_connect = 1
D/SmartNS_Utility( 4098): usb_denied = 0
D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/SmartNS_PSService( 4098): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 4098): USB Plugged, Set USBPlugged=  truePSenabled:false
D/Process (  956): killProcessQuiet, pid=4225
I/ActivityManager(  956): Killing 4225:com.google.android.gms:car/u0a24 (adj 15): empty #17
I/RemoteViews( 1218): reapply : com.android.settings 1 36
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  956): Recipient 4225
W/ContextImpl( 4826): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
I/ActivityManager(  956): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4850 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
D/Process (  956): killProcessQuiet, pid=4188
I/ActivityManager(  956): Killing 4188:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/cutils-trace( 4847): Error opening trace file: Permission denied (13)
D/CustomizationManager( 4847): ====startRecUseTime====
D/htc.customization.log.level( 4847):  is 
W/CustomizationLogLevel( 4847): Level value is invalid, use default level 2
I/ActivityManager(  956): Recipient 4188
D/CustomizationManager( 4847):  Read ACC file spent 0.038 (s)
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4847): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 4847): Parsing tag category name = system
I/CustomizationCIDLoader( 4847): Parsing tag category name = application
I/CustomizationCIDLoader( 4847): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4847): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4847): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4847): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4847): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4847): add string-array item, value = 42507
I/CustomizationCIDLoader( 4847): add string-array item, value = 21902
I/CustomizationCIDLoader( 4847): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4847): add string-array item, value = 23420
I/CustomizationCIDLoader( 4847): add string-array item, value = 22299
I/CustomizationCIDLoader( 4847): add string-array item, value = 24002
I/CustomizationCIDLoader( 4847): add string-array item, value = 23210
I/CustomizationCIDLoader( 4847): add string-array item, value = 23205
I/CustomizationCIDLoader( 4847): add string-array item, value = 23806
I/CustomizationCIDLoader( 4847): add string-array item, value = 23430
I/CustomizationCIDLoader( 4847): add string-array item, value = 23408
I/CustomizationCIDLoader( 4847): add string-array item, value = 27205
I/CustomizationCIDLoader( 4847): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4847):  Read CID file spent 0.081 (s)
D/CustomizationManager( 4847):  All configurations done spent 0.081 (s)
I/ActivityManager(  956): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4847 on display 0
D/PMS     (  956): acquireHCC(364cb8d8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 956 1000 null
D/PMS     (  956): acquireHCC(e0cb431): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 956 1000 null
W/asset   (  956): Copying FileAsset 0x55a39b2240 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  956): acquireWL(26408a84): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 956 1000 null
I/FeedHostManager( 1526): [onPause]
I/FeedProviderManager( 1526): onPause
I/FeedHostManager( 1526): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@38e2c4ff
I/SocialFeedProvider( 1526): +onPause
I/SocialFeedProvider( 1526): -onPause
W/ResourcesManager( 4850): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/AnimationUtil(  956): isHTCRecent(HelloWorld/Recent screens.)/5
W/HtcSystemUPManager(  956): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  956): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4887 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/art     (  456): Explicit concurrent mark sweep GC freed 8672(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 236us total 17.550ms
I/art     (  456): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 230us total 14.873ms
V/AlarmManager(  956): sending alarm PendingIntent{1b04b869: PendingIntentRecord{3b68b2ee android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=60395, Int=0
I/ClockController( 1218): schedule update now=1447782180025 next=59975
I/art     (  456): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 425us total 18.099ms
I/Clock   ( 1218): updateClock:18:43 Europe/Warsaw
I/Clock   ( 1218): updateClock:18:43 Europe/Warsaw
I/Clock   ( 1218): updateClock:18:43 Europe/Warsaw
W/asset   ( 4887): Copying FileAsset 0xac610ad0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/StatusBarManagerService(  956): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  956): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  956): hiding MENU key
I/TrimMemoryManager( 1526): [trimMemory] 20
D/WeatherUtility( 1218): Weather sync is On
W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
I/CalendarProvider2( 4850): Created com.android.providers.calendar.CalendarAlarmManager@1e81a808(com.htc.providers.calendar.HtcCalendarProvider@3c972ba1)
D/CalendarProvider2( 4850): wait start:true
I/WebViewFactory( 4887): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/FlexNetS( 4850): updateSvcAllowedInSettings:false
D/CalendarProvider2( 4850): wait end:false
I/ActivityManager(  956): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4912 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/LibraryLoader( 4887): Time to load native libraries: 11 ms (timestamps 599-610)
I/LibraryLoader( 4887): Expected native library version number "",actual native library version number ""
I/ActivityManager(  956): Waited long enough for: ServiceRecord{3eddd5f4 u0 com.htc.HTCSpeaker/.NGFService}
V/WebViewChromiumFactoryProvider( 4887): Binding Chromium to main looper Looper (main, tid 1) {1e81a808}
I/LibraryLoader( 4887): Expected native library version number "",actual native library version number ""
I/chromium( 4887): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/ContextImpl( 4912): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
I/BrowserStartupController( 4887): Initializing chromium process, singleProcess=true
W/art     ( 4887): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager(  956): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4938 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
D/PowerUsageList:PowerUsageHelper( 4912): MY_DEBUG = false
E/SysUtils( 4887): ApplicationContext is null in ApplicationStatus
D/PowerUsageService( 4912): repeat time = 1447783080439
D/WeatherUtility( 1441): Weather sync is On
D/WSP     ( 1441): [Receiver] auto sync agent, auto sync is enabled, reset schedule
W/chromium( 4887): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
D/PMS     (  956): acquireWL(34522e95): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 4850 10011 null
W/chromium( 4887): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/PMS     (  956): acquireWL(1de0d39b): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4912 1000 null
E/SQLiteLog( 4850): (284) automatic index on view_events(_id)
D/WeatherUtility( 4938): Weather sync is On
E/libEGL  ( 4887): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4887): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4887): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4887): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4887): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4887): Local Branch: 
I/Adreno-EGL( 4887): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4887): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4887):                  d74aa161a12b9c6fc6332151
I/ActivityManager(  956): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
I/ActivityManager(  956): Resuming delayed broadcast
I/ActivityManager(  956): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
W/WeatherRequest( 4938): request cur loc, but there is no sys cur
W/Settings( 4938): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/PMS     (  956): releaseWL(1de0d39b): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/ActivityManager(  956): Resuming delayed broadcast
I/ActionCombine( 4938): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
I/RemoteViews( 1526): reapply : com.htc.widget.weatherclock 7 17
W/System.err(  956): java.lang.Throwable: stack dump
D/BluetoothManagerService(  956): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  956): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  956): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  956): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  956): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  956): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13c1b13:true
D/BluetoothAdapter( 4887): 1006491015: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  956): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=4982 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
I/PowerUsageList:PowerUsageHelper( 4912): PowerProfile::POWER_SCREEN_FULL = 154.8
D/PMS     (  956): releaseWL(34522e95): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
D/Prism.PackageStateRece_( 1526): action: android.intent.action.PACKAGE_ADDED
I/[PluginManager]RegisterService( 1441): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
I/[PluginManager]RegisterService( 1441): handle notify Blinkfeed plugin client changed
D/PowerUsageList:BatterySipperExt( 4912): gen(), null == sipper.uidObj, userId = 0
D/PowerUsageList:BatterySipperExt( 4912): gen(), null == sipper.uidObj, userId = 0
D/PowerUsageList:BatterySipperExt( 4912): gen(), null == sipper.uidObj, userId = 0
I/ActivityManager(  956): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5009 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
D/PowerUsageService( 4912): calcPower(), no data
D/Process (  956): killProcessQuiet, pid=3367
I/ActivityManager(  956): Killing 3367:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/art     ( 4887): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager(  956): Recipient 3367
W/AwContents( 4887): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 4887): CordovaWebView is running on device made by: HTC
W/art     ( 4887): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4887): Attempt to remove local handle scope entry from IRT, ignoring
I/DeviceManagement( 5009): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=5009 dbg=false s=true
I/DeviceManagement( 5009): PackageUpdateReceiver: vvv Package added: [com.example.hello]
I/HtcModeClient( 3135): handler message = 4011
E/HtcModeClient( 3135): Check connection and retry 4 times.
D/Process (  956): killProcessQuiet, pid=4384
I/ActivityManager(  956): Killing 4384:com.google.android.youtube/u0a176 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
I/ActivityManager(  956): Recipient 4384
I/ActivityManager(  956): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5038 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
I/EASAppSvc( 4982): [ NA ]onCreate
I/VersionUtil( 4982): [ NA ]setIsFOTAing: true
I/VersionUtil( 4982): [ NA ]onUpgrade: current version=100, latest version=100
I/VersionUtil( 4982): [ NA ]setIsFOTAing: false
W/chromium( 4887): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/HtcAdjCursorFactory( 4982): Set CursorWindow size to: 4194304 KB, Tid: 5056
D/ORMLib  ( 4736): put()
D/HtcCupdReceiver(Provider)( 5038):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
D/FindExtension( 4887): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ActivityManager(  956): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5067 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  956): killProcessQuiet, pid=4462
I/ActivityManager(  956): Killing 4462:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/art     (  455): Explicit concurrent mark sweep GC freed 8663(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 158us total 20.332ms
I/art     (  455): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 163us total 17.880ms
I/art     (  455): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 136us total 16.306ms
I/CalendarProvider2( 4850): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 4850): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/Settings:HtcWirelessFeatureFlags( 4098): id/is att sku: 118/false
I/InputMethodManager( 4887): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@21b46602, mServedView=org.apache.cordova.engine.SystemWebView{38703b13 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3d7b2150
I/InputMethodManagerService(  956): Disable input method client, pid=1526
D/StatusBarManagerService(  956): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  956): Enable input method client, pid=4887
I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
W/BindingManager( 4887): Cannot call determinedVisibility() - never saw a connection for the pid: 4887
I/chromium( 4887): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
W/XT9_C   ( 1361): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1361): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1361): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1361): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/ActivityManager(  956): Recipient 4462
E/Settings:HtcWrapHeaderInfo( 4098): no such activity!
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4098): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 4098): updateDevelopment, bPrefShow = true
,D/PMS     (  956): releaseWL(26408a84): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4887): Set native->JS mode to OnlineEventsBridgeMode,
,E/Settings:HtcUmcWidgetEnabler( 4098): isSupportMusicChannel(): false
I/ActivityManager(  956): Displayed com.example.hello/.MainActivity: +1s325ms
,D/Process (  956): killProcessQuiet, pid=4501
I/ActivityManager(  956): Killing 4501:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/WifiService(  956): New client listening to asynchronous messages
E/WifiTrafficPoller(  956): ADD_CLIENT: 8
,W/EAS_NetworkUtil( 4982): [ NA ]getNetworkInfo: NetworkInfo is null
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4098): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4098): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4098): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4098): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4098): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4098): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4098): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4098): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4098): [supportHomeButton]support         :false
,E/AndroidProtocolHandler( 4887): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/MediaProvider( 3634): [update][5]#1#
,D/MediaScanner( 3634):  prescan time: 833ms
D/MediaScanner( 3634):     scan time: 1179ms
D/MediaScanner( 3634): postscan time: 3ms
D/MediaScanner( 3634):    total time: 2015ms
D/MediaScanner( 3634): -----------------------------------------------------------------
D/MediaScanner( 3634): firstscan(media) time: 620ms
D/MediaScanner( 3634): secondscan(non-media) time: 559ms
D/MediaScanner( 3634):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
D/MediaScanner( 3634):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3634):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3634):  [Total]    File(Image+Video+Audio+Others) in database : 1546
,I/ActivityManager(  956): Recipient 4501
,D/WifiService(  956): Client connection lost with reason: 4
,D/MediaProvider( 3634): [delete][20]
D/MediaProvider( 3634): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3634): [recoverParentNodes] - 0
D/MediaProvider( 3634): [update][4]
,D/MediaScannerServiceEx( 3634): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3634): [updateImage]+
,D/MediaScannerServiceEx( 3634): [updateImage]-0
,D/Process (  956): killProcessQuiet, pid=4627,
I/ActivityManager(  956): Killing 4627:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  956): Recipient 4627
,V/AlarmManager(  956): sending alarm PendingIntent{3563cedc: PendingIntentRecord{237446ba com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1447782181470, Int=0
,D/PMS     (  956): releaseWL(c04e9ec): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaScannerServiceEx( 3634): [1] scan finished
D/MediaProviderUtils( 3634): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3634): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3634): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3634): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3634): Process mounted intent for unmounted storage: /storage/ext_sd
I/EASAppSvc( 4982): [ NA ]onDestroy
I/EASAppSvc( 4982): [ NA ]> uninitEASService
D/MediaScannerServiceEx( 3634): [disAliveExtStorageRows]+131073
I/EASAppSvc( 4982): [ NA ]onCreate
I/EASRequestController( 4982): [ NA ]release
I/ActivityManager(  956): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4098): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 4098): isSupportVoWifi: null
D/MediaProvider( 3634): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4098): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 4098): updateDevelopment, bPrefShow = true
D/MediaProvider( 3634): [update][8]#1#
D/jxcore_app_log( 4887): JniHelper::setJavaVM(0xab4a28f8), pthread_self() = -1401148176
D/JX-Cordova( 4887): jxcore cordova android initializing
E/Settings:HtcUmcWidgetEnabler( 4098): isSupportMusicChannel(): false
D/EASPublicBinder( 4982): [ NA ]release
D/TaskBinder( 4982): [ NA ]release
D/TaskBinder( 4982): [ NA ]release
I/EASAppSvc( 4982): [ NA ]< uninitEASService
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4098): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4098): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4098): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4098): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4098): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4098): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4098): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4098): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4098): [supportHomeButton]support         :false
,I/VersionUtil( 4982): [ NA ]setIsFOTAing: true
D/MediaProvider( 3634): [update][16]#0#
I/VersionUtil( 4982): [ NA ]onUpgrade: current version=100, latest version=100
I/VersionUtil( 4982): [ NA ]setIsFOTAing: false
,W/jxcore-log( 4887): Initializing JXcore engine
,W/jxcore-log( 4887): JXcore engine is ready
,W/jxcore-log( 4887): Starting JXcore engine
,I/art     (  956): Explicit concurrent mark sweep GC freed 12864(657KB) AllocSpace objects, 2(536KB) LOS objects, 33% free, 16MB/24MB, paused 1.357ms total 132.724ms
,I/ActivityManager(  956): Killing 4658:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  956): killProcessQuiet, pid=4658
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/MediaScannerServiceEx( 3634): [disAliveExtStorageRows]--1, 0
,D/ORMLib  ( 4736): put()
,W/jxcore-log( 4887): Platform android
W/jxcore-log( 4887): 
W/jxcore-log( 4887): Process ARCH arm
W/jxcore-log( 4887): 
,I/ActivityManager(  956): Recipient 4658
,I/jxcore-log( 4887): JXcore Cordova bridge is ready!,
I/jxcore-log( 4887): 
W/jxcore-log( 4887): JXcore engine is started
,I/ActivityManager(  956): Cannot resolve ContentProvider=com.htc.vowifi,
,E/Settings:HtcVoWifiWidgetEnabler( 4098): isSupportVoWifi: null
E/ActivityThread( 4098): Failed to find provider info for com.htc.vowifi
,W/EAS_NetworkUtil( 4982): [ NA ]getNetworkInfo: NetworkInfo is null
,D/MediaProviderUtils( 3634): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3634): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3634): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3634): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3634): Process mounted intent for unmounted storage: /storage/usb
,D/MediaScannerServiceEx( 3634): [disAliveExtStorageRows]+196609
,I/PackageManager(  956):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5067, uid=10072, userID:0
,I/EASAppSvc( 4982): [ NA ]onDestroy
,I/EASAppSvc( 4982): [ NA ]> uninitEASService
,D/MediaProvider( 3634): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 3634): [update][8]#1#
,W/global  ( 5067): [apache-http] Connection GC has been deprecated!
,I/ActivityManager(  956): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5114 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
,I/EASRequestController( 4982): [ NA ]release
,D/EASPublicBinder( 4982): [ NA ]release
D/TaskBinder( 4982): [ NA ]release
,D/TaskBinder( 4982): [ NA ]release
I/EASAppSvc( 4982): [ NA ]< uninitEASService
,D/MediaProvider( 3634): [update][25]#0#
,D/MediaScannerServiceEx( 3634): [disAliveExtStorageRows]--1, 0,
,D/Finsky  ( 5067): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/PMS     (  956): releaseHCC(364cb8d8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  956): releaseHCC(e0cb431): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/global  ( 5067): [apache-http] Connection GC has been deprecated!
,E/jxcore-log( 4887): >> HTC-HTC One M8s
E/jxcore-log( 4887): 
,I/jxcore-log( 4887): Total memory 1931808768,
I/jxcore-log( 4887): 
I/jxcore-log( 4887): Free memory 83697664
I/jxcore-log( 4887): 
I/jxcore-log( 4887): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4887): 
I/jxcore-log( 4887): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4887): 
,I/jxcore-log( 4887): userPath [ 'www' ],
I/jxcore-log( 4887): 
I/jxcore-log( 4887): Size 1080 1776
I/jxcore-log( 4887): 
,I/jxcore-log( 4887): Screen Brightness 142,
I/jxcore-log( 4887): 
E/jxcore-log( 4887): Dummy Error Log.
E/jxcore-log( 4887): 
,D/Process (  956): killProcessQuiet, pid=4680
I/ActivityManager(  956): Killing 4680:com.htc.sense.news/u0a74 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/global  ( 5067): [apache-http] Connection GC has been deprecated!,
,D/ORMLib  ( 4736): put(),
,D/Finsky  ( 5067): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  956): Recipient 4680
,I/ActivityManager(  956): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5156 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/Settings( 5067): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5067): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,I/PackageManager(  956):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5067, uid=10072, userID:0
,W/ResourcesManager( 5156): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5156): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5156): VM with version 2.1.0 has multidex support
I/MultiDex( 5156): install
,I/MultiDex( 5156): VM has multidex support, MultiDex support library is disabled.
,D/Process (  956): killProcessQuiet, pid=4714,
I/ActivityManager(  956): Killing 4714:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17,
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  956): Recipient 4714
,I/jxcore-log( 4887): getBuffer is called!!!!,
I/jxcore-log( 4887): 
,D/Finsky  ( 5067): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5067): [1] 2.run: Finished loading 1 libraries.
,V/JNIHelp ( 5156): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
D/Finsky  ( 5067): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ChimeraCfgMgr( 4251): Loading module com.google.android.gms.games from APK com.google.android.play.games,
D/ChimeraModuleLdr( 4251): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 4251): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello,
,D/Finsky  ( 5067): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
,D/PMS     (  956): acquireWL(323044c2): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4251 10024 null,
,W/ActivityThread( 5156): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 5156): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22670d62: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5156): Installed default security provider GmsCore_OpenSSL
,I/art     ( 1864): Explicit concurrent mark sweep GC freed 10246(550KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 621us total 33.801ms,
,I/ConfigFetchService( 4251): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) },
,D/PMS     (  956): acquireWL(1213a0c5): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4251 10024 WorkSource{10373 com.example.hello},
I/ConfigFetchService( 4251): launchTask
D/PMS     (  956): releaseWL(323044c2): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,D/PMS     (  956): acquireWL(ab5aa1a): PARTIAL_WAKE_LOCK  Icing 0x1 4251 10024 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4251): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4251): Module APK com.google.android.play.games already loaded,
D/ChimeraCfgMgr( 4251): Loading module com.google.android.gms.vision from APK com.google.android.gms
,V/ConfigFetchTask( 4251): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1V_cRsRRtbISVoJFk39udPvq_h5obk9ufKqbjLNnFXfgcNAJH5Rkca-yhsdDn7oySuyhRcP-MnDVwV42hG2IbmYO6gNhpx_iCdaAzIlK32xD6h4YROkk-wtMO2tQ-mjWcCAUqx1gypqGOTK5RLzzjZC_gAu2ctfO7Oj6zGRX2f4mypx0tojhKViJaGuMRIDoGlvLXoF
,D/Vision  ( 4251): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,I/PeopleContactsSync( 4251): CP2 sync disabled
,D/Vision  ( 4251): Failed to find package metadata for com.example.hello
D/Vision  ( 4251): No vision deps
,I/PackageManager(  956):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4251, uid=10024, userID:0,
I/GoogleURLConnFactory( 4251): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  956): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5195 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a,
,I/SocialFeedProvider( 1526): +disConnect socialManager
,I/SocialFeedProvider( 1526): disconnect socialManager
,I/SocialFeedProvider( 1526): -disConnect socialManager
,D/Process (  956): killProcessQuiet, pid=3745
,I/ActivityManager(  956): Killing 3745:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/libc    ( 4251): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4251): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4251): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4251): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4251): [NET] android_getaddrinfo_proxy+
D/libc    ( 4251): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4251): [NET] android_getaddrinfo_proxy-, NODATA
,W/ConfigFetchTask( 4251): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname,
,I/ConfigFetchService( 4251): fetch service done; releasing wakelock
,D/PMS     (  956): releaseWL(1213a0c5): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10373 com.example.hello}
I/ConfigFetchService( 4251): stopping self
,I/ActivityManager(  956): Recipient 3745
,I/Icing   ( 4251): Storage manager: low false usage 1.98MB avail 5.80GB capacity 7.95GB
,I/ActivityManager(  956): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5222 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
V/AlarmManager(  956): sending alarm PendingIntent{fc2237d: PendingIntentRecord{c276272 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1447782182899, Int=0,
,V/AlarmManager(  956): sending alarm PendingIntent{31600b40: PendingIntentRecord{3cd27a79 com.android.vending startService}}, i=null, t=0, cnt=1, w=1447782183072, Int=0
,D/Finsky  ( 5067): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/Icing   ( 4251): Received bad json for section weights override -- ignoring.
,V/Finsky  ( 5067): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/GLSActivity( 1864): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 4251): Using Auth Proxy for data requests.
,W/BaseAppContext( 4251): Using Auth Proxy for data requests.
,W/Icing   ( 4251): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 4251): Received bad json for section weights override -- ignoring.
W/Icing   ( 4251): Received bad json for corpus context scoring override -- ignoring.
,I/GLSUser ( 1864): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1864): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1864): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1864): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1864): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 4251): Using Auth Proxy for data requests.
,I/ImageRamCache( 5222): create image Cache, size: 31457280.
,I/ImageRamCache( 5222): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 5222): create image Cache, size: 31457280.
,I/FeedSettings( 5222): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 5222): GroupBudget 0.500000 0.380000
I/FeedSettings( 5222): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 5222): changeLocale(): en_GB
V/GLSActivity( 1864): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 4251): Using Auth Proxy for data requests.
,I/Prism.AllAppsOptionsMa_( 5222): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 5222): loadGridSize() with Alternative,
,W/BaseAppContext( 4251): Using Auth Proxy for data requests.
,I/GLSUser ( 1864): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1864): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1864): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1864): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1864): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
W/BaseAppContext( 4251): Using Auth Proxy for data requests.
,W/Finsky  ( 5067): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/SocialManager[SocialBiLogHelper]( 5222): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 5222): last commit ulog time 1447739411733
I/SocialManager[SocialBiLogHelper]( 5222): skip commit this time
,E/Icing   ( 4251): Loading extension by file descriptor -1 failed,
,E/AndroidHttpClient( 5067): Leak found
E/AndroidHttpClient( 5067): java.lang.IllegalStateException: AndroidHttpClient created and never closed
,E/AndroidHttpClient( 5067): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5067): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5067): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5067): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5067): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5067): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5067): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5067): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5067): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5067): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5067): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5067): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5067): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5067): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5067): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5067): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/PackageManager(  956):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4251, uid=10024, userID:0
,I/PackageManager(  956):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4251, uid=10024, userID:0
I/PackageManager(  956):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4251, uid=10024, userID:0
,I/PackageManager(  956):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4251, uid=10024, userID:0
,D/AccTypeManager( 1678): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/AccTypeManager( 1678): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/ResourcesManager( 1475): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/SystemReader(  956): Cannot find grip_rejection_width, use default value instead
I/Icing   ( 4251): updateResources: need to parse f{com.google.android.gms}
W/ResourcesManager(  956): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/AccTypeManager( 1678): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
I/Prism.ItemManager( 5222): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5222): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1526): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1526): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1526): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Launcher( 1526): Deferring update until onResume
D/Launcher( 1526): waitUntilResume // bindAppsUpdated
D/PhoneApp( 1475): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1678): Unsupported attribute readOnly
,W/PackageManager(  956): Unable to load service info ResolveInfo{1a8faef5 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  956): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  956): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  956): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  956): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  956): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  956): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  956): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  956): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  956): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  956): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  956): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  956): 	at com.android.server.SystemServer.main(SystemServer.java:225),
W/PackageManager(  956): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  956): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  956): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  956): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/Icing   ( 4251): Internal init done: storage state 0
,I/Icing   ( 4251): Post-init done
,D/PMS     (  956): releaseWL(ab5aa1a): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
I/BackupManagerService(  956): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,I/GAv4    ( 5195): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
,I/GAv4    ( 5195):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5195):   adb logcat -s GAv4
,W/GAv4    ( 5195): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,V/GmsNetworkLocationProvi( 1823): DISABLE
,W/GAv4    ( 5195): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 5195): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/GCoreNlp( 1823): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/AnalyticsTrackerProxyImpl( 5195): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,D/ChimeraCfgMgr( 4251): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4251): Module APK com.google.android.play.games already loaded
,V/GLSActivity( 1864): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1864): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1864): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1864): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1864): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1864): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5067): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5067): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5067): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 5067): [1] DailyHygiene.reschedule: Scheduling new run in 840 minutes (failures=5),
,D/Process (  956): killProcessQuiet, pid=4352,
I/ActivityManager(  956): Killing 4352:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/art     ( 1823): Explicit concurrent mark sweep GC freed 23718(1439KB) AllocSpace objects, 7(140KB) LOS objects, 46% free, 4MB/8MB, paused 1.130ms total 65.162ms
,I/ActivityManager(  956): Recipient 4352
,D/Process (  956): killProcessQuiet, pid=4759
I/ActivityManager(  956): Killing 4759:com.htc.mobiledata/u0a46 (adj 15): empty #18
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  956): Recipient 4759,
,D/PMS     (  956): acquireWL(2d1b188b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1823 10024 WorkSource{10024 com.google.android.gms}
D/LocationProviderProxy(  956): applying state to connected service
D/PMS     (  956): releaseWL(2d1b188b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/VoldConnector(  956): SND -> {16 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
W/ContextImpl( 5195): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,I/ActivityManager(  956): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5274 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
D/Process (  956): killProcessQuiet, pid=4793
I/ActivityManager(  956): Killing 4793:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
,D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,W/ResourcesManager( 5195): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5195): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PMS     (  956): acquireWL(3c85fd68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 956 1000 null
,I/ActivityManager(  956): Recipient 4793
I/BatteryService(  956): n_update end
D/WifiService(  956): Client connection lost with reason: 4
D/PMS     (  956): releaseWL(3c85fd68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  956): updateBatteryInfo
,D/PowerUI ( 1218): closing low battery warning: level=100
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  956): plugged=true pluggin=true
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/LocationProviderProxy(  956): applying state to connected service
D/UsbnetService(  956): BroadcastReceiver::onReceive+
D/UsbnetService(  956): onReceive BATTERY_CHANGED
D/UsbnetService(  956):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  956): runPSCheck
D/UsbnetService(  956): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  956): Checking...
D/WifiController(  956): handleMessage: E msg.what=155652
I/HtcPowerSaver(  956): >> updateStatus
D/WifiController(  956): processMsg: ApStaDisabledState
D/WifiController(  956): battery changed pluggedType: 2
D/WifiController(  956): processMsg: DefaultState
D/WifiController(  956): handleMessage: X
,D/PMS     (  956): acquireWL(3eb2c581): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1823 10024 WorkSource{10024 com.google.android.gms}
I/HtcPowerSaver(  956): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  956): << updateStatus
D/PMS     (  956): acquireWL(2d119626): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1823 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  956): releaseWL(3eb2c581): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): acquireWL(13a0b267): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1823 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  956): releaseWL(2d119626): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ResourcesManager( 5274): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/DeviceConnectionService( 1823): client connected with version: 7571000
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,V/JNIHelp ( 5195): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 5195): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5195): Installed default security provider GmsCore_OpenSSL
,I/art     (  956): Explicit concurrent mark sweep GC freed 24563(1257KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.320ms total 179.694ms,
D/PMS     (  956): releaseWL(13a0b267): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1864): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  956): acquireWL(6fb43fe): PARTIAL_WAKE_LOCK  AsyncService 0x1 5274 10167 null
,D/PMS     (  956): acquireWL(1a8dc5ac): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5274 10167 null,
,D/PMS     (  956): releaseWL(6fb43fe): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  956): releaseWL(1a8dc5ac): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/ActivityManager(  956): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5305 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,D/Process (  956): killProcessQuiet, pid=4826
I/ActivityManager(  956): Killing 4826:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  956): Recipient 4826
,I/Prism.ItemManager( 5222): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 5222): loadItems() com.htc.launcher.pageview.WidgetManager@2498add9 +
I/Prism.WidgetManager( 5222): onLoadItems() +
,I/Prism.ItemManager( 1526): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1526): loadItems() com.htc.launcher.pageview.WidgetManager@726e4a2 +
I/Prism.WidgetManager( 1526): onLoadItems() +
,W/ResourcesManager( 1526): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 5222): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  956): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5327 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5327): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/LocationManagerService(  956): getProviders()=[passive]
,W/ResourcesManager( 1526): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5222): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 5305): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,W/asset   ( 5222): Copying FileAsset 0x55a37cea10 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,W/asset   ( 1526): Copying FileAsset 0x55a3a268e0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,I/ActivityManager(  956): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5357 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,W/asset   ( 5305): Copying FileAsset 0x55a367f180 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.,
,I/UpdateIcingCorporaServi( 5305): UpdateCorporaTask done [took 130 ms] updated apps [took 130 ms] 
,D/Process (  956): killProcessQuiet, pid=4938
,I/ActivityManager(  956): Killing 4938:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/SQLiteLog( 5327): (283) recovered 15 frames from WAL file /data/data/com.htc.album/databases/MMexternal.db-wal
,E/Prism.WidgetManager( 1526): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1526): onLoadItems() -
I/Prism.ItemManager( 1526): loadItems() com.htc.launcher.pageview.WidgetManager@726e4a2 -
I/Prism.WidgetManager( 5222): onLoadItems() -
I/Prism.ItemManager( 5222): loadItems() com.htc.launcher.pageview.WidgetManager@2498add9 -
,D/PhoneApp( 1475): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1475): -- N1 =0
,D/PhoneApp( 1475): -- N2 =0
,D/PhoneApp( 1475): -- N3 =0
,I/ActivityManager(  956): Recipient 4938,
,I/MusicStore( 5357): Database version: 120
,I/HtcModeClient( 3135): handler message = 4011,
,E/HtcModeClient( 3135): Check connection and retry 5 times.
,D/VoldConnector(  956): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5357): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,D/VoldConnector(  956): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5357): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  956): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5357): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 5357): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
,W/ResourcesManager( 5357): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5357): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 5357): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 5357): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c338b3c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5357): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5357): GMSCore installation verified
,I/ConfigStore( 5357): Config Database version: 1,
,I/PackageManager(  956):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5357, uid=10159, userID:0
,D/WifiDisplayAdapter(  956): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  956):     Client/Owner: Client
D/WifiDisplayAdapter(  956):     GroupId: 
D/WifiDisplayAdapter(  956):     Passphrase: 
D/WifiDisplayAdapter(  956):     SessionId: 0
,D/WifiDisplayAdapter(  956):     IP Address: }
,D/MediaRouterService(  956): Client com.google.android.music (pid 5357): Registered
,D/WifiDisplayAdapter(  956): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  956):     Client/Owner: Client
D/WifiDisplayAdapter(  956):     GroupId: 
D/WifiDisplayAdapter(  956):     Passphrase: 
D/WifiDisplayAdapter(  956):     SessionId: 0
D/WifiDisplayAdapter(  956):     IP Address: }
,D/Process (  956): killProcessQuiet, pid=4912
I/ActivityManager(  956): Killing 4912:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/MediaRouter( 5357): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/ActivityManager(  956): Recipient 4912,
,D/TelephonyReceiver( 1475): bind: true,
,I/ActivityManager(  956): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5392 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager(  956): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=5405 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/PackageManager(  956):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5357, uid=10159, userID:0
,I/GHttpClientFactory( 5357): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/DFPI.PIReciver( 5392): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
I/GoogleURLConnFactory( 5357): Using platform SSLCertificateSocketFactory
,I/DFPI.ApkInstallService( 5392): onHandleIntent
I/DFPI.ApkInstallService( 5392): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5392): check CID = HTC__102
I/DFPI.ApkInstallService( 5392): There is no Demo.apk in sd card or phone storage
,W/HtcWrapAdjustableCursorFactory( 5405): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
D/MessageFrequencyProvider( 5405): onCreate
I/ActivityManager(  956): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5439 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/GetPrviateResource( 5405): GetPrviateResource,
V/GetPrviateResource( 5405): GetPrviateResource
,D/MessageCustFlag( 5405): sense_version=6.0
,D/GenericMessagesProvider( 5405): query uri: content://htc-messages/wappush/count
,E/SQLiteLog( 5405): (14) cannot open file at line 30058 of [9491ba7d73]
E/SQLiteLog( 5405): (14) os_unix.c:30058: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
D/BTAccessoryUtil( 5405): createReceiver
E/SQLiteConnection( 5405): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 5405): DB info: errno = 2, errno message = No such file or directory
D/BTAccessoryUtil( 5405): registerReceiver return intent = null
,D/MessageCustFlag( 5405): sku_id=118
E/SQLiteDatabase( 5405): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 5405): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
E/SQLiteDatabase( 5405): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 5405): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5405): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5405): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5405): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err( 5405): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
,W/System.err( 5405): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/System.err( 5405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/System.err( 5405): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 5405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 5405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 5405): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/System.err( 5405): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/System.err( 5405): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/System.err( 5405): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
W/System.err( 5405): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 5405): 	at android.content.ContentProvider.query(ContentProvider.java:960)
W/System.err( 5405): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
W/System.err( 5405): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
W/System.err( 5405): 	at android.os.Binder.execTransact(Binder.java:454)
D/HtcBuildUtils( 5405): getRATByHtcTelephonyCapability:1
W/SystemReader( 5405): Cannot find qct_8960_interface, use default value instead
D/Process (  956): killProcessQuiet, pid=4850
I/ActivityManager(  956): Killing 4850:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  956): Recipient 4850
,D/TelephonyReceiver( 1475): switchBindHtcMsgCursor: null,
,D/Process (  956): killProcessQuiet, pid=4736
I/ActivityManager(  956): Killing 4736:com.htc.task/u0a69 (adj 15): empty #17
,D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  956): Recipient 4736,
,D/BluetoothManagerService(  956): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  956): disable(): mBluetooth = null mBinding = false
W/Settings:Agent(  956): MONITOR_LOG
W/Settings:Agent(  956): name: bluetooth_on
W/Settings:Agent(  956): value: 0
W/Settings:Agent(  956): >> traceCallingStack()
W/Settings:Agent(  956): Process.myPid(): 956
W/Settings:Agent(  956): Process.myTid(): 1646
W/Settings:Agent(  956): Process.myUid(): 1000
W/Settings:Agent(  956): 
W/Settings:Agent(  956): 
,W/System.err(  956): java.lang.Throwable: stack dump
,W/System.err(  956): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  956): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  956): ,	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  956): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  956): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  956): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  956): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  956): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
W/System.err(  956): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  956): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  956): 
W/Settings:Agent(  956): << traceCallingStack(): 13(ms)
D/BluetoothManagerService(  956): Message: MESSAGE_DISABLE
,D/WifiService(  956): New client listening to asynchronous messages
,E/WifiTrafficPoller(  956): ADD_CLIENT: 7
D/WifiManager( 4887): setWifiEnabled: Base Package Name=com.example.hello, uid=10373
,I/ActivityManager(  956): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5465 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a
,D/WifiService(  956): setWifiEnabled: false pid=4887, uid=10373
,E/WifiService(  956): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  956): isSprintWifiRestricted(): false
I/WifiService(  956): isMdmWifiRestricted(): false
,W/Settings:Agent(  956): MONITOR_LOG
,W/Settings:Agent(  956): name: wifi_on
W/Settings:Agent(  956): value: 0
W/Settings:Agent(  956): >> traceCallingStack()
W/Settings:Agent(  956): Process.myPid(): 956
W/Settings:Agent(  956): Process.myTid(): 1162
W/Settings:Agent(  956): Process.myUid(): 1000
W/Settings:Agent(  956): 
W/Settings:Agent(  956): 
W/System.err(  956): java.lang.Throwable: stack dump
W/System.err(  956): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  956): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  956): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  956): ,	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  956): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  956): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  956): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  956): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  956): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  956): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  956): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  956): 
W/Settings:Agent(  956): << traceCallingStack(): 6(ms)
,D/VoldConnector(  956): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/}
D/WifiController(  956): handleMessage: E msg.what=155656
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/
,D/WifiController(  956): processMsg: ApStaDisabledState
D/WifiController(  956): handleMessage: X
W/ContextImpl( 5439): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
I/jxcore-log( 4887): ****TEST TOOK:  5126  ms ****
I/jxcore-log( 4887): 
I/jxcore-log( 4887): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4887): 
,I/SoundPicker( 5465): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
,I/SoundPicker( 5465): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5465): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5465): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5465): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/DFPI.PIReciver( 5392): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
,W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,I/SoundPicker( 5465): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5465): SoundPickerReceiver [onReceive] startService
I/DFPI.ApkInstallService( 5392): onHandleIntent,
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/DFPI.ApkInstallService( 5392): Media Scan Finished Case 
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 4)
D/DFPI.ApkInstallService( 5392): check CID = HTC__102
I/DFPI.ApkInstallService( 5392): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
,I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
,I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5465): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5,
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
D/DFPI.PIReciver( 5392): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/DFPI.ApkInstallService( 5392): onHandleIntent
,I/DFPI.ApkInstallService( 5392): Media Scan Finished Case 
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
D/DFPI.ApkInstallService( 5392): check CID = HTC__102
I/DFPI.ApkInstallService( 5392): There is no Demo.apk in sd card or phone storage
I/SoundPicker( 5465): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5465): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/DFPI.PIReciver( 5392): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,I/DFPI.ApkInstallService( 5392): onHandleIntent
I/DFPI.ApkInstallService( 5392): Media Scan Finished Case 
I/SoundPicker( 5465): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/DFPI.ApkInstallService( 5392): check CID = HTC__102
I/DFPI.ApkInstallService( 5392): There is no Demo.apk in sd card or phone storage
I/SoundPicker( 5465): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5465): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) },
V/SoundPicker( 5465): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5465): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2,
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5465): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/ActivityManager(  956): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=5498 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/art     ( 1864): Explicit concurrent mark sweep GC freed 11253(617KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 609us total 40.194ms,
,D/DFPI.PIReciver( 5392): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
V/AlarmManager(  956): sending alarm PendingIntent{281b987a: PendingIntentRecord{2491482b com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1447782187369, Int=0
,I/DFPI.ApkInstallService( 5392): onHandleIntent
I/DFPI.ApkInstallService( 5392): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5392): check CID = HTC__102,
I/DFPI.ApkInstallService( 5392): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5465): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5465): SoundPickerReceiver [onReceive] startService
,D/DFPI.PIReciver( 5392): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/MediaStoreImporter( 5357): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/DFPI.ApkInstallService( 5392): onHandleIntent
I/DFPI.ApkInstallService( 5392): Media Scan Finished Case 
,E/cutils-trace( 5492): Error opening trace file: Permission denied (13)
D/DFPI.ApkInstallService( 5392): check CID = HTC__102
I/DFPI.ApkInstallService( 5392): There is no Demo.apk in sd card or phone storage
I/SoundPicker( 5465): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5465): SoundPickerReceiver [onReceive] startService
,D/TelephonyReceiver( 1475): bind: false
D/TelephonyReceiver( 1475): switchBindHtcMsgCursor: null
,D/DFPI.PIReciver( 5392): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/art     (  956): Explicit concurrent mark sweep GC freed 16194(879KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 3.604ms total 140.966ms,
,I/DFPI.ApkInstallService( 5392): onHandleIntent
I/DFPI.ApkInstallService( 5392): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5392): check CID = HTC__102
I/DFPI.ApkInstallService( 5392): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5465): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
D/CustomizationManager( 5492): ====startRecUseTime====
D/htc.customization.log.level( 5492):  is 
W/CustomizationLogLevel( 5492): Level value is invalid, use default level 2
,I/SoundPicker( 5465): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/MediaStoreImporter( 5357): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac,
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
D/GCM     ( 1864): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,D/AuthorizationBluetoothService( 1864): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,V/GmsCoreStatsServiceLauncher( 4251): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,D/WearableService( 4601): callingUid 10024, callindPid: 4601,
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/PackageManager(  956):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4251, uid=10024, userID:0
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac,
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
E/MDM     ( 1823): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5465): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5465): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5465): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5465): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5465): TurnFileToMediaUriServi,ce [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/LocationInitializer( 4251): Restart initialization of location
I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/GCM     ( 1864): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/CustomizationManager( 5492):  Read ACC file spent 0.038 (s)
D/AuthorizationBluetoothService( 1864): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/CIDMapFileReader( 5492): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5492): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5492): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5492): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5492): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5492): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5492): Parsing tag item name = HTC__031
I/MediaStoreImporter( 5357): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
V/CustomizationCIDLoader( 5492): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5492): Parsing tag category name = system
I/CustomizationCIDLoader( 5492): Parsing tag category name = application
I/CustomizationCIDLoader( 5492): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5492): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5492): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5492): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5492): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5492): add string-array item, value = 42507
I/CustomizationCIDLoader( 5492): add string-array item, value = 21902
I/CustomizationCIDLoader( 5492): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5492): add string-array item, value = 23420
I/CustomizationCIDLoader( 5492): add string-array item, value = 22299
I/CustomizationCIDLoader( 5492): add string-array item, value = 24002
I/CustomizationCIDLoader( 5492): add string-array item, value = 23210
I/CustomizationCIDLoader( 5492): add string-array item, value = 23205
I/CustomizationCIDLoader( 5492): add string-array item, value = 23806
I/CustomizationCIDLoader( 5492): add string-array item, value = 23430
I/CustomizationCIDLoader( 5492): add string-array item, value = 23408
I/CustomizationCIDLoader( 5492): add string-array item, value = 27205
I/CustomizationCIDLoader( 5492): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5492): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5492): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5492): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5492): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5492): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5492): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5492): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5492): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5492): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5492): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5492): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5492):  Read CID file spent 0.086 (s)
D/CustomizationManager( 5492):  All configurations done spent 0.086 (s)
V/GmsCoreStatsServiceLauncher( 4251): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/PackageManager(  956):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4251, uid=10024, userID:0
I/ActionCombine( 5498): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
E/MDM     ( 1823): [145] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/art     ( 3634): Explicit concurrent mark sweep GC freed 55166(3MB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1536KB/5MB, paused 511us total 33.980ms
D/LocationInitializer( 4251): Restart initialization of location
I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/PackageManager(  956): deletePackageAsUser: pkg=com.example.hello, pid=5492, uid=2000 userid=0
I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/ActivityManager(  956): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/RemoteViews( 1218): setHTCTheme(com.htc.updater,true,33751145)
,I/ActivityManager(  956): Killing 4887:com.example.hello/u0a373 (adj 0): stop com.example.hello
D/Process (  956): killProcessQuiet, pid=4887
,D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,I/RemoteViews( 1218): apply : com.htc.updater 0 12 2 36
,W/PackageSettings(  956): Skipping PackageSetting{34074813 com.test.thalitest/10366} due to missing metadata
,D/FindExtension( 1218): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/ThreadedRenderer( 1218): Defer allocateBuffers to drawing time
,I/ActivityManager(  956): Recipient 4887
I/WindowState(  956): WIN DEATH: Window{1752fd98 u0 com.example.hello/com.example.hello.MainActivity}
E/InputEventReceiver( 1361): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{332a79f1 uid 10373 pid 4887} (c)',
D/WifiService(  956): Client connection lost with reason: 4
,W/ActivityManager(  956): Force removing ActivityRecord{2935d716 u0 com.example.hello/.MainActivity t8}: app died, no saved state
,I/ActivityManager(  956): Force stopping com.example.hello appid=10373 user=0: pkg removed
,W/ActivityManager(  956): Spurious death for ProcessRecord{1bde48f6 4887:com.example.hello/u0a373}, curProc for 4887: null
,D/DotMatrix( 1308): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello,
,D/DotMatrix( 1308): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/PMS     (  956): acquireWL(3c2434f7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1823 10024 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1308): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
D/PMS     (  956): releaseWL(3c2434f7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
I/Prism.ItemManager( 5222): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5222): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/GeofencerStateMachine( 1823): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1678): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,I/FeedHostManager( 1526): [onResume]
I/FeedProviderManager( 1526): onResume
I/SocialFeedProvider( 1526): +onResume
I/SocialFeedProvider( 1526): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1526): -onResume
I/ConnectivityHelper( 1526): [getCurrentConnectionType] no network connection
I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,W/SystemReader(  956): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1678): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/StatusBarManagerService(  956): setSystemUiVisibility(0x700)
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,D/StatusBarManagerService(  956): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
D/StatusBarManagerService(  956): hiding MENU key
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/InputMethodManagerService(  956): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
D/FindExtension( 1526): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/MediaStoreImporter( 5357): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 5465): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5465): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5465): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5465): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/ThreadedRenderer( 1526): Defer allocateBuffers to drawing time
,D/PhoneApp( 1475): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED,
I/Prism.ItemManager( 1526): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1526): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
W/InputMethodManagerService(  956): Got RemoteException sending setActive(false) notification to pid 4887 uid 10373
D/AccTypeManager( 1678): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/StatusBarManagerService(  956): swetImeWindowStatus vis=0 backDisposition=0
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/InputMethodManagerService(  956): Enable input method client, pid=1526
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
W/ResourcesManager(  956): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
E/ExternalAccountType( 1678): Unsupported attribute readOnly
I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac,
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac,
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
D/PMS     (  956): acquireWL(25e25a18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1864 10024 WorkSource{10024 com.google.android.gms}
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8,
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
D/PMS     (  956): releaseWL(25e25a18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): acquireWL(1f63dc71): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1864 10024 WorkSource{10024 com.google.android.gms},
I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,D/PMS     (  956): releaseWL(1f63dc71): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
I/MediaStoreImporter( 5357): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5465): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5465): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5465): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/art     (  956): Explicit concurrent mark sweep GC freed 16016(1217KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/24MB, paused 3.954ms total 229.323ms
,D/StatusBarManagerService(  956): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  956): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  956): hiding MENU key
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,W/PackageManager(  956): Unable to load service info ResolveInfo{2133e1f4 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  956): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  956): 	,at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  956): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  956): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  956): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  956): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  956): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  956): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  956): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  956): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  956): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  956): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  956): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  956): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  956): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  956): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  956): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5565 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/MediaStoreImporter( 5357): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac,
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
I/ConfigService( 1864): onDestroy
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac,
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 5465): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5465): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5465): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac,
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,D/PhoneMonitor( 5565): Register our PhoneStateListener
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,D/JobSchedulerService(  956): Receieved: android.intent.action.PACKAGE_REMOVED,
I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
D/TaskPersister(  956): removeObsoleteFile: deleting file=8_task.xml
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/ActivityManager(  956): Killing 4540:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  956): killProcessQuiet, pid=4540
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/PhoneMonitor( 5565): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false,
,D/PhoneMonitor( 5565): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/ActivityManager(  956): Recipient 4540,
,W/OpenGLRenderer( 1526): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5465): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5465): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
,I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5465): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/GCM     ( 1864): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
D/ChimeraCfgMgr( 4251): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/ChimeraCfgMgr( 4251): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4251): [KidAccountFixer] No network connection
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,E/SQLiteDatabase( 1864): Failed to open database '/data/data/com.google.android.gms/databases/ns.db'.
E/SQLiteDatabase( 1864): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1864): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 1864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 1864): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1864): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 1864): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 1864): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 1864): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 1864): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1864): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1864): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1864): 	at com.google.android.gms.gcm.nts.n.b(SourceFile:252)
E/SQLiteDatabase( 1864): 	at com.google.android.gms.gcm.nts.k.a(SourceFile:562)
E/SQLiteDatabase( 1864): 	at com.google.android.gms.gcm.nts.k.b(SourceFile:540)
E/SQLiteDatabase( 1864): 	at com.google.android.gms.gcm.nts.SchedulerReceiver.onReceive(SourceFile:176)
E/SQLiteDatabase( 1864): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/SQLiteDatabase( 1864): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/SQLiteDatabase( 1864): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 1864): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1864): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 1864): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 1864): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 1864): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 1864): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 1864): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
E/AndroidRuntime( 1864): FATAL EXCEPTION: main
E/AndroidRuntime( 1864): Process: com.google.process.gapps, PID: 1864
E/AndroidRuntime( 1864): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.nts.SchedulerReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1864): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1864): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1864): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1864): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1864): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1864): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1864): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1864): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1864): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1864): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1864): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1864): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 1864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 1864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 1864): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 1864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 1864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 1864): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 1864): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 1864): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 1864): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 1864): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 1864): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 1864): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 1864): 	at com.google.android.gms.gcm.nts.n.b(SourceFile:252)
E/AndroidRuntime( 1864): 	at com.google.android.gms.gcm.nts.k.a(SourceFile:562)
E/AndroidRuntime( 1864): 	at com.google.android.gms.gcm.nts.k.b(SourceFile:540)
E/AndroidRuntime( 1864): 	at com.google.android.gms.gcm.nts.SchedulerReceiver.onReceive(SourceFile:176)
E/AndroidRuntime( 1864): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1864): 	... 9 more
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5465): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,E/ActivityManager(  956): App crashed! Process: com.google.process.gapps
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
I/DropBoxManagerService(  956): Usage (1282) > Quota (1280)
,E/DropBoxManagerService(  956): Can't write tombstone file,
E/DropBoxManagerService(  956): java.io.FileNotFoundException: /data/system/dropbox/SYSTEM_TOMBSTONE@1447675253956.lost: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  956): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  956): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  956): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  956): 	at com.android.server.DropBoxManagerService$EntryFile.<init>(DropBoxManagerService.java:531)
E/DropBoxManagerService(  956): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:804)
E/DropBoxManagerService(  956): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:197)
E/DropBoxManagerService(  956): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  956): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  956): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  956): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  956): ,	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  956): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  956): 	... 7 more
E/DropBoxManagerService(  956): Can't write: system_app_crash
E/DropBoxManagerService(  956): java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  956): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  956): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  956): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  956): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  956): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  956): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  956): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  956): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  956): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  956): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  956): 	... 5 more
,D/Messaging( 5405): supportCMAS(SIE)/init? false/true
D/MmsConfig( 5405): networkCode: 
D/MessageCustFlag( 5405): sku_id=118
,D/MmsConfig( 5405): SIE smsPri: null
D/MmsConfig( 5405): networkCode: 
,I/art     ( 3634): Explicit concurrent mark sweep GC freed 4769(214KB) AllocSpace objects, 0(0B) LOS objects, 73% free, 1481KB/5MB, paused 630us total 31.560ms
,D/MmsConfig( 5405): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 5405): startAsyncQueryReports ---
D/StatusBarManagerService(  956): setSystemUiVisibility(0xc0000000)
,D/MmsAsyncWorkHandler( 5405): 
D/MmsAsyncWorkHandler( 5405): HM tk = 20001
D/StatusBarManagerService(  956): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ReportIndicatorCache( 5405): MSG_QUERY_REPORTS >>
D/StatusBarManagerService(  956): hiding MENU key
,D/SettingsManager( 5405): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@3c972ba1
D/Messaging( 5405): mNeedToUpdateDate2 start
I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
D/TelephUtils( 1475): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1475): sku_id=118
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/Messaging( 5405): mccmnc> 
D/DraftCache( 5405): [DraftCache/1] DraftCache.constructor
D/DraftCache( 5405): [DraftCache/1] refresh
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,D/DraftCache( 5405): [DraftCache/116] rebuildCache
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,D/TelephUtils( 1475): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1475):  slotId = -1000
D/MmsSmsV2Provider( 1475): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
D/MmsConfig( 5405): networkCode: 
,D/TelephUtils( 1475): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1475):  slotId = -1000
D/MmsSmsV2Provider( 1475): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/Messaging( 5405): ViewCache CreatePreloadOnlyConversationList
,I/SoundPicker( 5465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/TelephUtils( 1475): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1475):  slotId = -1000
D/MmsSmsV2Provider( 1475): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/Process (  956): killProcessQuiet, pid=5009
I/ActivityManager(  956): Killing 5009:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MessageCustFlag( 5405): sense_version=6.0
,D/Jerry   ( 5405): start to preload cursor >>>>>>>
,D/Messaging( 5405): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,I/ActivityManager(  956): Recipient 5009
,D/TelephUtils( 1475): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/Jerry   ( 1475): URI_DRAFT
,D/TelephUtils( 1475): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1475):  slotId = -1000
D/MmsSmsV2Provider( 1475): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 5405): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 5405): [DraftCache/116] rebuildCache time: 12
D/MmsAsyncWorkHandler( 5405): 
D/MmsAsyncWorkHandler( 5405): HM tk = 20002
,D/Messaging( 5405): mNeedToUpdateDate2: false
D/TelephUtils( 1475): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1475):  slotId = -1000
D/PhoneStorageUtil( 5405): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 5405): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 5405): createReceiver
,D/TelephUtils( 1475): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1475): sku_id=118
,D/Messaging( 5405): ViewCache CreatePreload,
D/Messaging( 5405): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1475): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,V/MmsProvider( 1475): Update uri=content://mms, match=0
V/MmsProvider( 1475): selection=st=129 AND m_type!=134
D/Messaging( 5405): Reset downloading state: 0
D/TelephUtils( 1475): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/Cust_MMSMS( 5405): _has_set_default_values_2=true
,D/AccFlag ( 1475): sku_id=118
,V/MmsSystemEventReceiver( 5405): TransactionService is going to be woken up.
,D/MsgPreferenceUtils( 5405): def_index: 0
,V/TransactionService( 5405): 1-Creating TransactionService
,D/MsgPreferenceUtils( 5405): globalIndex = 1,
,D/MsgPreferenceUtils( 5405): phone state: true
,D/MsgPreferenceUtils( 5405): sd state: false
D/MsgPreferenceUtils( 5405): vIndex = 0
,V/TransactionService( 5405): onStartCommand: 1,
D/MmsSystemEventReceiver( 5405): unRegisterForConnectionStateChanges
,V/TransactionService( 5405): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 5405): Loading previous transactions.
,D/TelephUtils( 1475): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50,
D/AccFlag ( 1475): device_type: 1
,D/TransactionService( 5405): Force clearing mTransactionList
D/TransactionService( 5405): Force set service start id to 1
V/TransactionService( 5405): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5405): unRegisterForConnectionStateChanges
,D/TransactionService( 5405): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 5405): Destroying TransactionService
,V/TransactionService( 5405): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler },
,I/Prism.ItemManager( 5222): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 5222): loadItems() com.htc.launcher.pageview.WidgetManager@2498add9 +
I/Prism.WidgetManager( 5222): onLoadItems() +
,W/ResourcesManager( 5222): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/Prism.ItemManager( 1526): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1526): loadItems() com.htc.launcher.pageview.WidgetManager@726e4a2 +
I/Prism.WidgetManager( 1526): onLoadItems() +

```
