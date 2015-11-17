#### Test 50388019c82294c_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
I/ThumbnailProvider( 4470): ThumbnailProvider onCreate()
I/DocumentBroadcastReceiver( 4470): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
I/BroadcastProcessorService( 4470): [START] processBroadcastIntent ...
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
--------- beginning of system
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3782/cgroup.procs: No such file or directory
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
I/BroadcastProcessorService( 4470): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
I/SystemInfo( 4470): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 4470): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
I/BroadcastProcessorService( 4470): [START] DocumentService startDocumentService
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
I/DocumentService( 4470): DocumentService onCreate ... service
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
D/GalleryCacheReady( 4427): Receive action.ACTION_MEDIA_SCANNER_FINISHED
D/GalleryCacheReady( 4427): handleMeidaScanFinish()
D/FaceInterface( 4427): requestFaceScan() is called.
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
W/ContextImpl( 4470): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
W/ContextImpl( 4470): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
W/LocalSuggestAlbumData( 4427): query fail: 
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
W/LocalSuggestAlbumData( 4427): query fail: 
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
I/FaceInterface( 4427): startFaceScan() : waiting 5 sec
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
E/SystemInfo( 4470): [SIOP LEVEL] : 0
D/GCM     ( 1665): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
I/DocumentService( 4470): [BEGIN SYNC] DocumentService beginIndexing :16
D/AuthorizationBluetoothService( 1665): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 1854): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ContextImpl( 4470): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
E/MDM     ( 1691): [191] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/LocationInitializer( 1854): Restart initialization of location
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/File    ( 4470): fail readDirectory() errno=13
E/File    ( 4470): fail readDirectory() errno=13
I/SystemInfo( 4470): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 4470): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 4470): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :73
E/DocumentService( 4470): [THUMBNAIL] Total Time taken for each file :0
E/        ( 4470): [INDEX] Total time taken for each file :0
I/DocumentService( 4470): DocumentService onDestroy start
I/HomeSyncInstallReceiver( 1454): This pkg do not need BT addr. Do nothing
I/DocumentService( 4470): DocumentService onDestroy end
I/splitIntent( 1016): Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 9 r.nextReceiver= 2 receivers.size=41
I/splitIntent( 1016): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
I/DocumentService( 4470): DocumentService cleanupEverything start
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/PackagesMonitor( 4427): PackagesMonitor onReceive :com.example.hello
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/IndexParserThreadsManager( 4470): InterruptedException: null
E/Zygote  ( 4502): MountEmulatedStorage()
I/libpersona( 4502): KNOX_SDCARD checking this for 10100
E/Zygote  ( 4502): v2
I/libpersona( 4502): KNOX_SDCARD not a persona
I/SELinux ( 4502): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=4502 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 4502): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
I/SystemInfo( 4470): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 4470): DocumentService cleanupEverything end
I/Process ( 4470): Sending signal. PID: 4470 SIG: 9
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
E/SELinux ( 4502): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/lowmemorykiller(  255): Error writing /proc/4470/oom_score_adj; errno=22
I/art     ( 1665): Explicit concurrent mark sweep GC freed 18100(1038KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 10MB/17MB, paused 1.041ms total 42.046ms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 4502): TimaSignature is unavailable
D/ActivityThread( 4502): Added TimaKeyStore provider
I/art     (  308): Explicit concurrent mark sweep GC freed 8690(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 48.365ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 669us total 16.555ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 599us total 16.419ms
E/Zygote  ( 4521): MountEmulatedStorage()
I/libpersona( 4521): KNOX_SDCARD checking this for 10035
E/Zygote  ( 4521): v2
I/libpersona( 4521): KNOX_SDCARD not a persona
I/SELinux ( 4521): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageChangeEventReceiver: pid=4521 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4521): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4521): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
E/lowmemorykiller(  255): Error opening /proc/4470/oom_score_adj; errno=2
I/ActivityManager( 1016): Process com.samsung.indexservice (pid 4470)(adj 11) has died(57,1122)
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 4521): TimaSignature is unavailable
D/ActivityThread( 4521): Added TimaKeyStore provider
D/PackageIntentReceiver( 4502): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 4502): Not GearManger package! 
E/Zygote  ( 4538): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=4538 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 4538): v2
I/libpersona( 4538): KNOX_SDCARD checking this for 1000
I/SELinux ( 4538): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 4538): KNOX_SDCARD not a persona
I/SELinux ( 4538): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/SELinux ( 4538): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/GAV2    ( 4133): Thread[GAThread,5,main]: No campaign data found.
D/Mms/FreeMessageStatusReceiver( 4287): onReceive, action : android.intent.action.PACKAGE_ADDED
E/Zygote  ( 4552): MountEmulatedStorage()
E/Zygote  ( 4552): v2
I/libpersona( 4552): KNOX_SDCARD checking this for 1000
I/libpersona( 4552): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=4552 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 4552): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 4552): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4552): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 4538): TimaSignature is unavailable
D/ActivityThread( 4538): Added TimaKeyStore provider
D/Mms/FreeMessageReceiverService( 4287): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 4287): onHandleIntent: ACTION_PACKAGE_ADDED
D/TimaKeyStoreProvider( 4552): TimaSignature is unavailable
D/ActivityThread( 4552): Added TimaKeyStore provider
I/ActivityManager( 1016): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=4569 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
E/Zygote  ( 4569): MountEmulatedStorage()
I/libpersona( 4569): KNOX_SDCARD checking this for 10047
E/Zygote  ( 4569): v2
I/libpersona( 4569): KNOX_SDCARD not a persona
I/SELinux ( 4569): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Waited long enough for: ServiceRecord{1282ca2d u0 com.samsung.android.providers.context/.ContextService}
I/GAv4-SVC( 1854): Google Analytics 7.8.99 is starting up.
I/SELinux ( 4569): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4569): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/PCWCLIENTTRACE_LOG( 4538): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 4538): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 4538): new DMDBOpenHelper instance
E/SPPClientService( 4521): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 4521): [PushClientApplication] Push log off : This is Ship build version
D/TimaKeyStoreProvider( 4569): TimaSignature is unavailable
D/ActivityThread( 4569): Added TimaKeyStore provider
D/SPPClientService( 4521): PushLog.txt file is not deleted.
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/SPPClientService( 4521): PushLog.txt file is not deleted.
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/SPPClientService( 4521): ============PushLog. stop!
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4588): MountEmulatedStorage()
E/Zygote  ( 4588): v2
I/libpersona( 4588): KNOX_SDCARD checking this for 10091
I/libpersona( 4588): KNOX_SDCARD not a persona
I/SELinux ( 4588): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4588 uid=10091 gids={50091, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/DBG_DM  ( 2830): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 12 sec
I/SELinux ( 4588): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1016): Killing 3792:com.android.email/u0a145 (adj 15): empty #31
E/SELinux ( 4588): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/PCWCLIENTTRACE_PushUtil( 4538): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4538): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4538): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4538): [onReceive] - android.intent.action.PACKAGE_ADDED
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 4569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4569): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4569): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/Zygote  ( 4602): MountEmulatedStorage()
D/PackageManager( 1016): [MSG] SEND_PENDING_BROADCAST
E/Zygote  ( 4602): v2
I/libpersona( 4602): KNOX_SDCARD checking this for 1000
I/SELinux ( 4602): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 4602): KNOX_SDCARD not a persona
I/SELinux ( 4602): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1016): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=4602 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:95, scale:100, status:2, health:2, present:true, voltage: 4137, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
E/SELinux ( 4602): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/ActivityManager( 1016): Killing 3737:com.vlingo.midas/u0a31 (adj 15): empty #31
D/TimaKeyStoreProvider( 4588): TimaSignature is unavailable
D/ActivityThread( 4588): Added TimaKeyStore provider
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.PACKAGE_CHANGED
I/PageBuddyNotiSvc( 3166): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
D/TimaKeyStoreProvider( 4602): TimaSignature is unavailable
D/ActivityThread( 4602): Added TimaKeyStore provider
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 95
I/MediaStoreImporter( 4357): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:95 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:95 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:95 status:2 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :95 plugged : 2
D/AndroidRuntime( 4518): 
D/AndroidRuntime( 4518): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:95 status:2 health:2
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4620): MountEmulatedStorage()
I/libpersona( 4620): KNOX_SDCARD checking this for 10032
E/Zygote  ( 4620): v2
I/libpersona( 4620): KNOX_SDCARD not a persona
I/SELinux ( 4620): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=4620 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
D/AndroidRuntime( 4518): CheckJNI is OFF
D/AndroidRuntime( 4518): readGMSProperty: start
D/AndroidRuntime( 4518): readGMSProperty: already setted!!
D/AndroidRuntime( 4518): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4518): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4518): readGMSProperty: end
D/AndroidRuntime( 4518): addProductProperty: start
I/SELinux ( 4620): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4620): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 3818:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 4620): TimaSignature is unavailable
D/ActivityThread( 4620): Added TimaKeyStore provider
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/RegisteredComponentCache( 1454): Collect Tech packages for Knox
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PersonaManager( 1454): isKioskContainerExistOnDevice
D/MyFiles ( 4569): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/ActivityManager( 1016): Waited long enough for: ServiceRecord{34fe6bae u0 com.android.settings/.wifi.WifiCredService}
W/IntentResolver( 1016): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
D/WallpaperManager( 1491): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/WallpaperManager( 1491): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1016): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService( 1016): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
I/ActivityManager( 1016): Killing 3721:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
D/PersonaManager( 1454): isKioskContainerExistOnDevice
D/RegisteredServicesCache( 1454): empty dynamic service
W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SMD     (  289): DCD OFF
W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/art     ( 1016): Explicit concurrent mark sweep GC freed 29366(1643KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/40MB, paused 2.432ms total 157.543ms
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
I/ActivityManager( 1016): Killing 3852:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
D/AcmsPackageEventListener( 4602): Received: android.intent.action.PACKAGE_ADDED
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue( 1016): Exception when sending broadcast to ComponentInfo{com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver}
W/BroadcastQueue( 1016): android.os.TransactionTooLargeException
W/BroadcastQueue( 1016): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1016): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1016): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1016): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1016): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1016): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
W/BroadcastQueue( 1016): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1016): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
W/BroadcastQueue( 1016): 	at android.os.Binder.execTransact(Binder.java:461)
I/TactileAssist( 1016): enable value -1
I/TactileAssist( 1016): internal enable value -1
I/TactileAssist( 1016): intensity value -1
I/TactileAssist( 1016): saveAppList value true
I/TactileAssist( 1016): List of disabled apps :
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/Zygote  ( 4647): MountEmulatedStorage()
E/Zygote  ( 4647): v2
I/libpersona( 4647): KNOX_SDCARD checking this for 10152
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/libpersona( 4647): KNOX_SDCARD not a persona
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SELinux ( 4647): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4647 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 4647): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4647): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/installd(  285): system dir 0 : /system/app/
E/installd(  285): system dir 1 : /system/priv-app/
E/installd(  285): system dir 2 : /vendor/app/
E/installd(  285): system dir 3 : /oem/app/
W/ContextImpl( 4602): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
D/AcmsService( 4602): Enter Oncreate
D/AcmsServiceMonitor( 4602): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 4602): creating AcmsCore
D/AcmsCore( 4602): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 4602): AcmsCore
D/AcmsCore( 4602): init
D/AcmsCore( 4602): Looper handler is not null
D/AcmsCore( 4602): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 4602): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 4602): Incrementing - Counter value: 1
D/AcmsCore( 4602): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 4602): onStartCommand
D/AcmsService( 4602): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 4602): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 4602): Incrementing - Counter value: 2
D/AcmsService( 4602): Incremented Counter Value : onStartCommand
D/AcmsCertificateMngr( 4602): AcmsCertificateMngr
D/AcmsRevocationMngr( 4602): AcmsRevocationMngr
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 4647): TimaSignature is unavailable
D/ActivityThread( 4647): Added TimaKeyStore provider
D/PackageManager( 1016): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/Zygote  ( 4665): MountEmulatedStorage()
I/libpersona( 4665): KNOX_SDCARD checking this for 10053
E/Zygote  ( 4665): v2
I/libpersona( 4665): KNOX_SDCARD not a persona
I/SELinux ( 4665): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 4665): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4665): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=4665 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
D/ActivityThread( 4602): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
V/BackupManagerService( 1016): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
V/BackupManagerService( 1016): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@5d77c4b
D/TimaKeyStoreProvider( 4665): TimaSignature is unavailable
D/ActivityThread( 4665): Added TimaKeyStore provider
I/FeatureConfig( 4620): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/AcmsService( 4602): Inside handle Intent
D/AcmsService( 4602): App added - package name: com.example.hello
D/AcmsCore( 4602): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 4602): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 4602): Incrementing - Counter value: 3
D/AcmsCore( 4602): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 4602): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 4602): Decrementing - Counter value: 2
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
I/DBG_POLICYDM( 4036): [com.policydm.XSPPReceiver(53/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.example.hello
W/libprocessgroup( 1016): failed to open /acct/uid_10145/pid_3792/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10031/pid_3737/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3818/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10072/pid_3721/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1016): applying state to connected service
W/libprocessgroup( 1016): failed to open /acct/uid_10152/pid_3852/cgroup.procs: No such file or directory
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/SQLiteLog( 4647): (284) automatic index on shooting_modes(title_id)
W/ResourcesManager( 4665): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/Zygote  ( 4682): MountEmulatedStorage()
E/Zygote  ( 4682): v2
I/libpersona( 4682): KNOX_SDCARD checking this for 10038
I/libpersona( 4682): KNOX_SDCARD not a persona
D/Compatibility( 4665): onReceive() it will make start service
I/ActivityManager( 1016): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=4682 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
W/ResourcesManager( 4620): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/SELinux ( 4682): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 4682): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/SELinux ( 4682): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 4620): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/Zygote  ( 4698): MountEmulatedStorage()
E/Zygote  ( 4698): v2
I/libpersona( 4698): KNOX_SDCARD checking this for 10156
I/libpersona( 4698): KNOX_SDCARD not a persona
I/SELinux ( 4698): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=4698 uid=10156 gids={50156, 9997} abi=armeabi-v7a
I/SELinux ( 4698): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1016): Killing 3892:com.sec.modem.settings/1000 (adj 15): empty #31
E/SELinux ( 4698): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 4665): onHandleIntent()
D/TimaKeyStoreProvider( 4682): TimaSignature is unavailable
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 4682): Added TimaKeyStore provider
E/AffinityControl( 4518): AffinityControl: registerfunction enter
D/Compatibility( 4665): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10174, android.intent.extra.user_handle=0}]
D/Compatibility( 4665): found: 2
D/Compatibility( 4665): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 4665): skipping ResolveInfo{3bcae63d com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 4665): considering ResolveInfo{17b8ce32 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 4665): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 4665): enabling receiver ResolveInfo{152f3783 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/art     (  308): Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 607us total 34.208ms
W/ResourcesManager( 4620): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 18.299ms
D/AndroidRuntime( 4518): Calling main entry com.android.commands.am.Am
W/ResourcesManager( 4620): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 4698): TimaSignature is unavailable
D/ActivityThread( 4698): Added TimaKeyStore provider
W/ResourcesManager( 4620): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 688us total 19.763ms
D/Compatibility( 4665): enabling receiver ResolveInfo{1a56bd00 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
D/Compatibility( 4665): enabling receiver ResolveInfo{1284a939 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 4665): enabling receiver ResolveInfo{29219b7e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/Zygote  ( 4716): MountEmulatedStorage()
E/Zygote  ( 4716): v2
I/libpersona( 4716): KNOX_SDCARD checking this for 1000
I/libpersona( 4716): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=4716 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 4716): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 4716): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4716): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 4665): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ResourcesManager( 4620): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1016): mDVFSHelper.acquire()
D/FocusedStackFrame( 1016): Set to : 0
D/Launcher.HomeView( 1491): onPause
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1016): Focused application set to: xxxx
D/Launcher( 1491): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/InputDispatcher( 1016): Focus left window: 1491
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/AndroidRuntime( 4518): Shutting down VM
D/TimaKeyStoreProvider( 4716): TimaSignature is unavailable
W/ResourcesManager( 4682): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityThread( 4716): Added TimaKeyStore provider
W/ResourcesManager( 4682): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/PhoneWindow( 1016): *FMB* installDecor flags : 25362712
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3892/cgroup.procs: No such file or directory
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
I/libpersona( 4732): KNOX_SDCARD checking this for 10174
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
I/libpersona( 4732): KNOX_SDCARD not a persona
E/Zygote  ( 4732): MountEmulatedStorage()
E/Zygote  ( 4732): v2
I/SELinux ( 4732): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4732 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=10 createSurf (1x1),1 flag=404, iello
I/SELinux ( 4732): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4732): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 4620): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/TapandpayWidget:TapandpayAppWidgetProvider( 4698): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 4698): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
I/ActivityManager( 1016): Killing 3908:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
V/ActivityThread( 1491): updateVisibility : ActivityRecord{2be137f2 token=android.os.BinderProxy@1bd78be9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
I/TapandpayWidget:Utils( 4698): Clear T&P info.
D/TimaKeyStoreProvider( 4732): TimaSignature is unavailable
D/ActivityThread( 4732): Added TimaKeyStore provider
W/ResourcesManager( 4620): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4620): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/TapandpayWidget:TapandpayAppWidgetProvider( 4698): Widget is not attached.
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/Launcher.HomeView( 1491): onStop
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/ActivityThread( 1491): updateVisibility : ActivityRecord{2be137f2 token=android.os.BinderProxy@1bd78be9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1491): onTrimMemory. Level: 20
W/GalaxyFinderApplication( 4620): system/finder_cp/cpdata.xml file not found
D/PersonaManager( 1016): isKioskContainerExistOnDevice
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4750): MountEmulatedStorage()
I/libpersona( 4750): KNOX_SDCARD checking this for 10028
E/Zygote  ( 4750): v2
I/libpersona( 4750): KNOX_SDCARD not a persona
I/SELinux ( 4750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 4750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4750): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4750 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3941:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
W/ContextImpl( 4716): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
I/DBG_DM  ( 2830): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 13 sec
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
W/art     ( 4518): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/TimaKeyStoreProvider( 4750): TimaSignature is unavailable
D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1016): [SO] activate (ident=0xb8903410, enabled=0)
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/ActivityThread( 4750): Added TimaKeyStore provider
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/SensorManager( 1016): unregisterListener ::   
I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1016): [SO] changed settle time [1]
D/SensorService( 1016): [SO] setDelay [66000000]
D/SensorService( 1016): [SO] activate (ident=0xb8903410, enabled=1)
D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
I/ActivityManager( 1016): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=4767 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 4767): MountEmulatedStorage()
E/Zygote  ( 4767): v2
I/libpersona( 4767): KNOX_SDCARD checking this for 1000
I/libpersona( 4767): KNOX_SDCARD not a persona
I/SELinux ( 4767): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/WebViewFactory( 4732): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/SELinux ( 4767): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4767): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 3972:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
D/TimaKeyStoreProvider( 4767): TimaSignature is unavailable
D/ActivityThread( 4767): Added TimaKeyStore provider
I/LibraryLoader( 4732): Time to load native libraries: 2 ms (timestamps 6714-6716)
I/LibraryLoader( 4732): Expected native library version number "",actual native library version number ""
D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
W/ResourcesManager( 4767): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
V/WebViewChromiumFactoryProvider( 4732): Binding Chromium to main looper Looper (main, tid 1) {1284a939}
I/LibraryLoader( 4732): Expected native library version number "",actual native library version number ""
I/chromium( 4732): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/SensorService( 1016): [SO] 0.192 0.096 10.209
D/SensorService( 1016): [SO] [100 -> 255]
I/BrowserStartupController( 4732): Initializing chromium process, singleProcess=true
W/art     ( 4732): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4732): ApplicationContext is null in ApplicationStatus
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/chromium( 4732): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
E/Zygote  ( 4791): MountEmulatedStorage()
E/Zygote  ( 4791): v2
I/libpersona( 4791): KNOX_SDCARD checking this for 1000
I/libpersona( 4791): KNOX_SDCARD not a persona
I/SELinux ( 4791): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=4791 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 4019:com.sec.android.soagent/u0a34 (adj 15): empty #31
I/SELinux ( 4791): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4791): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/chromium( 4732): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4732): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4732): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4732): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4732): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4732): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4732): Local Branch: 
I/Adreno-EGL( 4732): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4732): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4732):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/TimaKeyStoreProvider( 4791): TimaSignature is unavailable
D/ActivityThread( 4791): Added TimaKeyStore provider
W/libprocessgroup( 1016): failed to open /acct/uid_1101/pid_3908/cgroup.procs: No such file or directory
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
W/ResourcesManager( 4791): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/libprocessgroup( 1016): failed to open /acct/uid_10157/pid_3941/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10159/pid_3972/cgroup.procs: No such file or directory
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
W/libprocessgroup( 1016): failed to open /acct/uid_10034/pid_4019/cgroup.procs: No such file or directory
D/BluetoothAdapter( 4732): 44438523: getState() :  mService = null. Returning STATE_OFF
D/Finsky  ( 4750): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/SL_DEBUG( 4682): isLoggable:: isProductShip = 1
I/SL_DEBUG( 4682): isLoggable:: SL_DEBUG_EXIST = false
I/SurfaceFlinger(  258): id=8 Removed Mauncher (5/8)
I/SurfaceFlinger(  258): id=8 Removed Mauncher (-2/8)
W/art     ( 4732): Attempt to remove local handle scope entry from IRT, ignoring
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4682): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/AwContents( 4732): onDetachedFromWindow called when already detached. Ignoring
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/PhoneWindow( 4732): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 4732): *FMB* installDecor flags : 8456448
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4682): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/SystemWebViewEngine( 4732): CordovaWebView is running on device made by: samsung
W/art     ( 4732): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4732): Attempt to remove local handle scope entry from IRT, ignoring
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
I/SA      ( 4060): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4060): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 4060): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10174 extra.user_handle.:0 ]
D/Finsky  ( 4750): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/GAv4    ( 4588): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4588):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4588):   adb logcat -s GAv4
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4863): MountEmulatedStorage()
E/Zygote  ( 4863): v2
I/libpersona( 4863): KNOX_SDCARD checking this for 10012
I/libpersona( 4863): KNOX_SDCARD not a persona
I/SELinux ( 4863): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4863): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4863): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4863 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,W/GAv4    ( 4588): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/TimaKeyStoreProvider( 4863): TimaSignature is unavailable
,D/OpenGLRenderer( 4732): Render dirty regions requested: true
,D/ActivityThread( 4863): Added TimaKeyStore provider
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,W/chromium( 4732): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/PhoneWindow( 4732): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 4732): *FMB* isFloatingMenuEnabled return false
,W/Settings( 4750): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4750): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 4863): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4863): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1016): Focus entered window: 4732
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 4732): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 4732): Initialized EGL, version 1.4
D/OpenGLRenderer( 4732): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 4732): Enabling debug mode 0
I/MultiDex( 4863): VM with version 2.1.0 has multidex support
I/MultiDex( 4863): install
I/MultiDex( 4863): VM has multidex support, MultiDex support library is disabled.
W/GAv4    ( 4588): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 4588): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,V/JNIHelp ( 4863): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager( 1016): Killing 3401:com.android.providers.calendar/u0a42 (adj 15): empty #31
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/GAv4    ( 4588): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup( 1016): failed to open /acct/uid_10042/pid_3401/cgroup.procs: No such file or directory
,I/ActivityManager( 1016): Killing 3990:com.google.android.youtube/u0a166 (adj 15): empty #31
,D/PanelView( 1173): There is/are notification(s) 
,D/Finsky  ( 4750): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4750): [1] 2.run: Finished loading 1 libraries.
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1016): Displayed Component not be shown by security: +1s74ms
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1016): mDVFSHelper.release()
I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{2ec0e2be u0 com.example.hello/.MainActivity t228} time:47490
,D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/SamsungIME( 1772): getCurrentCandidateView
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
V/AlarmManager( 1016): waitForAlarm result :4
W/ActivityThread( 4863): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4863): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@71169c0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4863): Installed default security provider GmsCore_OpenSSL
I/Timeline( 4732): Timeline: Activity_idle id: android.os.BinderProxy@c377065 time:47509
,D/Finsky  ( 4750): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 1854): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,D/ChimeraModuleLdr( 1854): Loading module APK com.google.android.play.games
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SamsungIME( 1772): Dismiss ExpandCandiate
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_10166/pid_3990/cgroup.procs: No such file or directory
,D/Finsky  ( 4750): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/DBG_DM  ( 2830): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 14 sec
,E/Watchdog( 1016): !@Sync 1
,D/SettingsProvider( 1016): name = audio_safe_volume_state
,I/SamsungIME( 1772): getDebugLevel  : 0x4f4c
,I/SurfaceFlinger(  258): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  258): id=10 Removed iello (-2/8)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigFetchService( 1854): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1854): launchTask
,D/AcmsKeyStoreHelper( 4602):  getKeyStoreForApplication Enter
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1854): Module APK com.google.android.play.games already loaded
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@11
,W/BindingManager( 4732): Cannot call determinedVisibility() - never saw a connection for the pid: 4732
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PeopleContactsSync( 1854): CP2 sync disabled
,I/AcmsKeyStoreHelper( 4602): Key Store exist
I/AcmsKeyStoreHelper( 4602): Hence loading the keystore file
,D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.vision from APK com.google.android.gms
,V/ConfigFetchTask( 1854): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WUsrCmRxY3H0u1ZoLY64NpoSN3jIK__tEulmaAY1Utn02YXfa7iqypmZytcKxLBl458NXJehGFdBkjFS-n_7jx-n_frojI2IKccmIiqygvFBUsAjozO6zNrVlReFWfM_kLHWJA28-2GlpaWPxZmtZNOM_bJiWT84frXtCxP2iM2diMsmqe-ypedKD6m6fxtC2DDL_1puZ-QcrIlkwSuE0S8_IsTXe1-KIL6JRjHYEJs2lw7IM
,I/GoogleURLConnFactory( 1854): Using platform SSLCertificateSocketFactory
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Icing   ( 1854): Storage manager: low false usage 2.00MB avail 7.89GB capacity 9.93GB
,D/Vision  ( 1854): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 1854): Failed to find package metadata for com.example.hello
,D/Vision  ( 1854): No vision deps
,I/chromium( 4732): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,W/Icing   ( 1854): Received bad json for section weights override -- ignoring.
,I/SamsungIME( 1772): getDebugLevel  : 0x4f4c
,W/Icing   ( 1854): Received bad json for corpus context scoring override -- ignoring.
,W/Icing   ( 1854): Received bad json for section weights override -- ignoring.
,W/Icing   ( 1854): Received bad json for corpus context scoring override -- ignoring.
,I/SamsungIME( 1772): KeybaordView init() : load resources
,D/AcmsKeyStoreHelper( 4602):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 4602): getKeyStoreForApplication success 
D/AcmsCore( 4602): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 4602): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 4602): Decrementing - Counter value: 1
D/AcmsCore( 4602): AcmsCore: ACMS_APP_INSTALLED
,I/ActivityManager( 1016): Killing 4133:com.google.android.gm/u0a101 (adj 15): empty #31
,I/SamsungIME( 1772): getCurrentKeyboard
I/SamsungIME( 1772): getTextKeyboard
,D/JsMessageQueue( 4732): Set native->JS mode to OnlineEventsBridgeMode
,D/SamsungIME( 1772): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/System.out( 1854): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1854): (HTTPLog)-Static: isSBSettingEnabled false
E/AndroidProtocolHandler( 4732): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/System.out( 1854): (HTTPLog)-Static: isShipBuild true,
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
I/System.out( 1854): (HTTPLog)-Thread-229-615176284: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
I/System.out( 1854): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): uids 10012,
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10012
,E/Zygote  ( 4919): MountEmulatedStorage(),
E/Zygote  ( 4919): v2
I/libpersona( 4919): KNOX_SDCARD checking this for 10120
I/SELinux ( 4919): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 4919): KNOX_SDCARD not a persona,
,I/ActivityManager( 1016): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4919 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1016): Killing 4188:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,I/SELinux ( 4919): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4919): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ConfigFetchTask( 1854): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname,
,I/ConfigFetchService( 1854): fetch service done; releasing wakelock
,W/ContextImpl( 4588): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
,D/AcmsCore( 4602): This is NOT a valid MirrorLink app
D/AcmsCore( 4602): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 4602): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 4602): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 4602): Counter value is 0: Stopping ACMS service
,W/ResourcesManager( 4588): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4588): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/AlarmManager( 1016): waitForAlarm result :8
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/AcmsServiceMonitor( 4602): getSvcCounter - Counter value: 0
D/AcmsService( 4602): Enter onDestroy
I/AcmsService( 4602): cleanUp(): inside service clean up
D/AcmsCore( 4602): AcmsCore: inside DeInit
D/AcmsCore( 4602): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 4602): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 4602): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 4602): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 4602): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 4602): getSvcCounter - Counter value: 0
D/AcmsService( 4602): killing acms process
I/Process ( 4602): Sending signal. PID: 4602 SIG: 9
I/ConfigFetchService( 1854): stopping self
,D/TimaKeyStoreProvider( 4919): TimaSignature is unavailable
,D/ActivityThread( 4919): Added TimaKeyStore provider
,I/ActivityManager( 1016): Process ACMS.Process (pid 4602)(adj 0) has died(43,1118)
,V/Finsky  ( 4750): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/JNIHelp ( 4588): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/BaseAppContext( 1854): Using Auth Proxy for data requests.
,W/BaseAppContext( 1854): Using Auth Proxy for data requests.
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 4750): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/ResourcesManager( 4919): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0,
,V/GLSActivity( 1665): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_10092/pid_4188/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10101/pid_4133/cgroup.procs: No such file or directory
,D/jxcore_app_log( 4732): JniHelper::setJavaVM(0xb82ca450), pthread_self() = -1199628912
,D/JX-Cordova( 4732): jxcore cordova android initializing
,I/GLSUser ( 1665): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1665): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1665): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1665): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1665): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/art     ( 4588): Suspending all threads took: 25.643ms
,W/ActivityThread( 4588): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4588): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@131c3749: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4588): Installed default security provider GmsCore_OpenSSL
,W/jxcore-log( 4732): Initializing JXcore engine
W/jxcore-log( 4732): JXcore engine is ready
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{9ff4f5 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,W/jxcore-log( 4732): Starting JXcore engine
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1665): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 33042(1893KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/40MB, paused 2.406ms total 247.030ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1665): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/audit   ( 1852): type=1400 msg=audit(1447782139.618:203): avc:  denied  { ioctl } for  pid=4732 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1852):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1852): type=1300 msg=audit(1447782139.618:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=beb44d58 items=0 ppid=308 ppcomm=main pid=4732 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1852): type=1320 msg=audit(1447782139.618:203): 
,W/BaseAppContext( 1854): Using Auth Proxy for data requests.
,W/BaseAppContext( 1854): Using Auth Proxy for data requests.
,I/GLSUser ( 1665): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1665): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1665): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1665): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1665): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1854): Using Auth Proxy for data requests.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 4750): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/BaseAppContext( 1854): Using Auth Proxy for data requests.
,I/DBG_DM  ( 2830): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 15 sec
,W/jxcore-log( 4732): Platform android
W/jxcore-log( 4732): 
,W/jxcore-log( 4732): Process ARCH arm
W/jxcore-log( 4732): 
,I/jxcore-log( 4732): JXcore Cordova bridge is ready!
I/jxcore-log( 4732): 
,W/jxcore-log( 4732): JXcore engine is started
,E/jxcore-log( 4732): >> samsung-SM-A500FU
E/jxcore-log( 4732): 
,I/jxcore-log( 4732): Total memory 1983787008
I/jxcore-log( 4732): 
,I/jxcore-log( 4732): Free memory 31481856
I/jxcore-log( 4732): 
I/jxcore-log( 4732): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4732): 
I/jxcore-log( 4732): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4732): 
,I/jxcore-log( 4732): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 4732): 
,I/jxcore-log( 4732): Size 720 1280
I/jxcore-log( 4732): 
,I/jxcore-log( 4732): Screen Brightness 5
I/jxcore-log( 4732): 
,E/jxcore-log( 4732): Dummy Error Log.
E/jxcore-log( 4732): 
,E/SMD     (  289): DCD OFF
,I/Icing   ( 1854): updateResources: need to parse f{com.google.android.gms}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1854): Module APK com.google.android.play.games already loaded
,I/Icing   ( 1854): Internal init done: storage state 0
,I/Icing   ( 1854): Post-init done,
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4954): MountEmulatedStorage()
,E/Zygote  ( 4954): v2
I/libpersona( 4954): KNOX_SDCARD checking this for 10010
I/libpersona( 4954): KNOX_SDCARD not a persona
,I/SELinux ( 4954): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 4954): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4954): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=4954 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 4227): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/jxcore-log( 4732): getBuffer is called!!!!
I/jxcore-log( 4732): 
,V/GLSActivity( 1665): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 4954): TimaSignature is unavailable
,D/ActivityThread( 4954): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1665): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1665): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1665): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1665): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1665): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 4750): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4750): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4750): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4750): [1] DailyHygiene.reschedule: Scheduling new run in 772 minutes (failures=5)
,I/splitIntent( 1016): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/UpdateIcingCorporaServi( 4227): UpdateCorporaTask done [took 188 ms] updated apps [took 188 ms] 
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  279): uids 10012
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10012
,D/DeviceConnectionService( 1691): client connected with version: 7571000
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Killing 3605:com.google.android.talk/u0a104 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 4167:com.dropbox.android/u0a92 (adj 15): empty #32
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4971): MountEmulatedStorage()
,E/Zygote  ( 4971): v2
I/libpersona( 4971): KNOX_SDCARD checking this for 10165
I/libpersona( 4971): KNOX_SDCARD not a persona
,I/SELinux ( 4971): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4971): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4971): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.app.wluc for broadcast com.sec.android.app.wluc/.PolicyManagerBroadcastReceiver: pid=4971 uid=10165 gids={50165, 9997} abi=armeabi-v7a
,I/DBG_DM  ( 2830): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 16 sec
,D/TimaKeyStoreProvider( 4971): TimaSignature is unavailable
,D/ActivityThread( 4971): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PolicyManagerBroadcastReceiver( 4971): onReceive: action = com.sec.intent.ACTION.SSRM_HGL_UPDATE
,I/PolicyManagerBroadcastReceiver( 4971): onReceive: width = 720, height = 1280
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/AssistantMenuSettingSearch( 4716): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
,D/AssistantMenuSettingSearch( 4716): Make Setting DB
,W/libprocessgroup( 1016): failed to open /acct/uid_10104/pid_3605/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10092/pid_4167/cgroup.procs: No such file or directory
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4988): MountEmulatedStorage()
E/Zygote  ( 4988): v2
I/libpersona( 4988): KNOX_SDCARD checking this for 10150
I/libpersona( 4988): KNOX_SDCARD not a persona
,I/SELinux ( 4988): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 4988): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4988): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=4988 uid=10150 gids={50150, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 4988): TimaSignature is unavailable
,D/ActivityThread( 4988): Added TimaKeyStore provider
,W/ContextImpl( 4716): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:158 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:38 
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.phone
,I/ActivityManager( 1016): Killing 4448:com.sec.smartcard.manager/u0a153 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 4337:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #32
,I/ActivityManager( 1016): Killing 4317:com.wsomacp/u0a25 (adj 15): empty #33
,I/SettingSearchManagerReceiver( 1470): onReceive : com.samsung.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
I/SettingSearchManagerReceiver( 1470): addSearchInfoDB
,I/FaceInterface( 4427): startFaceScan() : going on
,D/FaceInterface( 4427): startFaceScan() is called.
,D/ContentApp( 1221): startScan() is called.
,D/FaceValue( 1221): mSleepTime: 800
,D/FaceValue( 1221): mMaxThreadNum: 2
,W/FaceValue( 1221): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,D/ContentApp( 1221): startScan() is end.
,D/ContentApp( 1221): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1221): isNeedToRestore : start
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SettingSearchManagerReceiver( 1470): endInsert
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.app.popupuireceiver
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4337/cgroup.procs: No such file or directory
E/Zygote  ( 5005): MountEmulatedStorage()
E/Zygote  ( 5005): v2
I/libpersona( 5005): KNOX_SDCARD checking this for 1000
I/libpersona( 5005): KNOX_SDCARD not a persona
,I/SELinux ( 5005): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5005): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,I/ActivityManager( 1016): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5005 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 5005): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1016): failed to open /acct/uid_10025/pid_4317/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10153/pid_4448/cgroup.procs: No such file or directory
,D/SSRM:n  ( 1016): SIOP:: AP = 410,
,I/art     (  308): Explicit concurrent mark sweep GC freed 8764(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 653us total 20.122ms,
,D/TimaKeyStoreProvider( 5005): TimaSignature is unavailable,
D/ActivityThread( 5005): Added TimaKeyStore provider,
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 22.206ms
,D/PopupuiReceiver( 5005): onReceive() getAction : com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{36e58141 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,D/SecContentProvider2( 1016): uri = -1 selection = getSealedState
,D/SecContentProvider2( 1016): mCursor = null
I/PopupuiReceiver_KNOX( 5005): getSealedState : true
,D/SecContentProvider2( 1016): uri = 15 selection = getSealedHideNotificationMessages
D/SecContentProvider2( 1016): mCursor = null
,I/PopupuiReceiver_KNOX( 5005): getSealedHideNotificationMessages : 1
,D/SecContentProvider2( 1016): uri = 15 selection = getCheckCoverPopupState
D/SecContentProvider2( 1016): mCursor = null
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 17.011ms
I/PopupuiReceiver_KNOX( 5005): getCheckCoverPopupState : true
D/PopupuiReceiver( 5005): Action cable connected ! on - 
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.samsung.android.app.powersharing
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5021): MountEmulatedStorage(),
E/Zygote  ( 5021): v2
I/libpersona( 5021): KNOX_SDCARD checking this for 10122
,I/libpersona( 5021): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.samsung.android.app.powersharing for broadcast com.samsung.android.app.powersharing/.service.BatteryReceiver: pid=5021 uid=10122 gids={50122, 9997} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 4408:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
I/SELinux ( 5021): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5021): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 5021): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5021): TimaSignature is unavailable
,D/ActivityThread( 5021): Added TimaKeyStore provider
,I/FaceInterface( 4427): startFaceScan() : going on
,D/FaceInterface( 4427): startFaceScan() is called.
,I/PowerSharing.BatteryReceiver( 5021): onReceive : com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED
,D/ContentApp( 1221): startScan() is called.
,D/ContentApp( 1221): startScan() is end.
,D/ContentApp( 1221): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1221): isNeedToRestore : start
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1665): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_10040/pid_4408/cgroup.procs: No such file or directory
D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Kids    ( 1854): [KidAccountFixer] No network connection
,I/ActivityManager( 1016): Killing 4357:com.google.android.music:main/u0a111 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.download.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SafeBrowsingUpdateIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1665): Explicit concurrent mark sweep GC freed 13782(729KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/17MB, paused 1.100ms total 54.373ms
,W/libprocessgroup( 1016): failed to open /acct/uid_10111/pid_4357/cgroup.procs: No such file or directory
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5043): MountEmulatedStorage()
I/libpersona( 5043): KNOX_SDCARD checking this for 10134
E/Zygote  ( 5043): v2
I/libpersona( 5043): KNOX_SDCARD not a persona
,I/SELinux ( 5043): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5043 uid=10134 gids={50134, 9997} abi=armeabi-v7a
I/SELinux ( 5043): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5043): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5043): TimaSignature is unavailable
,D/ActivityThread( 5043): Added TimaKeyStore provider
,W/ResourcesManager( 5043): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5043): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5058): MountEmulatedStorage()
,E/Zygote  ( 5058): v2
I/libpersona( 5058): KNOX_SDCARD checking this for 10135
I/libpersona( 5058): KNOX_SDCARD not a persona
,I/SELinux ( 5058): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5058 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux ( 5058): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1016): Killing 4427:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
E/SELinux ( 5058): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5058): TimaSignature is unavailable
,D/ActivityThread( 5058): Added TimaKeyStore provider
,W/ResourcesManager( 5058): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5058): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5058): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/daemonapp( 1279): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/libprocessgroup( 1016): failed to open /acct/uid_10044/pid_4427/cgroup.procs: No such file or directory
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SPPClientService( 3957): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=5079 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 5079): MountEmulatedStorage(),
I/libpersona( 5079): KNOX_SDCARD checking this for 10035
E/Zygote  ( 5079): v2
I/libpersona( 5079): KNOX_SDCARD not a persona
I/SELinux ( 5079): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Killing 4502:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,I/SELinux ( 5079): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5079): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 2830): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 17 sec
,D/TimaKeyStoreProvider( 5079): TimaSignature is unavailable
,D/ActivityThread( 5079): Added TimaKeyStore provider
,E/SPPClientService( 5079): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5079): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 5079): PushLog.txt file is not deleted.
,D/SPPClientService( 5079): PushLog.txt file is not deleted.
,D/SPPClientService( 5079): ============PushLog. stop!
,W/libprocessgroup( 1016): failed to open /acct/uid_10100/pid_4502/cgroup.procs: No such file or directory
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5099): MountEmulatedStorage(),
E/Zygote  ( 5099): v2
I/libpersona( 5099): KNOX_SDCARD checking this for 10033
I/libpersona( 5099): KNOX_SDCARD not a persona
I/SELinux ( 5099): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5099): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1016): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=5099 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
I/ActivityManager( 1016): Killing 3433:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,E/SELinux ( 5099): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5099): TimaSignature is unavailable
,D/ActivityThread( 5099): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 4287:com.android.mms/u0a46 (adj 15): empty #31
,W/ResourcesManager( 5099): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5099): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 5099): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,D/CountryDetector( 1016): No listener is left
,W/ResourcesManager( 5099): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5099): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5099): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 5099): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_10015/pid_3433/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10046/pid_4287/cgroup.procs: No such file or directory
,D/PowerManagerService( 1016): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1016): Nap time (uid 1000)...
,D/PowerManagerService( 1016): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
,I/PowerManagerService( 1016): !@[ps] Screen__Off - 0 :  dream(timeout) (2)
I/PowerManagerService( 1016): Going to sleep due to screen timeout (uid 1000)...
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1016): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService( 1016): [PWL] sb acquire: PowerManagerService.Broadcasts
,V/WindowOrientationListener( 1016): WindowOrientationListener disabled
D/SensorService( 1016): [SO] activate (ident=0xb8903410, enabled=0)
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/PowerManagerService( 1016): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService( 1016): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
,D/PowerManagerService( 1016): handleSandman : startDream(true)
,E/PowerManagerService( 1016): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1016): Sleeping (uid 1000)...
D/PowerManagerService( 1016): [s] UserActivityState : 4 -> 0
,I/SurfaceFlinger(  258): id=12 createSurf (720x1280),-1 flag=20004, DolorFade
,D/SensorManager( 1016): unregisterListener ::   
,D/KeyguardViewMediator( 1173): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1173): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1173): changeWallpaperByScreenOff()
,D/PowerManagerService( 1016): Excessive delay in ColorFade : createSurface: 15ms
,I/Adreno-EGL( 1016): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1016): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1016): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1016): Local Branch: 
I/Adreno-EGL( 1016): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1016): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1016):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/KeyguardViewMediator( 1173): notifyScreenOffLocked
,D/KeyguardViewMediator( 1173): timeout : 5000
,D/PowerManagerService( 1016): Excessive delay in ColorFade : createEglContext: 20ms
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (197 us)
,D/PowerManagerService( 1016): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 21ms
,D/KeyguardViewMediator( 1173): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 1173): handleNotifyScreenOff
,D/VolumePanel( 1173): onScreenTurnedOff(),
D/VolumePanel( 1173): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,V/ActivityThread( 4732): updateVisibility : ActivityRecord{2192300 token=android.os.BinderProxy@c377065 {com.example.hello/com.example.hello.MainActivity}} show : true
,D/VolumePanel( 1173): mCoverBroadcastReceiver: Screen OFF end
,D/SecKeyguardClockSingleView( 1173): onScreenTurnedOff
,D/PowerManagerService( 1016): Excessive delay in ColorFade : initGLShaders: 44ms
E/SmartFaceService( 1016): onReceive: android.intent.action.SCREEN_ON
,W/System.err( 1016): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
D/PowerManagerService( 1016): Excessive delay in ColorFade prepare: 113ms
,W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1016): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1016): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1016): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SmartFaceService( 1016): fail to set sysfs 1
W/System.err( 1016): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1016): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1016): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1016): 	... 10 more
,D/DisplayPowerController( 1016): ColorFade: onAnimationStart
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
,D/InputMethodManagerService( 1016): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/PanelView( 1173): There is/are notification(s) 
,D/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_SCREEN_ON
,I/WifiNative-HAL( 1016): startHal
,E/wifi    ( 1016): getStaticLongField sWifiHalHandle 0x9cfa57fc
I/WifiNative-HAL( 1016): Could not start hal
,D/NotificationService( 1016): ACTION_SCREEN_ON
D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
,D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/MotionRecognitionService( 1016):  handler : SCREEN_ON end
,D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=on
V/voice   (  284): voice_set_parameters: enter: screen_state=on
V/voice   (  284): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  284): adev_set_parameters: exit
,D/IpRemoteDisplayController( 1016): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 1016): Bridge Server is not available
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1016): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1016): MSG_ACTION_SCREEN_ON called
,D/PanelView( 1173): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1454): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1454): call the applyRouting
,D/accuweather( 1611): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1611): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1611): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1611): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_ON
,I/SamsungIME( 1772): getNextShiftState() cursorCapsMode : 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{26974af7 u0 com.sec.bcservice/.BroadcastService}
,D/LightsService( 1016): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 1016) 
,D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
D/BatteryService( 1016): turn on LED for charging
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,E/lights  ( 1016): write_int failed to open -1
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SmartFaceService( 1016): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1016): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1016): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1016): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1016): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SmartFaceService( 1016): fail to set sysfs 0
W/System.err( 1016): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1016): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1016): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1016): 	... 10 more
,D/SSRM:n  ( 1016): SIOP:: AP = 410
,D/PanelView( 1173): There is/are notification(s) 
,D/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 1016):  handler : SCREEN_OFF end 
,I/WifiNative-HAL( 1016): startHal
E/wifi    ( 1016): getStaticLongField sWifiHalHandle 0x9cfa57fc
I/WifiNative-HAL( 1016): Could not start hal
,D/NotificationService( 1016): ACTION_SCREEN_OFF
D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
,D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=4) set Off
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=off
,V/voice   (  284): voice_set_parameters: enter: screen_state=off
V/voice   (  284): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
,V/audio_hw_primary(  284): adev_set_parameters: exit,
,D/IpRemoteDisplayController( 1016): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 1016): Bridge Server is not available
,I/ActivityManager( 1016): Killing 4538:com.sec.pcw.device/1000 (adj 15): empty #31
,D/DisplayPowerState( 1016): !@ ColorFade entry
D/DisplayPowerController( 1016): ColorFade: onAnimationEnd
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 0 -> 0
D/lights  ( 1016): lcd : 0 +
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/lights  ( 1016): lcd : 0 -
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 0 -> 0
D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/PowerManagerService( 1016): [PWL] sb release: PowerManagerService.Display
,D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event3/device/enabled: 0,
D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/DisplayManagerService( 1016): !@display_state: ON -> OFF
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/DisplayManagerService( 1016): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
I/QCOM PowerHAL( 1016): Got set_interactive hint
V/ActivityManager( 1016): Display changed displayId=0
D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb7aaa690
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
,E/Zygote  ( 5137): MountEmulatedStorage()
W/DisplayManagerService( 1016): Failed to notify process 4538 that displays changed, assuming it died.
W/DisplayManagerService( 1016): android.os.TransactionTooLargeException
W/DisplayManagerService( 1016): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService( 1016): 	at android.os.BinderProxy.transact(Binder.java:511)
W/DisplayManagerService( 1016): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService( 1016): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1372)
W/DisplayManagerService( 1016): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1170)
W/DisplayManagerService( 1016): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:146)
W/DisplayManagerService( 1016): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1305)
W/DisplayManagerService( 1016): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService( 1016): 	at android.os.Looper.loop(Looper.java:145)
W/DisplayManagerService( 1016): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService( 1016): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
E/Zygote  ( 5137): v2
I/libpersona( 5137): KNOX_SDCARD checking this for 10101
I/libpersona( 5137): KNOX_SDCARD not a persona
,I/SELinux ( 5137): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
I/ActivityManager( 1016): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5137 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5137): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5137): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 1173): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/TimaKeyStoreProvider( 5137): TimaSignature is unavailable
,D/ActivityThread( 5137): Added TimaKeyStore provider
,W/ContextImpl( 3923): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,I/DBG_DM  ( 2830): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 2830): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,E/DBG_DM  ( 2830): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,I/DBG_DM  ( 2830): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4538/cgroup.procs: No such file or directory
,V/EmergencyMode( 1430): [EmergencyStateReceiver] binteractive [false] why[3]
,D/PersonaManagerService( 1016): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1016): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1454): call the applyRouting
,D/accuweather( 1611): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1611): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1611): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_OFF
D/SViewCoverView( 1173): Move to page : HomePage
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/LibSecureUISvc( 1878): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/PowerManagerService( 1016): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:n  ( 1016): SIOP:: AP = 410
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 33173(1916KB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 26MB/40MB, paused 2.272ms total 154.932ms
,I/Process ( 3923): Sending signal. PID: 3923 SIG: 9
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl( 1016): Excessive delay in setPowerMode(): 260ms
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
D/PowerManagerService( 1016): Excessive delay in !@display_state: OFF: 262ms
I/libsuspend( 1016): !@autosuspend_wakeup_count_enable
I/libsuspend( 1016): !@autosuspend_wakeup_count_enable done
,D/PowerManagerService( 1016): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 270ms
I/PowerManagerService( 1016): [PWL] Off : 0s ago
I/PowerManagerService( 1016): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1016): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1016, ws=WorkSource{10042}) (elapsedTime=17805)
I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1854, ws=null) (elapsedTime=16654)
,I/ActivityManager( 1016): Process com.sec.android.app.sysscope (pid 3923)(adj 0) has died(73,1116)
,I/DBG_DM  ( 2830): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 18 sec
,I/DBG_DM  ( 2830): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 2830): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,I/Gmail   ( 5137): getAccountsCursor
,W/GAV2    ( 5137): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,E/DBG_DM  ( 2830): [IlIIlIIlIllllIlllIII(226/llIIIIlllllIIllIIllI)] Network Status is not ready. DM Not Initialized
,I/DBG_DM  ( 2830): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,V/GLSActivity( 1665): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 5137): Observing account changes for notifications
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5137): Error finding the version of the Email provider.....
E/Gmail   ( 5137): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5137): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 5137): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5137): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5137): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5137): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5137): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 5137): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 5137): We do not support migrating this version of the Email provider.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/Gmail   ( 5137): getAccountsCursor
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1665): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1665): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 5137): (283) recovered 108 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,D/GCM     ( 1665): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1665): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/GmsCoreStatsServiceLauncher( 1854): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/File    ( 5137): fail readDirectory() errno=2
,D/WearableService( 4262): callingUid 10012, callindPid: 4262
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 5137): notifyAccountChanged
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 5137): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,E/MDM     ( 1691): [174] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/Gmail   ( 5137): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1854): Restart initialization of location
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 5137): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5137): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 5137): getAccountsCursor
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5180): MountEmulatedStorage()
I/libpersona( 5180): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5180): v2
I/libpersona( 5180): KNOX_SDCARD not a persona
,I/SELinux ( 5180): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5180 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5180): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
E/SELinux ( 5180): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1665): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 5180): TimaSignature is unavailable
,D/ActivityThread( 5180): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/MTPRx   ( 5180): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1016): mCursor = null
,V/MTPRx   ( 5180): sealedState: false
V/MTPRx   ( 5180): sealedUsbMassStorageState: false
E/MTPRx   ( 5180): check value of boot_completed is1
E/MTPRx   ( 5180): check booting is completed_sys.boot_completed
,E/MTPRx   ( 5180): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 5180): Status for mount/Unmount :removed
E/MTPRx   ( 5180): SDcard is not available
,W/MTPRx   ( 5180): value of connected istrue
W/MTPRx   ( 5180): value of configured istrue
W/MTPRx   ( 5180): value of mtpEnabled istrue
W/MTPRx   ( 5180): value of ptpEnabled isfalse
,E/MTPRx   ( 5180): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 5180): mFirstTime: false
,D/        ( 5180): MTP: reading debug level property
,E/MTPJNIInterface( 5180): Getting CryptionKey from JAVA
E/MTPRx   ( 5180): currentUserId is 0
,E/MTPRx   ( 5180): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 5180): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 5180): is_Privatemode is NOT 1
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,D/SecContentProvider( 1016): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 5180): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1016): name = mtp_running_status
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,E/MTPRx   ( 5180): else part ... so first time!!!
E/MTPPlaObsrvr( 5180): inside setContext()
E/MTPPlaObsrvr( 5180):  inside createplafiles
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 5180): playlist count is0
E/MTPPlaObsrvr( 5180):  inside try branch createplafiles
,E/MTPPlaObsrvr( 5180):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 5180): Inside registerContentObserver
,E/MtpAdbObserver( 5180): inside setContext()
E/MtpAdbObserver( 5180): Inside registerContentObserver
W/Settings( 5180): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,I/NotifUtils( 5137): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,V/MtpMediaDBManager( 5180): inside deleteAllDB
,D/SettingsProvider( 1016): name = mtp_running_status
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,E/MtpService( 5180): onCreate.
,E/MtpService( 5180): < MTP > Registering BroadCast receiver :::::
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,E/MtpService( 5180): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/SMD     (  289): DCD OFF
E/MtpService( 5180): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,V/MtpMediaDBManager( 5180): inside Thread updateDB
,D/SSRM:a  ( 1016): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1016): SettingsAirViewInfo:: 000000000
,E/MtpService( 5180): onStartCommand.
,W/MTPRx   ( 5180): calling native method
E/MTPJNIInterface( 5180): < MTP > Registering BroadCast receiver :::::
,E/MtpMediaDBManager( 5180): count : 27
,E/MTPJNIInterface( 5180): < MTP > Registering BroadCast receiver :::::::
,E/MtpService( 5180): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 5180): noti = 10
E/MtpService( 5180): onStartCommand.
,D/MtpService( 1221): updating state; isCurrentUser=true, mMtpLocked=false
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/MTPRx   ( 5180): calling native method
E/MTPRx   ( 5180): Checking the driver time out
E/MTPJNIInterface( 5180): noti = 2
,D/        ( 5180): deleting sockets before message queue initialization
,D/        ( 5180): event handler thread is created, so set the flag
,E/MTPRx   ( 5180): called native method
E/MTPJNIInterface( 5180): setting Media scanner status0
E/MTPJNIInterface( 5180): After setting Media scanner status0
W/MTPRx   ( 5180): notification from stack 1
,E/        ( 5180): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
,E/MTPJNIInterface( 5180): Getting media scanner status0
,E/MTPJNIInterface( 5180): DeviceName is Thali Test (Galaxy A5)
,E/Zygote  ( 5203): MountEmulatedStorage()
,I/libpersona( 5203): KNOX_SDCARD checking this for 1000,
E/Zygote  ( 5203): v2
I/libpersona( 5203): KNOX_SDCARD not a persona
I/SELinux ( 5203): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=5203 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/SELinux ( 5203): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5203): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/MtpService( 5180): handleMessage. msg= { when=-32ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,W/MtpMediaDBManager( 5180): sending db update complete noti to stack
E/MTPJNIInterface( 5180): noti = 29
,E/MTPJNIInterface( 5180): Status for mount/Unmount :removed
,E/MTPJNIInterface( 5180): SDcard is not available
,D/TimaKeyStoreProvider( 5203): TimaSignature is unavailable
,D/ActivityThread( 5203): Added TimaKeyStore provider
I/NotifUtils( 5137): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,I/Gmail   ( 5137): getAccountsCursor
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,E/        ( 5180): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,V/GLSActivity( 1665): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MTPJNIInterface( 5180): Status for mount/Unmount :removed
E/MTPJNIInterface( 5180): SDcard is not available
E/SQLiteLog( 5180): (21) API call with NULL database connection pointer
E/SQLiteLog( 5180): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 5180): (21) API call with NULL database connection pointer
E/SQLiteLog( 5180): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5180): (21) API call with NULL database connection pointer
E/SQLiteLog( 5180): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5180): (21) API call with NULL database connection pointer
E/SQLiteLog( 5180): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 5180): notification from stack 2
,D/        ( 5180): [mtp_init_device] Library open with 32 bits.
D/        ( 5180): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 5180): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 5180): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 5180):  [sua_support_present:1287] returning false 
D/        ( 5180): *****Starting mtp_io()
,D/        ( 5180): [mtp_start_io] source_thread Creation 
,D/        ( 5180): [mtp_start_io] sink_thread Creation 
D/        ( 5180): [mtp_start_io:376] sink thread created so set th_sink
,W/MTPRx   ( 5180): notification from stack 3
,D/TMNetworkReceiver( 5203): TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
D/TMNetworkReceiver( 5203): TMNetworkReceiver.onReceive() Enter
,D/TMNetworkReceiver( 5203): MirrorLink feauture level: using UEvent
,I/ActivityManager( 1016): Killing 4552:com.samsung.helphub/1000 (adj 15): empty #31
,D/MediaScannerReceiver( 1221): action: com.samsung.intent.action.MTP_FILE_SCAN
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5224): MountEmulatedStorage(),
E/Zygote  ( 5224): v2
I/libpersona( 5224): KNOX_SDCARD checking this for 10042
I/libpersona( 5224): KNOX_SDCARD not a persona
I/SELinux ( 5224): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5224): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 5224): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5224 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5224): TimaSignature is unavailable
,D/ActivityThread( 5224): Added TimaKeyStore provider
,W/ResourcesManager( 5224): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5224): CalendarProvider2.onCreate() called
,D/MediaScannerService( 1221): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4552/cgroup.procs: No such file or directory
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter finished
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/MediaProvider( 1221): savePlaylistTableInBulkDeleter started
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter finished
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
D/MediaScanner( 1221): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,V/MediaScanner( 1221): processDirectory :  /storage/emulated/0
,E/SQLiteLog( 5224): (284) automatic index on view_events(_id),
D/MediaScanner( 1221): Skipping:
D/MediaScanner( 1221): 7klwibgf7fvntblfd7(75ebcf7
,D/MediaScanner( 1221): Skipping:
,D/MediaScanner( 1221): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,E/Zygote  ( 5244): MountEmulatedStorage()
E/Zygote  ( 5244): v2
I/libpersona( 5244): KNOX_SDCARD checking this for 10104
I/libpersona( 5244): KNOX_SDCARD not a persona
,I/SELinux ( 5244): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5244): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5244): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=5244 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/MediaScanner( 1221): processDirectory :  /storage/extSdCard
W/MediaScanner( 1221): Error opening directory, reason : Permission denied.
W/MediaScanner( 1221): 7klwibgf7fxlKdCbid7
,V/MediaScanner( 1221):  prescan time: 46ms (DB items: 27)
V/MediaScanner( 1221):     scan time: 25ms (Caching mode: true), (makeEntry time: 17ms ~68%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1221): postscan time: 2ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1221):    total time: 73ms
V/MediaScanner( 1221): checked files: 10  directories : 17  (I: 0, U: 0)
,D/MediaScannerService( 1221): !@done scanning volume external
,E/MTPJNIInterface( 5180): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,D/CalendarAlarmManager( 5224): sys current time:1447782143426
,D/CalendarAlarmManager( 5224): reminder amount:0
,D/TimaKeyStoreProvider( 5244): TimaSignature is unavailable
,D/ActivityThread( 5244): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ResourcesManager( 5244): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/iu.UploadsManager( 1854): End new media; added: 0, uploading: 0, time: 110 ms
,I/Babel_SMS( 5244): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5244): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5244): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel_SMS( 5244): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5244): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 5244): MmsConfig.loadFromResources
,E/Babel_SMS( 5244): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5244): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  284): getCameraInfo: X
,W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  284): getCameraInfo: X
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/PolicyManagerBroadcastReceiver( 4971): This process will be killed soon.
,I/Process ( 4971): Sending signal. PID: 4971 SIG: 9
,W/Settings( 5244): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5244): startup - clean
,I/Babel   ( 5244): deleted: false for 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/splitIntent( 1016): intent=android.intent.action.PACKAGE_CHANGED will be not split. because same process=com.google.android.googlequicksearchbox:search is in other queue. index=1
,I/splitIntent( 1016): base  index=1, name=com.google.android.googlequicksearchbox com.google.android.search.core.GmsPackageWatcher
I/splitIntent( 1016): other index=14, name=com.google.android.googlequicksearchbox com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_CHANGED !! do not split it!!
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 5244): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5244): Unsupported mime audio/evrc
,E/Zygote  ( 5269): MountEmulatedStorage()
,E/Zygote  ( 5269): v2
I/libpersona( 5269): KNOX_SDCARD checking this for 10044
I/libpersona( 5269): KNOX_SDCARD not a persona
I/SELinux ( 5269): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=5269 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
,I/SELinux ( 5269): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
W/AudioCapabilities( 5244): Unsupported mime audio/qcelp
E/SELinux ( 5269): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Process com.sec.android.app.wluc (pid 4971)(adj 15) has died(55,1117),
,W/AudioCapabilities( 5244): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5244): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5244): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5244): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5244): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5244): Unsupported mime audio/evrc
,I/art     (  308): Explicit concurrent mark sweep GC freed 8701(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 661us total 24.996ms
,D/TimaKeyStoreProvider( 5269): TimaSignature is unavailable
,D/ActivityThread( 5269): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 627us total 17.191ms
,W/ResourcesManager( 5269): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5269): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5269): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5269): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5269): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 5269): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5269): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5269): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/VideoCapabilities( 5244): Unsupported mime video/wvc1
,W/VideoCapabilities( 5244): Unsupported mime video/x-ms-wmv
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 16.634ms
,W/VideoCapabilities( 5244): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5244): Unsupported mime video/wvc1
,W/VideoCapabilities( 5244): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5244): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5244): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5244): Unsupported mime video/mp43
,W/VideoCapabilities( 5244): Unsupported mime video/sorenson
,W/VideoCapabilities( 5244): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5244): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5244): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5244): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5244): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5244): Unrecognized profile 2130706433 for video/avc
,D/NearbySource( 5269): Nearby Source Create!
,D/NearbyContext( 5269): Nearby Context Create!
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.requestwriter.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.requestwriter.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/vclib   ( 5244): onServiceConnected
,W/Babel   ( 5244): Attempted to change video mute state without an active call.
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5269): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 5269): Samsung link source created
,W/ResourcesManager( 5244): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5244): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/ContactProvider( 5269): getAllContactInfoList Start
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/JNIHelp ( 5244): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/PackagesMonitor( 5269): PackagesMonitor onReceive :com.google.android.gms
,D/ContactProvider( 5269): getAllContactInfoList End
,I/syncContacts( 5269): thread: 888, sync time = 41
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5291): MountEmulatedStorage()
E/Zygote  ( 5291): v2
I/libpersona( 5291): KNOX_SDCARD checking this for 10069
I/SELinux ( 5291): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 5291): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5291 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5291): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5291): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityThread( 5244): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5244): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3f303b7d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5244): Installed default security provider GmsCore_OpenSSL
,I/ConfigService( 1665): onDestroy,
,D/TimaKeyStoreProvider( 5291): TimaSignature is unavailable
,D/ActivityThread( 5291): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/FileShare-Server( 5291): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5244): connection state changed from UNKNOWN to DISCONNECTED
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5310): MountEmulatedStorage(),
E/Zygote  ( 5310): v2
I/libpersona( 5310): KNOX_SDCARD checking this for 1000
,I/libpersona( 5310): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=5310 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 5310): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5310): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5310): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5310): TimaSignature is unavailable
,D/ActivityThread( 5310): Added TimaKeyStore provider
,D/KnoxSetupWizardDbHelper( 5310): dbMigrationFlag : false
,D/ShortcutReceiver( 5310):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,I/ActivityManager( 1016): Killing 4569:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PackageBroadcastService( 1854): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,I/PackageBroadcastService( 1854): Null package name or gms related package.  Ignoreing.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Icing   ( 1854): updateResources: need to parse f{com.google.android.gms}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/UpdateIcingCorporaServi( 4227): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5332): MountEmulatedStorage(),
,E/Zygote  ( 5332): v2
I/libpersona( 5332): KNOX_SDCARD checking this for 10142
I/libpersona( 5332): KNOX_SDCARD not a persona
,I/SELinux ( 5332): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5332 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5332): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5332): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1016): failed to open /acct/uid_10047/pid_4569/cgroup.procs: No such file or directory
,I/CalendarProvider2( 5224): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/TimaKeyStoreProvider( 5332): TimaSignature is unavailable
,D/ActivityThread( 5332): Added TimaKeyStore provider
,I/UpdateIcingCorporaServi( 4227): UpdateCorporaTask done [took 86 ms] updated apps [took 86 ms] 
,I/ActivityManager( 1016): Killing 4588:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,V/TaskCloserActivity( 5332): TaskCloserActivity enter()
,V/TaskCloserActivity( 5332): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Killing 4647:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,D/GCM     ( 1665): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AuthorizationBluetoothService( 1665): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/GmsCoreStatsServiceLauncher( 1854): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1691): [188] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1854): Restart initialization of location
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.requestwriter.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.requestwriter.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/VideoCapabilities( 5244): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5244): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5244): Unrecognized profile 2130706433 for video/avc
,E/SQLiteLog( 1665): (10) POSIX Error : 11 SQLite Error : 3850
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/EnterpriseController(  279): uids 10012
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10012
,E/Zygote  ( 5356): MountEmulatedStorage()
E/Zygote  ( 5356): v2
I/libpersona( 5356): KNOX_SDCARD checking this for 10111
I/libpersona( 5356): KNOX_SDCARD not a persona
I/SELinux ( 5356): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5356): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1016): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=5356 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5356): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5356): TimaSignature is unavailable
,D/ActivityThread( 5356): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_10152/pid_4647/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10091/pid_4588/cgroup.procs: No such file or directory
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 24557(1385KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 26MB/40MB, paused 2.272ms total 153.691ms
,I/MusicStore( 5356): Database version: 120
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/BluetoothAdapter( 4732): disable()
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5356): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/BluetoothManagerService( 1016): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1016): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1016): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1016): mCursor = null
,D/WifiService( 1016): setWifiEnabled: false pid=4732, uid=10174
,D/SettingsProvider( 1016): name = wifi_on
,I/jxcore-log( 4732): ****TEST TOOK:  5061  ms ****
I/jxcore-log( 4732): 
,I/jxcore-log( 4732): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4732): 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5356): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5356): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ResourcesManager( 5356): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5356): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5356): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 5356): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5356): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d5b6677: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5356): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5356): GMSCore installation verified
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ConfigStore( 5356): Config Database version: 1
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1016): getStreamVolume 3 index 0
I/MediaRouter( 5356): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/AndroidRuntime( 5380): 
D/AndroidRuntime( 5380): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/AndroidRuntime( 5380): CheckJNI is OFF
D/AndroidRuntime( 5380): readGMSProperty: start
D/AndroidRuntime( 5380): readGMSProperty: already setted!!
D/AndroidRuntime( 5380): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5380): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5380): readGMSProperty: end
D/AndroidRuntime( 5380): addProductProperty: start
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:mai,n, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.android.settings
,I/SettingSearch/SearchIntentReceiver( 1293): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1293): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/MusicLeanback( 5356): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 5356): Stop autocaching.
,I/MusicLeanback( 5356): Stop autocaching.
,I/MusicLeanback( 5356): Stop autocaching.
I/SettingSearch/SearchIntentReceiver( 1293): InitTitleDBThread start --> mDoingInitTitleDB : true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
,I/SettingSearch/SearchIntentReceiver( 1293): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1293): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,D/daemonapp( 1279): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1279): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1279): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/MusicLeanback( 5356): Stop autocaching.
,I/GHttpClientFactory( 5356): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/daemonapp( 1279): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1279): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1279): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 1279): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1279): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1279): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1279): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1279): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1279): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1279): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/GoogleURLConnFactory( 5356): Using platform SSLCertificateSocketFactory
,D/daemonapp( 1279): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1279): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1447803660000
D/daemonapp( 1279): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1447782145360
D/daemonapp( 1279): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/daemonapp( 1279): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1279): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1279): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1279): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1279): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
E/daemonapp( 1279): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5402): MountEmulatedStorage()
,E/Zygote  ( 5402): v2
I/libpersona( 5402): KNOX_SDCARD checking this for 1000
,I/libpersona( 5402): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=5402 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 5402): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SettingSearch/SettingsSearchManager( 1293): Infomation -> numtitleinfo : 0 numSearchinfo : 315
,I/SELinux ( 5402): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5402): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5402): TimaSignature is unavailable
,D/ActivityThread( 5402): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/AffinityControl( 5380): AffinityControl: registerfunction enter
,I/DIAGMON_AGENT( 5402): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/SettingSearch/SettingsSearchManager( 1293):  Infomation -> getItem size : 315
,D/AndroidRuntime( 5380): Calling main entry com.android.commands.pm.Pm
E/GmsUtils( 5356): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5356): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager( 1016): Killing 4036:com.policydm/1000 (adj 15): empty #31
,D/PersonaManagerService( 1016): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1016): START PACKAGE DELETE: observer{957958388}
D/PackageManager( 1016): pkg{<packageName>}
D/PackageManager( 1016): user{0}
D/PackageManager( 1016): caller{2000}
D/PackageManager( 1016): flags{3}
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1016): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1016): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager( 1016): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1016): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1016): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1016): !@killApplicatoin: 10174, uninstall pkg
,I/ActivityManager( 1016): Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
,I/ActivityManager( 1016): Killing 4732:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,W/PackageSettings( 1016): Skipping PackageSetting{1fa663b1 com.test.thalitest/10175} due to missing metadata
,I/DIAGMON_AGENT( 5402): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 5402): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 5402): [com.diagmondm.XDMBroadcastReceiver(33/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/WindowState( 1016): WIN DEATH: Window{9efedfb u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (6/8)
I/SurfaceFlinger(  258): id=11 Removed NainActivit (-2/8)
,D/InputDispatcher( 1016): Focus left window: 4732
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (-2/8)
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1016):   Force finishing activity ActivityRecord{2ec0e2be u0 com.example.hello/.MainActivity t228}
,D/InputDispatcher( 1016): Focused application released
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4036/cgroup.procs: No such file or directory
,I/ActivityManager( 1016): Killing 4665:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,W/ResourcesManager( 1293): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 1293): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1293): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1293): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1016): Spurious death for ProcessRecord{24b6981d 4732:com.example.hello/u0a174}, curProc for 4732: null
,I/ActivityManager( 1016): Force stopping com.example.hello appid=10174 user=0: pkg removed
,I/DBG_DM  ( 2830): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
,E/SamsungIME( 1772): mOCRHelper is null
I/art     ( 3832): Explicit concurrent mark sweep GC freed 2178(132KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 6MB/11MB, paused 2.345ms total 22.921ms
,I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,W/GeofencerStateMachine( 1691): Ignoring removeGeofence because network location is disabled.
,I/art     ( 4227): Explicit concurrent mark sweep GC freed 23614(1728KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 9MB/12MB, paused 953us total 45.897ms
,D/accuweather( 1611): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1279): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1611): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1611): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1611): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1611): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/RegisteredComponentCache( 1454): Collect Tech packages for Knox
,D/PersonaManager( 1454): isKioskContainerExistOnDevice
,D/daemonapp( 1279): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1279): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,D/accuweather( 1611): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1611): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1611): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1611): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,D/PersonaManager( 1454): isKioskContainerExistOnDevice
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1611): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1611): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/RegisteredServicesCache( 1454): empty dynamic service
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/SQLiteLog( 1665): (10) POSIX Error : 11 SQLite Error : 3850
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/RCPManagerService( 1016): PackageReceiver onReceive()
,I/HarmonyEASService( 1016): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1016): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1016): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1016): DBIntegrity::getInstance - New instance created
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,D/OTPFW   ( 1016): PackageRemovalReceiver::onReceive deleting token for Pkg = com.example.hello uid = 10174 container id = 0
,I/OTPFW   ( 1016): ProvisionData::getAllEntries Enter
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,E/OTPFW   ( 1016): ProvisionData::getAllEntries Table is empty
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1016): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10174
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10174
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,D/SSRM:aZ ( 1016): MSG_TYPE_APP_REMOVED::
D/TaskPersister( 1016): removeObsoleteFile: deleting file=228_task.xml
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/EnterpriseDeviceManagerService( 1016): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1016): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1016): no available spell checker services found
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/CscFactoryReceiver( 1470): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1470): Media DB Scanner finished.
D/CscFactoryReceiver( 1470): start service to Set Ringtone
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1470): start service to Set Notification
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1470): start service to Set Alarmtone
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscUpdateService( 1470): onStart
E/CscUpdateService( 1470): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1470): only ringtone update
,D/CscUpdateService( 1470): onStart
E/CscUpdateService( 1470): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1470): only notification update
D/CscUpdateService( 1470): onStart
E/CscUpdateService( 1470): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1470): only alarmtone update
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
,E/CscParser( 1470): update(): xml file exist
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 26916(1982KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/40MB, paused 4.094ms total 247.906ms
,E/CscParser( 1470): update(): xml file exist
,E/CscParser( 1470): update(): xml file exist
,E/Zygote  ( 5433): MountEmulatedStorage()
E/Zygote  ( 5433): v2
W/CSCSettings( 1470): Setting Ringtones (type) : 4
D/CscParser( 1470): AlarmTone: null
W/CSCSettings( 1470): 1. Tag_Str: null
,I/SELinux ( 5433): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 5433): KNOX_SDCARD checking this for 10006
W/CSCSettings( 1470): Setting Ringtones (type) : 1
I/libpersona( 5433): KNOX_SDCARD not a persona
D/CscParser( 1470): RingTone: null
I/ActivityManager( 1016): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5433 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
W/CSCSettings( 1470): 1. Tag_Str: null
I/SELinux ( 5433): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/CSCSettings( 1470): Setting Ringtones (type) : 2
D/CscParser( 1470): MessageTone: null
W/CSCSettings( 1470): 1. Tag_Str: null
E/SELinux ( 5433): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5433): TimaSignature is unavailable
,D/ActivityThread( 5433): Added TimaKeyStore provider
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ThumbnailProvider( 5433): ThumbnailProvider onCreate()
,W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/DocumentBroadcastReceiver( 5433): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 5433): [START] processBroadcastIntent ...
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,E/SMD     (  289): DCD OFF
,D/PackageManager( 1016): delete codoeFile: 
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/AASAuninstall( 1016): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.example.hello
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
I/AASA_removePackage( 1016): UID=10174 Target=com.example.hello
D/PackageManager( 1016): result of delete: 1{957958388}
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/AndroidRuntime( 5380): Shutting down VM
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/Zygote  ( 5449): MountEmulatedStorage()
E/Zygote  ( 5449): v2
I/libpersona( 5449): KNOX_SDCARD checking this for 10040
I/libpersona( 5449): KNOX_SDCARD not a persona
,I/SELinux ( 5449): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5449): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1016): Start proc com.sec.android.app.music:service for broadcast com.sec.android.app.music/.appwidget.MusicAppWidgetProvider: pid=5449 uid=10040 gids={50040, 9997, 3003, 3002, 1028, 1015, 1023, 1007} abi=armeabi-v7a
E/SELinux ( 5449): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/BroadcastProcessorService( 5433): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,I/SystemInfo( 5433): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 5433): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/BroadcastProcessorService( 5433): [START] DocumentService startDocumentService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/DocumentService( 5433): DocumentService onCreate ... service
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1016): clearDefaults: com.example.hello
I/CrashAnrDetector( 1016): onPackageRemoved : com.example.hello
D/TimaKeyStoreProvider( 5449): TimaSignature is unavailable
W/libprocessgroup( 1016): failed to open /acct/uid_10053/pid_4665/cgroup.procs: No such file or directory
D/ActivityThread( 5449): Added TimaKeyStore provider
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5433): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5433): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/CheckinService( 1854): Done disabling old GoogleServicesFramework version
,I/SettingSearch/SearchIntentReceiver( 1293): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1293): LOCALE_CHANGED call search setting db finish!!
,W/ResourcesManager( 5449): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5449): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5449): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5449): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5449): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5449): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/SystemInfo( 5433): [SIOP LEVEL] : 0
,I/DocumentService( 5433): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5433): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/SettingSearch/SearchIntentReceiver( 1293): InitTitleDBThread start --> mDoingInitTitleDB : true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 5269): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/GalleryCacheReady( 5269): handleMeidaScanFinish()
,I/SettingSearch/SearchIntentReceiver( 1293): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 1293): LOCALE_CHANGED call search setting db finish!!
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/File    ( 5433): fail readDirectory() errno=13
,E/File    ( 5433): fail readDirectory() errno=13
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,W/ContextImpl( 5269): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,I/SystemInfo( 5433): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5433): [STOP DOCUMENTSERVICE] Attempting to stop the Service
,E/DocumentService( 5433): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :84
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
E/DocumentService( 5433): [THUMBNAIL] Total Time taken for each file :0
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
E/        ( 5433): [INDEX] Total time taken for each file :0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,W/ContextImpl( 5269): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,I/DocumentService( 5433): DocumentService onDestroy start
I/DocumentService( 5433): DocumentService onDestroy end
,I/DocumentService( 5433): DocumentService cleanupEverything start
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/IndexParserThreadsManager( 5433): InterruptedException: null
,W/ContextImpl( 5269): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5269): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,I/SystemInfo( 5433): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5433): DocumentService cleanupEverything end
,I/Process ( 5433): Sending signal. PID: 5433 SIG: 9
,D/FaceInterface( 5269): requestFaceScan() is called.
,I/FaceInterface( 5269): startFaceScan() : waiting 5 sec
,W/LocalSuggestAlbumData( 5269): query fail: 
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/LocalSuggestAlbumData( 5269): query fail: 
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,W/art     ( 5380): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,I/KLMS-2.5.183: ( 3546): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Nov 17 18:42:26 GMT+01:00 2015
,E/lowmemorykiller(  255): Error writing /proc/5433/oom_score_adj; errno=22
,I/ActivityManager( 1016): Killing 4698:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3546): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1016): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=28
I/splitIntent( 1016): base  index=28, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1016): other index=31, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3546): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3546): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3546): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  ( 5475): MountEmulatedStorage(),
E/Zygote  ( 5475): v2
,I/libpersona( 5475): KNOX_SDCARD checking this for 10094
I/libpersona( 5475): KNOX_SDCARD not a persona
,I/SELinux ( 5475): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5475 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 5475): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5475): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3546): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3546): KLMSIntentService(): PACKAGE_REMOVED
,I/ActivityManager( 1016): Process com.samsung.indexservice (pid 5433)(adj 13) has died(95,1086)
,I/KLMS-2.5.183: ( 3546): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.183: ( 3546): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/TimaKeyStoreProvider( 5475): TimaSignature is unavailable
,D/ActivityThread( 5475): Added TimaKeyStore provider
,E/SQLiteLog( 5356): (10) POSIX Error : 9 SQLite Error : 3850
,E/SQLiteLog( 5356): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/libprocessgroup( 1016): failed to open /acct/uid_10156/pid_4698/cgroup.procs: No such file or directory
,D/elm:15183( 5475): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 5475): ELMEngine.ELMEngine( context ).
,D/elm:15183( 5475): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 5475): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15183( 5475): ElmAgentService : onCreate()
I/KLMS-2.5.183: ( 3546): KLMSIntentService(): listeningToPackageRemoved().END
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/AndroidRuntime( 5356): FATAL EXCEPTION: MediaStoreImportService
E/AndroidRuntime( 5356): Process: com.google.android.music:main, PID: 5356
E/AndroidRuntime( 5356): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5356): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 5356): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime( 5356): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 5356): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 5356): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/AndroidRuntime( 5356): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/AndroidRuntime( 5356): 	at com.google.android.music.store.BaseStore.beginWriteTxn(BaseStore.java:58)
E/AndroidRuntime( 5356): 	at com.google.android.music.store.Store.beginWriteTxn(Store.java:232)
E/AndroidRuntime( 5356): 	at com.google.android.music.store.MediaStoreImporter.importAudioFiles(MediaStoreImporter.java:504)
E/AndroidRuntime( 5356): 	at com.google.android.music.store.MediaStoreImporter.importNow(MediaStoreImporter.java:307)
E/AndroidRuntime( 5356): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:222)
E/AndroidRuntime( 5356): 	at com.google.android.music.store.Store.importMediaStore(Store.java:10438)
E/AndroidRuntime( 5356): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/AndroidRuntime( 5356): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/AndroidRuntime( 5356): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/AndroidRuntime( 5356): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 5356): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5356): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/AndroidRuntime( 5356): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 5356): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/elm:15183( 5475): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15183( 5475): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 5475): MDMBridge.getInstance()
D/elm:15183( 5475): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15183( 5475): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 5492): MountEmulatedStorage()
,E/Zygote  ( 5492): v2
I/libpersona( 5492): KNOX_SDCARD checking this for 1000
I/libpersona( 5492): KNOX_SDCARD not a persona
,I/SELinux ( 5492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1016): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5492 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 5492): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.music:main
,I/KLMS-2.5.183: ( 3546): KLMSIntentService(): onDestroy()
,D/elm:15183( 5475): ElmAgentService : onDestroy().
,E/DropBoxManagerService( 1016): Can't write: system_app_crash
E/DropBoxManagerService( 1016): java.io.FileNotFoundException: /data/system/dropbox/drop163.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1016): 	,at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1016): 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1016): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1016): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1016): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
E/DropBoxManagerService( 1016): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1016): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1016): 	,at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1016): 	... 5 more
,I/Process ( 5356): Sending signal. PID: 5356 SIG: 9
,D/TimaKeyStoreProvider( 5492): TimaSignature is unavailable,
,D/ActivityThread( 5492): Added TimaKeyStore provider

```
