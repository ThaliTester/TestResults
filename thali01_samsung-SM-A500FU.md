#### Test 58741471ee11130_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.sec.smartcard.manager
W/ContextImpl( 4980): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
--------- beginning of system
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.smartcard.manager, hostingType: broadcast
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5008): MountEmulatedStorage()
E/Zygote  ( 5008): v2
I/SELinux ( 5008): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5008): KNOX_SDCARD checking this for 10153
I/libpersona( 5008): KNOX_SDCARD not a persona
I/SELinux ( 5008): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5008): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/FaceInterface( 4980): requestFaceScan() is called.
I/ActivityManager( 1015): Start proc com.sec.smartcard.manager for broadcast com.sec.smartcard.manager/com.sec.smartcard.pinservice.SmartCardBroadcastReceiver: pid=5008 uid=10153 gids={50153, 9997, 3001, 3002} abi=armeabi-v7a
W/LocalSuggestAlbumData( 4980): query fail: 
W/LocalSuggestAlbumData( 4980): query fail: 
I/FaceInterface( 4980): startFaceScan() : waiting 5 sec
D/TimaKeyStoreProvider( 5008): TimaSignature is unavailable
D/ActivityThread( 5008): Added TimaKeyStore provider
W/ResourcesManager( 5008): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
E/SmartCardContentProvider( 5008): onCreate
I/SmartCardBroadcastReceiver( 5008): SmartCardBroadcastReceiver - onReceive() 
I/SmartCardBroadcastReceiver( 5008): Broadcast received for locktype changed 
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
I/ActivityManager( 1015): Killing 4569:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
E/CscFactoryReceiver( 1454): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1454): Media DB Scanner finished.
D/CscFactoryReceiver( 1454): start service to Set Ringtone
D/ActivityManager( 1015): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/CscFactoryReceiver( 1454): start service to Set Notification
D/ActivityManager( 1015): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
I/Mms/MmsApp( 4731):  start initViewCache mms
D/Mms/ComposeMessageFragment( 4731): [start]    fillCache consume time = 1927.490156
D/Mms/ComposeMessageFragment( 4731): fillCache, easy = false
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/CscFactoryReceiver( 1454): start service to Set Alarmtone
D/ActivityManager( 1015): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/CscUpdateService( 1454): onStart
E/CscUpdateService( 1454): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1454): only ringtone update
D/CscUpdateService( 1454): onStart
E/CscUpdateService( 1454): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1454): only notification update
D/CscUpdateService( 1454): onStart
E/CscUpdateService( 1454): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1454): only alarmtone update
W/ActivityManager( 1015): userId = 0, bbcId = -10000
E/CscParser( 1454): update(): xml file exist
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.indexservice, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/CscParser( 1454): update(): xml file exist
W/CSCSettings( 1454): Setting Ringtones (type) : 2
W/CSCSettings( 1454): Setting Ringtones (type) : 1
D/CscParser( 1454): MessageTone: null
D/CscParser( 1454): RingTone: null
W/CSCSettings( 1454): 1. Tag_Str: null
W/CSCSettings( 1454): 1. Tag_Str: null
E/CscParser( 1454): update(): xml file exist
E/Zygote  ( 5032): MountEmulatedStorage()
I/libpersona( 5032): KNOX_SDCARD checking this for 10006
E/Zygote  ( 5032): v2
I/libpersona( 5032): KNOX_SDCARD not a persona
I/SELinux ( 5032): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/CSCSettings( 1454): Setting Ringtones (type) : 4
D/CscParser( 1454): AlarmTone: null
W/CSCSettings( 1454): 1. Tag_Str: null
I/ActivityManager( 1015): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5032 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5032): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5032): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  304): Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 651us total 22.218ms
D/TimaKeyStoreProvider( 5032): TimaSignature is unavailable
D/ActivityThread( 5032): Added TimaKeyStore provider
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 17.771ms
I/ThumbnailProvider( 5032): ThumbnailProvider onCreate()
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 17.109ms
D/AbsListView( 4731): Get MotionRecognitionManager
D/MotionRecognitionService( 1015):  ssp status : false
I/DocumentBroadcastReceiver( 5032): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
I/BroadcastProcessorService( 5032): [START] processBroadcastIntent ...
D/ActivityManager( 1015): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
D/Mms/ComposeMessageFragment( 4731): [end]    fillCache consume time = 120.032916
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
W/libprocessgroup( 1015): failed to open /acct/uid_10113/pid_4569/cgroup.procs: No such file or directory
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
D/GalleryCacheReady( 4980): Receive action.ACTION_MEDIA_SCANNER_FINISHED
D/GalleryCacheReady( 4980): handleMeidaScanFinish()
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
D/FaceInterface( 4980): requestFaceScan() is called.
I/FaceInterface( 4980): startFaceScan() : waiting 5 sec
W/LocalSuggestAlbumData( 4980): query fail: 
W/LocalSuggestAlbumData( 4980): query fail: 
D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
I/BroadcastProcessorService( 5032): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
I/SystemInfo( 5032): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 5032): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
I/BroadcastProcessorService( 5032): [START] DocumentService startDocumentService
D/ActivityManager( 1015): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
I/DocumentService( 5032): DocumentService onCreate ... service
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5032): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5032): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
D/Mms/BubbleViewCache( 4731): fillCache bubble = 1
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.app.popupuireceiver
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5054): MountEmulatedStorage()
I/libpersona( 5054): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5054): v2
I/libpersona( 5054): KNOX_SDCARD not a persona
D/SensorService( 1015): [SO] 0.019 0.096 10.132
I/SELinux ( 5054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/SystemInfo( 5032): [SIOP LEVEL] : 0
I/SELinux ( 5054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5054 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 5054): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DocumentService( 5032): [BEGIN SYNC] DocumentService beginIndexing :16
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5032): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
D/TimaKeyStoreProvider( 5054): TimaSignature is unavailable
D/ActivityThread( 5054): Added TimaKeyStore provider
E/File    ( 5032): fail readDirectory() errno=13
E/File    ( 5032): fail readDirectory() errno=13
I/SystemInfo( 5032): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5032): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 5032): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :47
E/DocumentService( 5032): [THUMBNAIL] Total Time taken for each file :0
E/        ( 5032): [INDEX] Total time taken for each file :0
D/PopupuiReceiver( 5054): onReceive() getAction : com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED
D/SecContentProvider2( 1015): uri = -1 selection = getSealedState
D/SecContentProvider2( 1015): mCursor = null
I/PopupuiReceiver_KNOX( 5054): getSealedState : true
D/SecContentProvider2( 1015): uri = 15 selection = getSealedHideNotificationMessages
D/SecContentProvider2( 1015): mCursor = null
I/DocumentService( 5032): DocumentService onDestroy start
I/DocumentService( 5032): DocumentService onDestroy end
I/PopupuiReceiver_KNOX( 5054): getSealedHideNotificationMessages : 1
D/SecContentProvider2( 1015): uri = 15 selection = getCheckCoverPopupState
D/SecContentProvider2( 1015): mCursor = null
I/DocumentService( 5032): DocumentService cleanupEverything start
I/PopupuiReceiver_KNOX( 5054): getCheckCoverPopupState : true
D/PopupuiReceiver( 5054): Action cable connected ! on - 
I/IndexParserThreadsManager( 5032): InterruptedException: null
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.samsung.android.app.powersharing
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.powersharing, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 4947): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/Zygote  ( 5073): MountEmulatedStorage()
E/Zygote  ( 5073): v2
I/libpersona( 5073): KNOX_SDCARD checking this for 10122
I/libpersona( 5073): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.samsung.android.app.powersharing for broadcast com.samsung.android.app.powersharing/.service.BatteryReceiver: pid=5073 uid=10122 gids={50122, 9997} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 4548:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
I/SELinux ( 5073): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SystemInfo( 5032): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5032): DocumentService cleanupEverything end
I/Process ( 5032): Sending signal. PID: 5032 SIG: 9
I/SELinux ( 5073): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5073): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 4947): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4947): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4947): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/ActivityManager( 1015): Process com.samsung.indexservice (pid 5032)(adj 11) has died(107,1148)
D/TimaKeyStoreProvider( 5073): TimaSignature is unavailable
D/ActivityThread( 5073): Added TimaKeyStore provider
W/libprocessgroup( 1015): failed to open /acct/uid_10010/pid_4548/cgroup.procs: No such file or directory
I/MediaStoreImporter( 4458): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/PowerSharing.BatteryReceiver( 5073): onReceive : com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.wluc, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.sec.android.app.wluc for broadcast com.sec.android.app.wluc/.PolicyManagerBroadcastReceiver: pid=5088 uid=10165 gids={50165, 9997} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 4625:com.sec.android.cloudagent/u0a2 (adj 15): empty #31
E/Zygote  ( 5088): MountEmulatedStorage()
E/Zygote  ( 5088): v2
I/libpersona( 5088): KNOX_SDCARD checking this for 10165
I/libpersona( 5088): KNOX_SDCARD not a persona
I/SELinux ( 5088): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5088): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5088): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5088): TimaSignature is unavailable
D/ActivityThread( 5088): Added TimaKeyStore provider
I/PolicyManagerBroadcastReceiver( 5088): onReceive: action = com.sec.intent.ACTION.SSRM_HGL_UPDATE
I/PolicyManagerBroadcastReceiver( 5088): onReceive: width = 720, height = 1280
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5103): MountEmulatedStorage()
E/Zygote  ( 5103): v2
I/ActivityManager( 1015): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuSettingSearch: pid=5103 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/libpersona( 5103): KNOX_SDCARD checking this for 1000
I/libpersona( 5103): KNOX_SDCARD not a persona
I/SELinux ( 5103): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5103): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Killing 4670:com.sec.android.diagmonagent/1000 (adj 15): empty #31
E/SELinux ( 5103): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5103): TimaSignature is unavailable
D/ActivityThread( 5103): Added TimaKeyStore provider
D/AssistantMenuSettingSearch( 5103): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
D/AssistantMenuSettingSearch( 5103): Make Setting DB
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.sec.providers.settingsearch
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5118): MountEmulatedStorage()
E/Zygote  ( 5118): v2
I/libpersona( 5118): KNOX_SDCARD checking this for 10150
I/libpersona( 5118): KNOX_SDCARD not a persona
I/SELinux ( 5118): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5118): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=5118 uid=10150 gids={50150, 9997} abi=armeabi-v7a
E/SELinux ( 5118): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5118): TimaSignature is unavailable
D/ActivityThread( 5118): Added TimaKeyStore provider
W/libprocessgroup( 1015): failed to open /acct/uid_10002/pid_4625/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4670/cgroup.procs: No such file or directory
W/ContextImpl( 5103): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:158 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:38 
W/ActivityManager( 1015): userId = 0, bbcId = -10000
I/ActivityManager( 1015): Killing 4653:com.google.android.apps.plus/u0a120 (adj 15): empty #31
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.phone
I/ActivityManager( 1015): Killing 3148:com.policydm/1000 (adj 15): empty #32
I/SettingSearchManagerReceiver( 1454): onReceive : com.samsung.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
I/SettingSearchManagerReceiver( 1454): addSearchInfoDB
W/libprocessgroup( 1015): failed to open /acct/uid_10120/pid_4653/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3148/cgroup.procs: No such file or directory
I/ActivityManager( 1015): Waited long enough for: ServiceRecord{14bad13c u0 com.samsung.hs20settings/.WifiHs20UtilityService}
D/SSRM:n  ( 1015): SIOP:: AP = 400
I/SettingSearchManagerReceiver( 1454): endInsert
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5138): MountEmulatedStorage()
I/ActivityManager( 1015): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5138 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 5138): v2
I/libpersona( 5138): KNOX_SDCARD checking this for 10101
D/AndroidRuntime( 5122): 
D/AndroidRuntime( 5122): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/libpersona( 5138): KNOX_SDCARD not a persona
I/SELinux ( 5138): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5138): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5138): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 5122): CheckJNI is OFF
D/AndroidRuntime( 5122): readGMSProperty: start
D/AndroidRuntime( 5122): readGMSProperty: already setted!!
D/AndroidRuntime( 5122): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5122): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5122): readGMSProperty: end
D/AndroidRuntime( 5122): addProductProperty: start
D/TimaKeyStoreProvider( 5138): TimaSignature is unavailable
D/ActivityThread( 5138): Added TimaKeyStore provider
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/AffinityControl( 5122): AffinityControl: registerfunction enter
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/AndroidRuntime( 5122): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
D/AndroidRuntime( 5122): Shutting down VM
I/Gmail   ( 5138): getAccountsCursor
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1825): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5138): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/Gmail   ( 5138): Observing account changes for notifications
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 5138): Error finding the version of the Email provider.....
E/Gmail   ( 5138): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5138): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 5138): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 5138): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 5138): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5138): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5138): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 5138): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5138): We do not support migrating this version of the Email provider.
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/Gmail   ( 5138): getAccountsCursor
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1825): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5181): MountEmulatedStorage()
I/libpersona( 5181): KNOX_SDCARD checking this for 10033
E/Zygote  ( 5181): v2
I/libpersona( 5181): KNOX_SDCARD not a persona
I/SELinux ( 5181): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=5181 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 4229:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
I/SELinux ( 5181): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
E/SELinux ( 5181): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
V/GLSActivity( 1825): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimaKeyStoreProvider( 5181): TimaSignature is unavailable
D/ActivityThread( 5181): Added TimaKeyStore provider
E/SQLiteLog( 5138): (283) recovered 36 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
W/art     ( 5122): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/libprocessgroup( 1015): failed to open /acct/uid_10125/pid_4229/cgroup.procs: No such file or directory
,W/ResourcesManager( 5181): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5181): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5181): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/File    ( 5138): fail readDirectory() errno=2
,I/Gmail   ( 5138): notifyAccountChanged
,I/Gmail   ( 5138): getAccountsCursor
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1825): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 5181): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
W/ResourcesManager( 5181): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5181): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,I/Gmail   ( 5138): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 5181): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5181): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 5181): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
I/Gmail   ( 5138): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5138): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5138): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5138): getAccountsCursor
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1825): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SPPClientService( 3972): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5214): MountEmulatedStorage(),
E/Zygote  ( 5214): v2
I/libpersona( 5214): KNOX_SDCARD checking this for 10035
I/libpersona( 5214): KNOX_SDCARD not a persona
I/SELinux ( 5214): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5214): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1015): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=5214 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5214): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 4471:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5214): TimaSignature is unavailable
,D/ActivityThread( 5214): Added TimaKeyStore provider
,E/SPPClientService( 5214): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5214): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 5214): PushLog.txt file is not deleted.
,D/SPPClientService( 5214): PushLog.txt file is not deleted.
,D/SPPClientService( 5214): ============PushLog. stop!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 4267:com.android.calendar/u0a135 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5234): MountEmulatedStorage(),
E/Zygote  ( 5234): v2
I/libpersona( 5234): KNOX_SDCARD checking this for 10035,
I/libpersona( 5234): KNOX_SDCARD not a persona
I/SELinux ( 5234): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5234): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5234): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=5234 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5234): TimaSignature is unavailable
,D/ActivityThread( 5234): Added TimaKeyStore provider
,E/SPPClientService( 5234): ============PushLog. commonIsShipBuild. stop!
E/LNoti   ( 5234): [PhoneStatusChangeReceiver] This device doesn't register yet.
,E/SPPClientService( 5234): [PushClientApplication] Push log off : This is Ship build version
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 4389:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SPPClientService( 5234): PushLog.txt file is not deleted.
,D/SPPClientService( 5234): PushLog.txt file is not deleted.
D/SPPClientService( 5234): ============PushLog. stop!
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1015): failed to open /acct/uid_10009/pid_4471/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.download.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1825): No location to return for getLastLocation()
,W/FusedLocationProvider( 1825): location=null
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SafeBrowsingUpdateIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
,W/libprocessgroup( 1015): failed to open /acct/uid_10135/pid_4267/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4389/cgroup.procs: No such file or directory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1825): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1015): Background sticky concurrent mark sweep GC freed 163959(5MB) AllocSpace objects, 19(5MB) LOS objects, 12% free, 54MB/62MB, paused 4.008ms total 129.196ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5259): MountEmulatedStorage()
,E/Zygote  ( 5259): v2
,I/libpersona( 5259): KNOX_SDCARD checking this for 10104,
I/libpersona( 5259): KNOX_SDCARD not a persona
I/SELinux ( 5259): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5259 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 5259): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5259): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/SMD     (  287): DCD OFF
,D/TimaKeyStoreProvider( 5259): TimaSignature is unavailable
,D/ActivityThread( 5259): Added TimaKeyStore provider
,W/ResourcesManager( 5259): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 356067(20MB) AllocSpace objects, 2(3MB) LOS objects, 30% free, 36MB/52MB, paused 5.070ms total 249.219ms
,I/Babel   ( 5259): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 5259): MmsConfig.loadMmsSettings
I/Babel   ( 5259): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 5259): MmsConfig.loadFromDatabase
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/Babel   ( 5259): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5259): MmsConfig.loadFromResources
,W/Settings( 5259): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Babel   ( 5259): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 5259): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel_StickerModule( 5259): App launched.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5284): MountEmulatedStorage(),
,I/ActivityManager( 1015): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=5284 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 5284): v2,
,I/libpersona( 5284): KNOX_SDCARD checking this for 1000
I/libpersona( 5284): KNOX_SDCARD not a persona
I/SELinux ( 5284): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5284): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  282): getCameraInfo: X,
W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  282): getCameraInfo: X
E/SELinux ( 5284): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5284): TimaSignature is unavailable
,D/ActivityThread( 5284): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 8701(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 28.248ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 16.983ms
,W/VideoCapabilities( 5259): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5259): Unsupported mime audio/evrc
,W/AudioCapabilities( 5259): Unsupported mime audio/qcelp
,I/DIAGMON_AGENT( 5284): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/AudioCapabilities( 5259): Unsupported mime audio/mpeg-L1
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 17.113ms
,W/AudioCapabilities( 5259): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5259): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5259): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5259): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5259): Unsupported mime audio/evrc
,W/VideoCapabilities( 5259): Unsupported mime video/wvc1
,W/VideoCapabilities( 5259): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5259): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5259): Unsupported mime video/wvc1
,W/VideoCapabilities( 5259): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5259): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5259): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5259): Unsupported mime video/mp43
,W/VideoCapabilities( 5259): Unsupported mime video/sorenson
,W/VideoCapabilities( 5259): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5259): Unsupported profile 4 for video/mp4v-es
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/ActivityManager( 1015): Killing 4048:com.android.providers.calendar/u0a42 (adj 15): empty #31
,I/DIAGMON_AGENT( 5284): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 5284): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 5284): [com.diagmondm.XDMBroadcastReceiver(33/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager( 1015): Killing 3998:com.osp.app.signin/u0a41 (adj 15): empty #31
,I/DBG_DM  ( 3089): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5301): MountEmulatedStorage(),
E/Zygote  ( 5301): v2
I/libpersona( 5301): KNOX_SDCARD checking this for 10135
I/libpersona( 5301): KNOX_SDCARD not a persona
,I/SELinux ( 5301): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5301): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5301 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux ( 5301): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5301): TimaSignature is unavailable,
D/ActivityThread( 5301): Added TimaKeyStore provider
,W/ResourcesManager( 5301): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5301): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5301): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/PackageManager( 1015): verifying app can be installed or not
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled
,D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking SIG BL - true
,D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  enabled true
,I/AASAInstall( 1015): ship mode
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/libprocessgroup( 1015): failed to open /acct/uid_10042/pid_4048/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10041/pid_3998/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ContextImpl( 4758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.sm.base.a.a:307 com.samsung.android.sm.contextagent.ContextAgentReceiver.onReceive:124 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5259): Creating RTCS,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5325): MountEmulatedStorage()
E/Zygote  ( 5325): v2
I/libpersona( 5325): KNOX_SDCARD checking this for 10142
I/libpersona( 5325): KNOX_SDCARD not a persona
,I/SELinux ( 5325): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5325): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5325 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 5325): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Babel   ( 5259): Destroying RTCS
,I/ActivityManager( 1015): Killing 4697:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5325): TimaSignature is unavailable
D/ActivityThread( 5325): Added TimaKeyStore provider
,V/TaskCloserActivity( 5325): TaskCloserActivity enter()
,V/TaskCloserActivity( 5325): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5340): MountEmulatedStorage(),
E/Zygote  ( 5340): v2
I/libpersona( 5340): KNOX_SDCARD checking this for 10042
I/libpersona( 5340): KNOX_SDCARD not a persona
,I/SELinux ( 5340): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5340 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 5340): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Killing 4716:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
E/SELinux ( 5340): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/art     ( 1015): Background sticky concurrent mark sweep GC freed 124978(6MB) AllocSpace objects, 10(2MB) LOS objects, 0% free, 53MB/53MB, paused 3.097ms total 146.964ms
,D/TimaKeyStoreProvider( 5340): TimaSignature is unavailable
,D/ActivityThread( 5340): Added TimaKeyStore provider
,W/ResourcesManager( 5340): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5340): CalendarProvider2.onCreate() called
,W/libprocessgroup( 1015): failed to open /acct/uid_10062/pid_4697/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10157/pid_4716/cgroup.procs: No such file or directory
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{3b17a41d u0 com.sec.bcservice/.BroadcastService}
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5359): MountEmulatedStorage(),
E/Zygote  ( 5359): v2
I/libpersona( 5359): KNOX_SDCARD checking this for 1000
I/libpersona( 5359): KNOX_SDCARD not a persona
I/SELinux ( 5359): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5359): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5359 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 5359): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/SQLiteLog( 5340): (284) automatic index on view_events(_id)
,D/TimaKeyStoreProvider( 5359): TimaSignature is unavailable
,D/ActivityThread( 5359): Added TimaKeyStore provider
,I/art     ( 1015): Background partial concurrent mark sweep GC freed 231381(13MB) AllocSpace objects, 11(8MB) LOS objects, 29% free, 38MB/54MB, paused 4.700ms total 192.579ms
,D/CalendarAlarmManager( 5340): sys current time:1455023149988
,D/CalendarAlarmManager( 5340): reminder amount:0
,E/MTPRx   ( 5359): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1015): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1015): mCursor = null
,V/MTPRx   ( 5359): sealedState: false
V/MTPRx   ( 5359): sealedUsbMassStorageState: false
E/MTPRx   ( 5359): check value of boot_completed is1
E/MTPRx   ( 5359): check booting is completed_sys.boot_completed
,E/MTPRx   ( 5359): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 5359): Status for mount/Unmount :removed
E/MTPRx   ( 5359): SDcard is not available
,W/MTPRx   ( 5359): value of connected istrue
W/MTPRx   ( 5359): value of configured istrue
W/MTPRx   ( 5359): value of mtpEnabled istrue
W/MTPRx   ( 5359): value of ptpEnabled isfalse
,E/MTPRx   ( 5359): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 5359): mFirstTime: false
,D/        ( 5359): MTP: reading debug level property
,E/MTPJNIInterface( 5359): Getting CryptionKey from JAVA
,E/MTPRx   ( 5359): currentUserId is 0
,E/MTPRx   ( 5359): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 5359): cannot open file : /sys/class/android_usb/android0/bcdUSB
,E/MTPRx   ( 5359): is_Privatemode is NOT 1
,D/SettingsProvider( 1015): name = mtp_usb_conditions_met
,D/SecContentProvider( 1015): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 5359): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1015): name = mtp_running_status
,D/SettingsProvider( 1015): name = mtp_usb_conditions_met,
,E/MTPRx   ( 5359): else part ... so first time!!!
E/MTPPlaObsrvr( 5359): inside setContext()
E/MTPPlaObsrvr( 5359):  inside createplafiles
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 5359): playlist count is0
E/MTPPlaObsrvr( 5359):  inside try branch createplafiles
,E/MTPPlaObsrvr( 5359):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 5359): Inside registerContentObserver
,E/MtpAdbObserver( 5359): inside setContext()
E/MtpAdbObserver( 5359): Inside registerContentObserver
W/Settings( 5359): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,V/MtpMediaDBManager( 5359): inside deleteAllDB
,D/SettingsProvider( 1015): name = mtp_running_status
,D/SettingsProvider( 1015): name = mtp_usb_conditions_met
,E/MtpService( 5359): onCreate.
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,V/MtpMediaDBManager( 5359): inside Thread updateDB
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,E/MtpService( 5359): < MTP > Registering BroadCast receiver :::::
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MtpMediaDBManager( 5359): count : 27
,E/MtpService( 5359): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 5359): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,D/MtpService( 1227): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpService( 5359): onStartCommand.
,E/MtpService( 5359): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,W/MTPRx   ( 5359): calling native method
E/MTPJNIInterface( 5359): < MTP > Registering BroadCast receiver :::::
,D/MediaScannerReceiver( 1227): action: com.samsung.intent.action.MTP_FILE_SCAN
,E/MTPJNIInterface( 5359): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 5359): noti = 10
E/MtpService( 5359): onStartCommand.
,W/MTPRx   ( 5359): calling native method
E/MTPRx   ( 5359): Checking the driver time out
E/MTPJNIInterface( 5359): noti = 2
D/        ( 5359): deleting sockets before message queue initialization
,D/        ( 5359): event handler thread is created, so set the flag
,E/MTPRx   ( 5359): called native method
E/MTPJNIInterface( 5359): setting Media scanner status0
E/MTPJNIInterface( 5359): After setting Media scanner status0
E/MtpService( 5359): handleMessage. msg= { when=-2ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/MTPRx   ( 5359): notification from stack 1
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/        ( 5359): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 5359): Getting media scanner status0
,E/MTPJNIInterface( 5359): DeviceName is A5-1
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/MtpMediaDBManager( 5359): sending db update complete noti to stack
,E/MTPJNIInterface( 5359): noti = 29
,E/MTPJNIInterface( 5359): Status for mount/Unmount :removed
E/MTPJNIInterface( 5359): SDcard is not available
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/        ( 5359): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,E/        ( 5359): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/MTPJNIInterface( 5359): Status for mount/Unmount :removed
E/MTPJNIInterface( 5359): SDcard is not available
,E/SQLiteLog( 5359): (21) API call with NULL database connection pointer
E/SQLiteLog( 5359): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 5359): (21) API call with NULL database connection pointer
E/SQLiteLog( 5359): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5359): (21) API call with NULL database connection pointer
E/SQLiteLog( 5359): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5359): (21) API call with NULL database connection pointer
E/SQLiteLog( 5359): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 5359): notification from stack 2
D/        ( 5359): [mtp_init_device] Library open with 32 bits.
,D/        ( 5359): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 5359): [mtp_init_device 702]  After open the MTP fd = 33 and line = 702...
D/        ( 5359): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 5359):  [sua_support_present:1287] returning false 
,D/        ( 5359): *****Starting mtp_io()
,W/MTPRx   ( 5359): notification from stack 3
,D/        ( 5359): [mtp_start_io] source_thread Creation 
,D/        ( 5359): [mtp_start_io] sink_thread Creation 
,D/        ( 5359): [mtp_start_io:376] sink thread created so set th_sink
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/PolicyManagerBroadcastReceiver( 5088): This process will be killed soon.
,I/Process ( 5088): Sending signal. PID: 5088 SIG: 9
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1825): callingUid 10012, callindPid: 1825
,I/ActivityManager( 1015): Process com.sec.android.app.wluc (pid 5088)(adj 15) has died(86,1158)
,D/MediaScannerService( 1227): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.android.settings
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SettingSearch/SearchIntentReceiver( 1320): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1320): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
,I/SettingSearch/SearchIntentReceiver( 1320): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1320): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/SettingSearch/SearchIntentReceiver( 1320): InitTitleDBThread start --> mDoingInitTitleDB : true
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,I/MusicLeanback( 4458): Conditions not met for autocaching.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/MusicLeanback( 4458): Stop autocaching.
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/MediaScanner( 1227): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
D/PackageManager( 1015): Existing package
,D/PackageManager( 1015): Renaming /data/app/vmdl1229993198.tmp to /data/app/com.test.thalitest-1
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,D/PackageManager( 1015): installNewPackageLI: Package{37f0d1f9 com.test.thalitest}
I/PackageManager( 1015): scanFileNewer : com.test.thalitest
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,V/MediaScanner( 1227): processDirectory :  /storage/emulated/0
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(75ebcf7
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,V/MediaScanner( 1227): processDirectory :  /storage/extSdCard
W/MediaScanner( 1227): Error opening directory, reason : Permission denied.
W/MediaScanner( 1227): 7klwibgf7fxlKdCbid7
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,V/MediaScanner( 1227):  prescan time: 26ms (DB items: 27)
V/MediaScanner( 1227):     scan time: 26ms (Caching mode: true), (makeEntry time: 12ms ~46%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 3ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 55ms
V/MediaScanner( 1227): checked files: 10  directories : 17  (I: 0, U: 0)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/MediaScannerService( 1227): !@done scanning volume external
,E/MTPJNIInterface( 5359): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,E/GmsUtils( 4458): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 4458): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SettingSearch/SettingsSearchManager( 1320): Infomation -> numtitleinfo : 0 numSearchinfo : 306
,I/iu.UploadsManager( 2006): End new media; added: 0, uploading: 0, time: 90 ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SettingSearch/SettingsSearchManager( 1320):  Infomation -> getItem size : 306
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
,E/CscFactoryReceiver( 1454): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1454): Media DB Scanner finished.
D/CscFactoryReceiver( 1454): start service to Set Ringtone
,D/ActivityManager( 1015): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,W/ResourcesManager( 1320): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 1320): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1320): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1320): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/CscFactoryReceiver( 1454): start service to Set Notification
,D/ActivityManager( 1015): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1454): start service to Set Alarmtone
,D/ActivityManager( 1015): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscUpdateService( 1454): onStart
,E/CscUpdateService( 1454): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1454): only ringtone update
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.indexservice, hostingType: broadcast
,D/CscUpdateService( 1454): onStart
E/CscUpdateService( 1454): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1454): only notification update
D/CscUpdateService( 1454): onStart
,E/CscUpdateService( 1454): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1454): only alarmtone update
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/CscParser( 1454): update(): xml file exist
,E/CscParser( 1454): update(): xml file exist
,E/Zygote  ( 5401): MountEmulatedStorage()
,E/Zygote  ( 5401): v2
I/libpersona( 5401): KNOX_SDCARD checking this for 10006
I/libpersona( 5401): KNOX_SDCARD not a persona
,I/SELinux ( 5401): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5401 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5401): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5401): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/CscParser( 1454): update(): xml file exist
,W/CSCSettings( 1454): Setting Ringtones (type) : 1
D/CscParser( 1454): RingTone: null
,W/CSCSettings( 1454): 1. Tag_Str: null
W/CSCSettings( 1454): Setting Ringtones (type) : 2
D/CscParser( 1454): MessageTone: null
W/CSCSettings( 1454): 1. Tag_Str: null
,W/CSCSettings( 1454): Setting Ringtones (type) : 4
D/CscParser( 1454): AlarmTone: null
W/CSCSettings( 1454): 1. Tag_Str: null
,I/art     ( 1015): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
I/art     ( 1015): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.test.thalitest-1/arm/base.odex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
D/PackageManager( 1015): Running dexopt on: /data/app/com.test.thalitest-1/base.apk pkg=com.test.thalitest isa=arm vmSafeMode=false interpret_only=false
,D/TimaKeyStoreProvider( 5401): TimaSignature is unavailable
,D/ActivityThread( 5401): Added TimaKeyStore provider
,I/ThumbnailProvider( 5401): ThumbnailProvider onCreate()
,I/DocumentBroadcastReceiver( 5401): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 5401): [START] processBroadcastIntent ...
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,I/dex2oat ( 5415): ----------------------------------------------------
I/dex2oat ( 5415): <SS>: S T A R T I N G . . .
I/dex2oat ( 5415): <SS>: going to process manifest for 32-bit...
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
I/        ( 5415): SS_ART_lib [I]: Memory allocation: ctx
I/        ( 5415): SS_ART_lib [I]: Memory allocation: manifest_buf
,I/        ( 5415): SS_ART_lib [I]: Parsing Manifest for SS stuff
I/        ( 5415): SS_ART_lib [I]: Memory allocation: ctx->libs
I/        ( 5415): SS_ART_lib [I]: Memory allocation: ctx->package_name
I/        ( 5415): SS_ART_lib [I]: Parsing completed
I/        ( 5415): SS_ART_lib [I]: permission is absent: /data/app/com.test.thalitest-1/base.apk
I/        ( 5415): SS_ART_lib [I]: Closing zip file: /data/app/com.test.thalitest-1/base.apk
I/        ( 5415): SS_ART_lib [I]: access to SS denied
I/        ( 5415): SS_ART_lib [I]: ctx will be cleaned
I/        ( 5415): SS_ART_lib [I]: ctx component will be cleaned: ctx->libs
I/        ( 5415): SS_ART_lib [I]: ctx component is cleaned: ctx->libs
I/        ( 5415): SS_ART_lib [I]: ctx component will be cleaned: ctx->package_name
I/        ( 5415): SS_ART_lib [I]: ctx component is cleaned: ctx->package_name
I/        ( 5415): SS_ART_lib [I]: ctx is cleaned
I/BroadcastProcessorService( 5401): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
I/dex2oat ( 5415): /system/bin/dex2oat --zip-fd=11 --zip-location=/data/app/com.test.thalitest-1/base.apk --oat-fd=12 --art-fd=-1 --oat-location=/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/GalleryCacheReady( 4980): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,I/SystemInfo( 5401): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 5401): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
,I/BroadcastProcessorService( 5401): [START] DocumentService startDocumentService
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,D/GalleryCacheReady( 4980): handleMeidaScanFinish()
,I/DocumentService( 5401): DocumentService onCreate ... service
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/FaceInterface( 4980): requestFaceScan() is called.
,W/LocalSuggestAlbumData( 4980): query fail: 
,W/LocalSuggestAlbumData( 4980): query fail: 
,I/FaceInterface( 4980): startFaceScan() : waiting 5 sec
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5401): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5401): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/SystemInfo( 5401): [SIOP LEVEL] : 0
,I/MediaStoreImporter( 4458): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/DocumentService( 5401): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5401): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/art     ( 1227): Explicit concurrent mark sweep GC freed 7059(484KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 703us total 23.752ms
,D/BluetoothMediaBrowser( 2621):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,E/File    ( 5401): fail readDirectory() errno=13
,E/File    ( 5401): fail readDirectory() errno=13
,D/BluetoothMediaBrowser( 2621): no now playing list
,D/BluetoothMediaBrowser( 2621):  getNowPlayingId now playing id : -1
,I/SystemInfo( 5401): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5401): [STOP DOCUMENTSERVICE] Attempting to stop the Service
,E/DocumentService( 5401): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :86
E/DocumentService( 5401): [THUMBNAIL] Total Time taken for each file :0
,E/        ( 5401): [INDEX] Total time taken for each file :0
,I/DocumentService( 5401): DocumentService onDestroy start
,I/DocumentService( 5401): DocumentService onDestroy end
,I/DocumentService( 5401): DocumentService cleanupEverything start
,I/IndexParserThreadsManager( 5401): InterruptedException: null
,I/SystemInfo( 5401): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5401): DocumentService cleanupEverything end
,I/Process ( 5401): Sending signal. PID: 5401 SIG: 9
,I/ActivityManager( 1015): Process com.samsung.indexservice (pid 5401)(adj 11) has died(75,1158)
,I/SettingSearch/SearchIntentReceiver( 1320): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1320): LOCALE_CHANGED call search setting db finish!!
,I/SettingSearch/SearchIntentReceiver( 1320): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/SettingSearch/SearchIntentReceiver( 1320): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1320): LOCALE_CHANGED call search setting db finish!!
,I/CalendarProvider2( 5340): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/dex2oat ( 5415): dex2oat took 484.063ms (threads: 4)
,I/PackageManager( 1015): do mInstaller.dexopt : 0
,D/PackageManager( 1015): Time to dexopt: 0.559 seconds
,W/System.err( 1015): java.io.FileNotFoundException: /data/app/com.test.thalitest-1: open failed: EISDIR (Is a directory)
,W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err( 1015): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 1015): 	at android.content.pm.PackageParser.getHashValueOfPackage(PackageParser.java:5140)
,W/System.err( 1015): 	at com.android.server.pm.PackageManagerService.saveHash(PackageManagerService.java:19520)
W/System.err( 1015): 	at com.android.server.pm.PackageManagerService.access$5400(PackageManagerService.java:342)
W/System.err( 1015): 	at com.android.server.pm.PackageManagerService$19.run(PackageManagerService.java:19505)
,W/System.err( 1015): Caused by: android.system.ErrnoException: open failed: EISDIR (Is a directory)
W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:446)
W/System.err( 1015): 	... 5 more
,I/HarmonyEASService( 1015): Updating for all 1
D/PackageManager( 1015): New package installed
,D/PackageManager( 1015): doPostInstall for uid{10155}
,D/PackageManager( 1015): token 1 to BM for possible restore
,V/BackupManagerService( 1015): restoreAtInstall pkg=com.test.thalitest token=1 restoreSet=0
V/BackupManagerService( 1015): Finishing install immediately
,D/PackageManager( 1015): BM finishing package install for 1
,D/PackageManager( 1015): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 1015): [MSG] MCS_UNBIND
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,I/PageBuddyNotiSvc( 4213): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 1454): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 5435): MountEmulatedStorage()
E/Zygote  ( 5435): v2
I/libpersona( 5435): KNOX_SDCARD checking this for 1000
I/libpersona( 5435): KNOX_SDCARD not a persona
,I/SELinux ( 5435): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5435): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1015): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=5435 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 5435): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PackageManager( 1015): [MSG] POST_INSTALL: observer{830230605}
D/PackageManager( 1015):           Handling post-install for 1
,I/ActivityManager( 1015): Killing 4747:com.qualcomm.timeservice/1000 (adj 15): empty #31
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 5435): TimaSignature is unavailable
,D/ActivityThread( 5435): Added TimaKeyStore provider
,W/Settings( 1015): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,D/RegisteredComponentCache( 1441): Collect Tech packages for Knox
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,D/AASAservice-UpdateReceiver( 5435): AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.google.android.gms, uid = -1
,E/SamsungIME( 1788): mOCRHelper is null
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,I/splitIntent( 1015): intent=android.intent.action.PACKAGE_CHANGED will be not split. because same process=com.google.android.googlequicksearchbox:search is in other queue. index=1
I/splitIntent( 1015): base  index=1, name=com.google.android.googlequicksearchbox com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher
I/splitIntent( 1015): other index=7, name=com.google.android.googlequicksearchbox com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_CHANGED !! do not split it!!
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 5453): MountEmulatedStorage(),
E/Zygote  ( 5453): v2
I/libpersona( 5453): KNOX_SDCARD checking this for 10057
I/libpersona( 5453): KNOX_SDCARD not a persona,
,I/SELinux ( 5453): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5453): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5453): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher: pid=5453 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 4780:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,D/PersonaManager( 1441): isKioskContainerExistOnDevice
,D/PersonaManager( 1441): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1441): empty dynamic service
,D/RegisteredComponentCache( 1441): Collect Tech packages for Knox
,D/PersonaManager( 1441): isKioskContainerExistOnDevice
,D/TimaKeyStoreProvider( 5453): TimaSignature is unavailable
,D/ActivityThread( 5453): Added TimaKeyStore provider
,D/PersonaManager( 1441): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1441): empty dynamic service
,I/FaceInterface( 4980): startFaceScan() : going on
,D/FaceInterface( 4980): startFaceScan() is called.
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,D/ContentApp( 1227): startScan() is called.
,D/FaceValue( 1227): mSleepTime: 800
,D/FaceValue( 1227): mMaxThreadNum: 2
,W/FaceValue( 1227): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,D/ContentApp( 1227): startScan() is end.
,D/ContentApp( 1227): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1227): isNeedToRestore : start
,W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 93688(5MB) AllocSpace objects, 10(2MB) LOS objects, 27% free, 41MB/57MB, paused 13.061ms total 333.625ms
,D/PackageManager( 1015): result of install: 1{830230605}
I/PackageManager( 1015): Observer no longer exists.
,W/IntentResolver( 1015): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1015): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService( 1015): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.backup.TRANSPORT_HOST
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1015): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/FaceInterface( 4980): startFaceScan() : going on
D/FaceInterface( 4980): startFaceScan() is called.
,D/ContentApp( 1227): startScan() is called.
,D/ContentApp( 1227): startScan() is end.
,D/ContentApp( 1227): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1227): isNeedToRestore : start
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/RCPManagerService( 1015): PackageReceiver onReceive()
D/RCPManagerService( 1015): App Installed with packageNAme = com.test.thalitest
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/RCPManagerService( 1015):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: Attempt to invoke virtual method 'java.lang.String android.os.Bundle.getString(java.lang.String)' on a null object reference
D/RCPManagerService( 1015):  PackageReceiver onReceive() bundle null
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/KnoxMUMContainerPolicy( 1015): mPackageReceiver : action - android.intent.action.PACKAGE_ADDED
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/BackupManagerService( 1015): Removing schedule queue dupe of com.test.thalitest
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_ADDED
V/EnterpriseBillingPolicy( 1015): uID is 10155
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
,D/PersonaPolicyManagerService( 1015): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,V/BackupManagerService( 1015): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 1015): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3a4156d7
,D/KnoxMUMContainerPolicy( 1015): packageInstalledForExternalStorage com.test.thalitest,
V/AlarmManagerEXT( 1015): com.test.thalitest(10155) is added to mUserAppList
,E/Zygote  ( 5473): MountEmulatedStorage(),
I/libpersona( 5473): KNOX_SDCARD checking this for 10015
E/Zygote  ( 5473): v2
I/libpersona( 5473): KNOX_SDCARD not a persona
,I/SELinux ( 5473): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5473 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
I/SELinux ( 5473): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5473): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,I/GCoreNlp( 1825): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationManagerService( 1015): getProviders()=[passive]
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/TimaKeyStoreProvider( 5473): TimaSignature is unavailable
,D/ActivityThread( 5473): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 4796:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,D/EnterpriseDeviceManagerService( 1015): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1015): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1015): no available spell checker services found
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/Babel   ( 5259): Creating RTCS
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/CrashAnrDetector( 1015): onPackageAdded : com.test.thalitest
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,E/Zygote  ( 5497): MountEmulatedStorage()
,E/Zygote  ( 5497): v2
I/libpersona( 5497): KNOX_SDCARD checking this for 10032
I/libpersona( 5497): KNOX_SDCARD not a persona
,I/SELinux ( 5497): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5497): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5497): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5497 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/LocationProviderProxy( 1015): applying state to connected service
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4747/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1015): applying state to connected service
W/libprocessgroup( 1015): failed to open /acct/uid_10085/pid_4780/cgroup.procs: No such file or directory
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,W/libprocessgroup( 1015): failed to open /acct/uid_10094/pid_4796/cgroup.procs: No such file or directory
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/TimaKeyStoreProvider( 5497): TimaSignature is unavailable
,D/ActivityThread( 5497): Added TimaKeyStore provider
,I/Babel   ( 5259): Destroying RTCS
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,I/ActivityManager( 1015): Killing 4855:com.wsomacp/u0a25 (adj 15): empty #31
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,I/GCoreNlp( 1825): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/FeatureConfig( 5497): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/ActivityManager( 1015): Killing 4876:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/PackagesMonitor( 4980): PackagesMonitor onReceive :com.google.android.gms
,D/LocationProviderProxy( 1015): applying state to connected service
,W/ResourcesManager( 5497): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5497): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 5497): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5497): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/UpdateIcingCorporaServi( 5453): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/ResourcesManager( 5497): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 5516): MountEmulatedStorage()
,E/Zygote  ( 5516): v2
I/libpersona( 5516): KNOX_SDCARD checking this for 10069
I/libpersona( 5516): KNOX_SDCARD not a persona
I/SELinux ( 5516): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5516 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5516): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5516): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/ResourcesManager( 5497): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 5497): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 5497): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 5497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5516): TimaSignature is unavailable
,D/ActivityThread( 5516): Added TimaKeyStore provider
,W/ResourcesManager( 5497): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5497): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/FileShare-Server( 5516): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,W/ResourcesManager( 5497): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1015): failed to open /acct/uid_10025/pid_4855/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10003/pid_4876/cgroup.procs: No such file or directory
,E/Zygote  ( 5531): MountEmulatedStorage()
,E/Zygote  ( 5531): v2
I/libpersona( 5531): KNOX_SDCARD checking this for 1000
I/libpersona( 5531): KNOX_SDCARD not a persona
,I/SELinux ( 5531): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5531 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5531): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5531): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 5497): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     (  304): Explicit concurrent mark sweep GC freed 8724(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 647us total 20.929ms
,W/ResourcesManager( 5497): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5531): TimaSignature is unavailable
I/UpdateIcingCorporaServi( 5453): UpdateCorporaTask done [took 115 ms] updated apps [took 115 ms] 
D/ActivityThread( 5531): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 4893:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,W/ResourcesManager( 5497): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 649us total 17.331ms
W/ResourcesManager( 5497): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5531): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5497): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 17.030ms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,W/GalaxyFinderApplication( 5497): system/finder_cp/cpdata.xml file not found
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5547): MountEmulatedStorage(),
E/Zygote  ( 5547): v2
I/libpersona( 5547): KNOX_SDCARD checking this for 1000
I/libpersona( 5547): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=5547 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/ActivityManager( 1015): Killing 5008:com.sec.smartcard.manager/u0a153 (adj 15): empty #31
,I/SELinux ( 5547): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5547): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5547): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5547): TimaSignature is unavailable
,D/ActivityThread( 5547): Added TimaKeyStore provider
,D/KnoxSetupWizardDbHelper( 5547): dbMigrationFlag : false
,D/ShortcutReceiver( 5547):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5563): MountEmulatedStorage()
,E/Zygote  ( 5563): v2
I/libpersona( 5563): KNOX_SDCARD checking this for 10120
I/libpersona( 5563): KNOX_SDCARD not a persona
,I/SELinux ( 5563): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5563 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 5563): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5563): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 4731:com.android.mms/u0a46 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5563): TimaSignature is unavailable
,D/ActivityThread( 5563): Added TimaKeyStore provider
,W/ResourcesManager( 5563): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CountryDetector( 1015): No listener is left
,W/libprocessgroup( 1015): failed to open /acct/uid_10107/pid_4893/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10153/pid_5008/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10046/pid_4731/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5583): MountEmulatedStorage(),
,E/Zygote  ( 5583): v2
I/libpersona( 5583): KNOX_SDCARD checking this for 10028
I/libpersona( 5583): KNOX_SDCARD not a persona
I/SELinux ( 5583): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5583 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 5583): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5583): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5583): TimaSignature is unavailable
,D/ActivityThread( 5583): Added TimaKeyStore provider
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1015): Killing 5054:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5054/cgroup.procs: No such file or directory
,I/GAV2    ( 5138): Thread[GAThread,5,main]: No campaign data found.
,D/Finsky  ( 5583): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/Finsky  ( 5583): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5583): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5583): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 5583): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5583): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5583): Skipping gmscore version check
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/PackageBroadcastService( 2006): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5583): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/HomeSyncInstallReceiver( 1441): This pkg do not need BT addr. Do nothing
,I/PackageBroadcastService( 2006): Null package name or gms related package.  Ignoreing.
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1015): Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=14, mSplitNum[1]=23, mSplitNum[2]=36, mBgSplitQueueNum=3 divideNum= 11 r.nextReceiver= 2 receivers.size=47
,D/Finsky  ( 5583): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/splitIntent( 1015): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,D/AASAservice-UpdateReceiver( 5435): AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
,I/AASAservice-TokenRule( 5435): parseToken()
,W/System.err( 5435): java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
W/System.err( 5435): 	at libcore.io.IoBridge.open(IoBridge.java:456)
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/System.err( 5435): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 5435): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/System.err( 5435): 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:80)
W/System.err( 5435): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:52)
W/System.err( 5435): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 5435): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 5435): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 5435): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5435): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5435): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 5435): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5435): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5435): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5435): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 5435): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 5435): 	at libcore.io.Posix.open(Native Method)
W/System.err( 5435): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 5435): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 5435): 	... 14 more
E/AASAservice-TokenRule( 5435): parseToken() : TokenFile is null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
E/AASAservice-UpdateReceiver( 5435): AASARuleUpdateResult() : Rule file is not exist.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PackagesMonitor( 4980): PackagesMonitor onReceive :com.test.thalitest
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5633): MountEmulatedStorage()
,E/Zygote  ( 5633): v2
,I/libpersona( 5633): KNOX_SDCARD checking this for 10152
I/libpersona( 5633): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5633 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a,
I/SELinux ( 5633): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5633): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5633): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5649): MountEmulatedStorage(),
E/Zygote  ( 5649): v2
I/libpersona( 5649): KNOX_SDCARD checking this for 10046
I/libpersona( 5649): KNOX_SDCARD not a persona
I/SELinux ( 5649): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,D/TimaKeyStoreProvider( 5633): TimaSignature is unavailable,
I/SELinux ( 5649): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityThread( 5633): Added TimaKeyStore provider
,I/ActivityManager( 1015): Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=5649 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/SELinux ( 5649): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/art     ( 1629): Explicit concurrent mark sweep GC freed 4760(199KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 744us total 25.951ms
,E/Zygote  ( 5670): MountEmulatedStorage()
,E/Zygote  ( 5670): v2
,I/libpersona( 5670): KNOX_SDCARD checking this for 1000
I/libpersona( 5670): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5670 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 5670): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5670): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5670): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5649): TimaSignature is unavailable
,D/ActivityThread( 5649): Added TimaKeyStore provider
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 5103): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/SQLiteLog( 5633): (284) automatic index on shooting_modes(title_id)
,D/TimaKeyStoreProvider( 5670): TimaSignature is unavailable
,D/ActivityThread( 5670): Added TimaKeyStore provider
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5649): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5649): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5649): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5649): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5649): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5649): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 5688): MountEmulatedStorage(),
I/libpersona( 5688): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5688): v2
I/libpersona( 5688): KNOX_SDCARD not a persona
I/SELinux ( 5688): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5688 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5688): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5688): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5706): MountEmulatedStorage()
E/Zygote  ( 5706): v2
I/libpersona( 5706): KNOX_SDCARD checking this for 10156
I/libpersona( 5706): KNOX_SDCARD not a persona
,D/TimaKeyStoreProvider( 5688): TimaSignature is unavailable
,D/ActivityThread( 5688): Added TimaKeyStore provider
I/SELinux ( 5706): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5706): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5706 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,E/SELinux ( 5706): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 5073:com.samsung.android.app.powersharing/u0a122 (adj 15): empty #31
,D/Mms/MmsApp( 5649): [start]    onCreate() consume time = 0.0,
,D/TimaKeyStoreProvider( 5706): TimaSignature is unavailable
,D/ActivityThread( 5706): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_LOG( 5670): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5670): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5670): new DMDBOpenHelper instance
,W/ResourcesManager( 5688): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,I/PCWCLIENTTRACE_PushUtil( 5670): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5670): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5670): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5670): [onReceive] - android.intent.action.PACKAGE_ADDED
,I/Icing   ( 2006): Storage manager: low false usage 1.75MB avail 10.16GB capacity 11.68GB
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,I/TapandpayWidget:TapandpayAppWidgetProvider( 5706): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 5706): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/TapandpayWidget:Utils( 5706): Clear T&P info.
,E/Zygote  ( 5722): MountEmulatedStorage()
E/Zygote  ( 5722): v2
I/libpersona( 5722): KNOX_SDCARD checking this for 1000
I/libpersona( 5722): KNOX_SDCARD not a persona
,I/SELinux ( 5722): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5722): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5722): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=5722 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 5181:com.sec.android.app.sns3/u0a33 (adj 15): empty #31
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5722): TimaSignature is unavailable
,D/ActivityThread( 5722): Added TimaKeyStore provider
,E/Zygote  ( 5739): MountEmulatedStorage()
E/Zygote  ( 5739): v2
I/libpersona( 5739): KNOX_SDCARD checking this for 10091
I/libpersona( 5739): KNOX_SDCARD not a persona
I/SELinux ( 5739): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5739): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5739 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5739): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5706): Widget is not attached.
,I/ActivityManager( 1015): Killing 3972:com.sec.spp.push/u0a35 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5739): TimaSignature is unavailable
,D/ActivityThread( 5739): Added TimaKeyStore provider
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 5583): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,W/libprocessgroup( 1015): failed to open /acct/uid_10122/pid_5073/cgroup.procs: No such file or directory
,W/art     ( 5649): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 138.182ms
E/Zygote  ( 5756): MountEmulatedStorage()
E/Zygote  ( 5756): v2
I/libpersona( 5756): KNOX_SDCARD checking this for 10010
I/libpersona( 5756): KNOX_SDCARD not a persona
,I/SELinux ( 5756): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5756): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5756): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5756 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 5214:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31
,I/art     (  304): Explicit concurrent mark sweep GC freed 8747(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 22.088ms
,D/TimaKeyStoreProvider( 5756): TimaSignature is unavailable
,D/ActivityThread( 5756): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 19.276ms
,I/DBG_POLICYDM( 5722): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 5722): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,W/libprocessgroup( 1015): failed to open /acct/uid_10033/pid_5181/cgroup.procs: No such file or directory
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 643us total 17.884ms
,W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_5214/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_3972/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5722): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 5722): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 5722): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 5722): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/art     ( 5649): Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 113.738ms
,D/Mms/ArtClassLoader( 5649): init before art
,D/Mms/TelephonyPermission( 5649): start operation mode monitor
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5722): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 5722): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 5722): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,W/ResourcesManager( 5649): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5722): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,D/PackageBroadcastService( 2006): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/DBG_POLICYDM( 5722): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,E/PhotosPlugin( 5739): Loading PhotosPlugin
,I/DBG_POLICYDM( 5722): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5722): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 5722): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 5722): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 5722): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 5722): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 5722): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 5722): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5722): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/02/16/12:12:08
,I/DBG_POLICYDM( 5722): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/02/09/14:05:53
,I/DBG_POLICYDM( 5722): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 5722): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{1fe24209 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5722): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 5722): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 5722): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 5722): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 5722): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 5722): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,I/DBG_POLICYDM( 5722): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 203916(13MB) AllocSpace objects, 4(3MB) LOS objects, 33% free, 27MB/40MB, paused 2.967ms total 245.049ms
,I/DBG_POLICYDM( 5722): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/ChimeraCfgMgr( 2006): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2006): Loading module APK com.google.android.play.games
,I/DBG_POLICYDM( 5722): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,D/Mms/TelephonyPermission( 5649): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 5649): isDefault true
,D/Mms/MmsApp( 5649): onCreate() com.android.mms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,E/Zygote  ( 5783): MountEmulatedStorage(),
E/Zygote  ( 5783): v2
I/libpersona( 5783): KNOX_SDCARD checking this for 10035
I/libpersona( 5783): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5783 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 5234:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
I/SELinux ( 5783): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SELinux ( 5783): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
E/SELinux ( 5783): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5783): TimaSignature is unavailable
,D/ActivityThread( 5783): Added TimaKeyStore provider
,D/Mms/MmsApp( 5649): [start]    initCountryIso consume time = 704.689895
,D/CountryDetector( 1015): The first listener is added
,I/DBG_POLICYDM( 5722): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,D/Mms/MmsApp( 5649): [end]    initCountryIso consume time = 10.428542
D/Mms/MmsConfig( 5649): [start]    MmsConfig.init() consume time = 0.189011
,I/DBG_POLICYDM( 5722): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/Mms/MmsConfig( 5649): before partial update
,D/Mms/ArtClassLoader( 5649): init [DONE] art
,D/Mms/MmsConfig( 5649): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 5649): serviceId : 1, features : -1
,E/SPPClientService( 5783): ============PushLog. commonIsShipBuild. stop!
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/SPPClientService( 5783): [PushClientApplication] Push log off : This is Ship build version
,E/Zygote  ( 5805): MountEmulatedStorage()
,E/Zygote  ( 5805): v2
I/libpersona( 5805): KNOX_SDCARD checking this for 10038
I/libpersona( 5805): KNOX_SDCARD not a persona
,I/SELinux ( 5805): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1015): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5805 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,D/EasySignUpManager_1.0.1( 5649): isAuth is false,
D/Mms/MmsConfig( 5649): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,I/SELinux ( 5805): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5805): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_5234/cgroup.procs: No such file or directory
,D/TP/MmsSmsProvider( 1454): query,matched:2117, calling pid = 5649
D/SPPClientService( 5783): PushLog.txt file is not deleted.
D/SPPClientService( 5783): PushLog.txt file is not deleted.
D/SPPClientService( 5783): ============PushLog. stop!
D/TP/MmsSmsProvider( 1454): match 2117:Elapsed time : 0.842 ms
,D/TimaKeyStoreProvider( 5805): TimaSignature is unavailable
,D/ActivityThread( 5805): Added TimaKeyStore provider
,D/EasySignUpManager_1.0.1( 5649): isAuth is false
D/EasySignUpManager_1.0.1( 5649): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 5649): mps_code.dat does not exist
E/CscParser( 5649): customer_path =/system/csc/customer.xml
E/CscParser( 5649): fileName + /system/csc/customer.xml
,W/ResourcesManager( 5805): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5805): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/CscParser( 5649): mps_code.dat does not exist
E/CscParser( 5649): customer_path =/system/csc/customer.xml
E/CscParser( 5649): fileName + /system/csc/customer.xml
,D/CscParser( 5649): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 5649):  enable multiwindow = true
,E/Mms/MessageUtils( 5649): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5649): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 5649): [end]    init() consume time = 152.405104
,D/Mms/Contact( 5649): [start]    init() consume time = 1.082812
,D/Mms/Contact( 5649): [end]    init consume time = 9.964167
,D/TP/MmsSmsProvider( 1454): query,matched:13, calling pid = 5649
,D/TP/MmsSmsProvider( 1454): match 13:Elapsed time : 0.994 ms
,D/Mms/DraftCache( 5649): [start]    rebuildCache consume time = 14.073125
,D/TP/MmsSmsProvider( 1454): query,matched:12, calling pid = 5649
,D/Mms/MethodReflector( 5649): getSubId is called
D/Mms/TelephonyUtils( 5649): getLongSubId from simSlot 0, return Value = -1
,D/TP/MmsSmsProvider( 1454): match 12:Elapsed time : 2.782 ms
,D/Mms/DraftCache( 5649): [end]    rebuildCache consume time = 13.171406
,D/Mms/MethodReflector( 5649): getTelephonyProperty is called
D/Mms/DownloadManager( 5649): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5649): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5649): auto download without roaming -> true
D/Mms/DownloadManager( 5649): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5649): getSubId is called
,D/Mms/MethodReflector( 5649): getDefaultSmsSubId is called
,E/Mms/TelephonyUtils( 5649): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5649): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5649): getTelephonyProperty is called
,D/Mms/DownloadManager( 5649): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5649): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5649): auto download without roaming -> true
D/Mms/DownloadManager( 5649): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
,D/Mms/DownloadManager( 5649): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5649): mAutoDownload ------> true
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,I/Icing   ( 2006): updateResources: need to parse f{com.google.android.gms}
,D/ComposerPerformance( 5649): 1455023154309 ms / [DONE] Composer constructor
,E/CII     ( 5649): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 5649): ReservationManager()
,I/Mms/ReservationManager( 5649): resetAfterConnected()
,D/TP/MmsSmsProvider( 1454): query,matched:7, calling pid = 5649
,D/TP/MmsSmsProvider( 1454): match 7:Elapsed time : 1.499 ms
,D/Mms/Conversation( 5649): [start]    init() consume time = 68.894844
,I/Mms/ReservationManager( 5649): getReservedSendMessageCount(): retMessageCount=0
,D/TP/MmsSmsProvider( 1454): deleteConversation threadId: 9223372036854775807
,D/Mms/MmsApp( 5649): [end]    onCreate() consume time = 5.149583
,D/TP/MmsSmsProvider( 1454): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1454): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1454): sUpgradeVersion = 0, db.getVersion() = 81
,D/TP/MmsSmsProvider( 1454): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1454): need read changed broadcast:false
,D/Mms/Conversation( 5649): [end]    init consume time = 10.875417
,D/Mms/MessagingNotification( 5649): [start]    init() consume time = 3.782656
,D/Mms/MessagingNotification( 5649): [end]    init consume time = 3.045625
,D/Mms/DownloadManager( 5649): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 5649): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 5649): getSubId is called
D/Mms/TelephonyUtils( 5649): getLongSubId from simSlot 0, return Value = -1
,D/TP/MmsSmsProvider( 1454): query,matched:0, calling pid = 5649
,V/TP/MmsSmsProvider( 1454): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1454): match 0:Elapsed time : 1.487 ms
,D/Mms/MethodReflector( 5649): getTelephonyProperty is called
D/Mms/DownloadManager( 5649): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5649): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5649): auto download without roaming -> true
D/Mms/DownloadManager( 5649): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5649): mAutoDownload ------> true
,D/Mms/Synchronizer( 5649): [start]    doSync consume time = 16.28349
,D/Mms/SpamFilter( 5649): [start]    SpamFilter fill() begin consume time = 1.733906
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,D/TP/MmsSmsProvider( 1454): update, matched:300, calling pid = 5649
V/TP/MmsSmsProvider( 1454): syncDBData start
,V/TP/MmsSmsProvider( 1454): syncDBData sms end
,D/TP/MmsSmsProvider( 1454): query,matched:400, calling pid = 5649
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/Mms/FreeMessageStatusReceiver( 5649): onReceive, action : android.intent.action.PACKAGE_ADDED
,V/TP/MmsSmsProvider( 1454): syncDBData mms end
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,V/TP/MmsSmsProvider( 1454): syncDBData end
,E/Zygote  ( 5833): MountEmulatedStorage()
E/Zygote  ( 5833): v2
I/libpersona( 5833): KNOX_SDCARD checking this for 10072
I/libpersona( 5833): KNOX_SDCARD not a persona
,I/SELinux ( 5833): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5833 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/ActivityManager( 1015): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/Mms/Synchronizer( 5649): [end]    doSync consume time = 29.761927
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
I/SELinux ( 5833): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5833): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5833): TimaSignature is unavailable
,D/ActivityThread( 5833): Added TimaKeyStore provider
,D/Mms/FreeMessageReceiverService( 5649): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5649): onHandleIntent: ACTION_PACKAGE_ADDED
E/Zygote  ( 5849): MountEmulatedStorage()
I/libpersona( 5849): KNOX_SDCARD checking this for 10047
E/Zygote  ( 5849): v2
I/libpersona( 5849): KNOX_SDCARD not a persona
,I/SELinux ( 5849): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5849): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5849): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5849 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 5325:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 5284:com.sec.android.diagmonagent/1000 (adj 15): empty #32
,D/Mms/SpamFilter( 5649): [end]    SpamFilter fill() finished consume time = 62.037812
,D/TimaKeyStoreProvider( 5849): TimaSignature is unavailable
,D/ActivityThread( 5849): Added TimaKeyStore provider
,D/BadgeProvider( 5833): onCreate
,D/ChimeraCfgMgr( 2006): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2006): Module APK com.google.android.play.games already loaded
,D/BadgeProvider( 5833): DatabaseHelper
,W/ResourcesManager( 5849): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5849): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5849): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5284/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10142/pid_5325/cgroup.procs: No such file or directory
,D/Mms/MessagingNotification( 5649): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1454): query,matched:26, calling pid = 5649
,D/ChimeraCfgMgr( 2006): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/TP/SmsProvider( 1454): match 26:Elapsed time : 1.827 ms
,D/AsyncTaskServiceImpl( 2006): Submit a task: k
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsSmsProvider( 1454): query,matched:6, calling pid = 5649
,D/TP/MmsSmsProvider( 1454): match 6:Elapsed time : 1.505 ms
,I/ActivityManager( 1015): Killing 5340:com.android.providers.calendar/u0a42 (adj 15): empty #31
,D/ChimeraCfgMgr( 2006): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5868 uid=10025 gids={50025, 9997} abi=armeabi-v7a,
,E/Zygote  ( 5868): MountEmulatedStorage()
E/Zygote  ( 5868): v2
I/libpersona( 5868): KNOX_SDCARD checking this for 10025
I/libpersona( 5868): KNOX_SDCARD not a persona
,I/SELinux ( 5868): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5868): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5868): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1015): failed to open /acct/uid_10042/pid_5340/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5868): TimaSignature is unavailable
,D/ActivityThread( 5868): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 5118:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/ChimeraCfgMgr( 2006): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 2006): Processing package: com.test.thalitest
,W/ResourcesManager( 5868): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/OMACP   ( 5868): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,W/libprocessgroup( 1015): failed to open /acct/uid_10150/pid_5118/cgroup.procs: No such file or directory
,D/MyFiles ( 5849): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,D/Mms/Omacp( 5649): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,I/TactileAssist( 1015): enable value -1
,I/TactileAssist( 1015): internal enable value -1
I/TactileAssist( 1015): intensity value -1
I/TactileAssist( 1015): saveAppList value true
,I/TactileAssist( 1015): List of disabled apps :
,E/installd(  283): system dir 0 : /system/app/
E/installd(  283): system dir 1 : /system/priv-app/
E/installd(  283): system dir 2 : /vendor/app/
E/installd(  283): system dir 3 : /oem/app/
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/OMACP   ( 5868): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5868): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
D/GassUtils( 2006): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 2006): Found info for package com.test.thalitest in db.
,I/OMACP   ( 5868): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,D/PackageManager( 1015): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,I/OMACP   ( 5868): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 5868): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 5868): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false,
I/OMACP   ( 5868): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
E/Zygote  ( 5890): MountEmulatedStorage()
E/Zygote  ( 5890): v2
I/libpersona( 5890): KNOX_SDCARD checking this for 10053
I/OMACP   ( 5868): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/libpersona( 5890): KNOX_SDCARD not a persona
,I/SELinux ( 5890): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/OMACP   ( 5868): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5868): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 5868): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/ActivityManager( 1015): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5890 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 5890): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5890): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/OMACP   ( 5868): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5868): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/TimaKeyStoreProvider( 5890): TimaSignature is unavailable
,D/ActivityThread( 5890): Added TimaKeyStore provider
,W/BaseAppContext( 2006): Using Auth Proxy for data requests.
W/BaseAppContext( 2006): Using Auth Proxy for data requests.
,W/ResourcesManager( 5890): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/Compatibility( 5890): onReceive() it will make start service
,D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/Compatibility( 5890): onHandleIntent()
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
D/Compatibility( 5890): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Compatibility( 5890): found: 2
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/UpdateIcingCorporaServi( 5453): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/SL_DEBUG( 5805): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 5805): isLoggable:: SL_DEBUG_EXIST = false
,D/Compatibility( 5890): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5890): skipping ResolveInfo{acb4b88 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5890): considering ResolveInfo{3cc2c921 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5890): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5890): enabling receiver ResolveInfo{28bde146 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5890): enabling receiver ResolveInfo{35a06f07 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,W/BaseAppContext( 2006): Using Auth Proxy for data requests.
,D/Compatibility( 5890): enabling receiver ResolveInfo{1d8d9834 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5890): enabling receiver ResolveInfo{25e1d65d com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5890): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,I/PeopleDatabaseHelper( 2006): cleanUpNonGplusAccounts done.
,E/SMD     (  287): DCD OFF
,W/BaseAppContext( 2006): Using Auth Proxy for data requests.
,W/BaseAppContext( 2006): Using Auth Proxy for data requests.
W/BaseAppContext( 2006): Using Auth Proxy for data requests.
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 4
,W/BaseAppContext( 2006): Using Auth Proxy for data requests.
,I/UpdateIcingCorporaServi( 5453): UpdateCorporaTask done [took 104 ms] updated apps [took 104 ms] 
,W/art     ( 5739): Suspending all threads took: 6.636ms
,I/ActivityManager( 1015): Killing 5138:com.google.android.gm/u0a101 (adj 15): empty #31
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5805): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5805): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1015): failed to open /acct/uid_10101/pid_5138/cgroup.procs: No such file or directory
,E/Zygote  ( 5921): MountEmulatedStorage()
I/libpersona( 5921): KNOX_SDCARD checking this for 10041
E/Zygote  ( 5921): v2
I/libpersona( 5921): KNOX_SDCARD not a persona
I/SELinux ( 5921): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5921): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5921): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5921 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GAV2    ( 5739): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TimaKeyStoreProvider( 5921): TimaSignature is unavailable
,D/ActivityThread( 5921): Added TimaKeyStore provider
,I/Icing   ( 2006): Internal init done: storage state 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Icing   ( 2006): Post-init done
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,I/Icing   ( 2006): updateResources: need to parse f{com.google.android.gms}
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 5921): [SSP] onCreated
,I/ActivityManager( 1015): Killing 4964:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,I/SA      ( 5921): [TPM] There is no property file
,I/SA      ( 5921): [SCU] isHaveSA() - false
,I/SA      ( 5921): [TPM] getModelProperty : null
I/SA      ( 5921): [TPM] getCSCProperty : null
,I/SA      ( 5921): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5921): [DM] PRODUCT AMOLED FEATURE: false
,I/SA      ( 5921): [DM] TFT FEATURE: false
,I/SA      ( 5921): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 5921): [DM] init START
,I/SA      ( 5921): [DM] This device is not a Vodafone
,W/ResourceType( 5921): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 5921): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 5921): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 5921): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 5921): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 5921): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 5921): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 5921): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 5921): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 5921): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 5921): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 5921): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 5921): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 5921): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 5921): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 5921): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 5921): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 5921): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 5921): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 5921): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 5921): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5921): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 5921): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 5921): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 5921): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 5921): [SCU] isHaveSA() - false
I/SA      ( 5921): support phone number id : false
I/SA      ( 5921): [DM] Supports Ref Jpn : true
,I/SA      ( 5921): [DM] init END
I/SA      ( 5921): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 5921): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
,I/ActivityManager( 1015): Killing 4458:com.google.android.music:main/u0a111 (adj 15): empty #31
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/GAV2    ( 5739): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/libprocessgroup( 1015): failed to open /acct/uid_10040/pid_4964/cgroup.procs: No such file or directory
,E/Zygote  ( 5953): MountEmulatedStorage(),
I/libpersona( 5953): KNOX_SDCARD checking this for 10100
E/Zygote  ( 5953): v2
I/libpersona( 5953): KNOX_SDCARD not a persona
I/SELinux ( 5953): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5953): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1015): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5953 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/SELinux ( 5953): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 5953): TimaSignature is unavailable
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 5953): Added TimaKeyStore provider
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1015): failed to open /acct/uid_10111/pid_4458/cgroup.procs: No such file or directory
,D/PackageIntentReceiver( 5953): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5953): Not GearManger package! 
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5972): MountEmulatedStorage()
,E/Zygote  ( 5972): v2
I/libpersona( 5972): KNOX_SDCARD checking this for 1000
I/libpersona( 5972): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5972 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 5972): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Killing 4813:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/SELinux ( 5972): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5972): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1825): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 5972): TimaSignature is unavailable
,D/ActivityThread( 5972): Added TimaKeyStore provider
,W/AccountFeatureHelper( 5739): Write apps_features disabled false
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,W/libprocessgroup( 1015): failed to open /acct/uid_10134/pid_4813/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5988 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 5301:com.android.calendar/u0a135 (adj 15): empty #31
,E/Zygote  ( 5988): MountEmulatedStorage()
E/Zygote  ( 5988): v2
I/libpersona( 5988): KNOX_SDCARD checking this for 1000
I/libpersona( 5988): KNOX_SDCARD not a persona
,I/SELinux ( 5988): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5988): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5988): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5988): TimaSignature is unavailable
,D/ActivityThread( 5988): Added TimaKeyStore provider
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,D/AcmsPackageEventListener( 5988): Received: android.intent.action.PACKAGE_ADDED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,W/ContextImpl( 5988): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,I/FaceInterface( 4980): startFaceScan() : going on
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/FaceInterface( 4980): startFaceScan() is called.,
,D/ContentApp( 1227): startScan() is called.,
D/ContentApp( 1227): startScan() is end.
D/ContentApp( 1227): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1227): isNeedToRestore : start
,D/AcmsService( 5988): Enter Oncreate
,D/AcmsServiceMonitor( 5988): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsService( 5988): creating AcmsCore
,W/GAV2    ( 5739): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/AcmsCore( 5988): AcmsCore.getAcmsCore() - Enter
,D/AcmsCore( 5988): AcmsCore
,D/AcmsCore( 5988): init
D/AcmsCore( 5988): Looper handler is not null
D/AcmsCore( 5988): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5988): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5988): Incrementing - Counter value: 1
D/AcmsCore( 5988): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 5988): onStartCommand
D/AcmsService( 5988): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 5988): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 5988): Incrementing - Counter value: 2
D/AcmsService( 5988): Incremented Counter Value : onStartCommand
,D/AcmsCertificateMngr( 5988): AcmsCertificateMngr
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityThread( 5988): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsRevocationMngr( 5988): AcmsRevocationMngr
,W/SQLiteConnectionPool( 2006): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/AcmsService( 5988): Inside handle Intent
D/AcmsService( 5988): App added - package name: com.test.thalitest
D/AcmsCore( 5988): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5988): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5988): Incrementing - Counter value: 3
D/AcmsCore( 5988): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 5988): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 5988): Decrementing - Counter value: 2
,I/splitIntent( 1015): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1015): Killing 5259:com.google.android.talk/u0a104 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10135/pid_5301/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2006): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2006): Module APK com.google.android.play.games already loaded
,W/libprocessgroup( 1015): failed to open /acct/uid_10104/pid_5259/cgroup.procs: No such file or directory
,I/Mms/MmsApp( 5649):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5649): [start]    fillCache consume time = 1873.029687
,D/Mms/ComposeMessageFragment( 5649): fillCache, easy = false
,V/AlarmManager( 1015): waitForAlarm result :4
,D/AbsListView( 5649): Get MotionRecognitionManager
,D/MotionRecognitionService( 1015):  ssp status : false
,D/Mms/ComposeMessageFragment( 5649): [end]    fillCache consume time = 73.666146
,I/Icing   ( 2006): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,D/Mms/BubbleViewCache( 5649): fillCache bubble = 1
,D/Icing   ( 2006): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2006): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 5516:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10069/pid_5516/cgroup.procs: No such file or directory
,I/CheckinService( 2006): Done disabling old GoogleServicesFramework version
,I/DBG_POLICYDM( 5722): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/SensorService( 1015): [SO] 0.019 0.077 10.094
,D/SSRM:n  ( 1015): SIOP:: AP = 400
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/AcmsKeyStoreHelper( 5988):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 5988): Key Store exist
,I/AcmsKeyStoreHelper( 5988): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 5988):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5988): getKeyStoreForApplication success 
D/AcmsCore( 5988): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5988): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5988): Decrementing - Counter value: 1
D/AcmsCore( 5988): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5988): This is NOT a valid MirrorLink app
D/AcmsCore( 5988): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5988): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5988): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5988): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5988): getSvcCounter - Counter value: 0
,D/AcmsService( 5988): Enter onDestroy
I/AcmsService( 5988): cleanUp(): inside service clean up
D/AcmsCore( 5988): AcmsCore: inside DeInit
,D/AcmsCore( 5988): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5988): AcmsCertificateMngr: inside cleanup
,D/AcmsRevocationMngr( 5988): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5988): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5988): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 5988): getSvcCounter - Counter value: 0
,D/AcmsService( 5988): killing acms process
I/Process ( 5988): Sending signal. PID: 5988 SIG: 9
,I/ActivityManager( 1015): Process ACMS.Process (pid 5988)(adj 0) has died(84,1186)
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/AlarmManager( 1015): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/accuweather( 1724): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
D/accuweather( 1724): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1724): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1724): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1724): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1724): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1724): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1724): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1724): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1724): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 14 06
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 29302(1616KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/40MB, paused 2.396ms total 144.873ms
,I/iu.UploadsManager( 2006): End new media; added: 0, uploading: 0, time: 198 ms
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  287): DCD OFF
,D/PackageManager( 1015): [MSG] MCS_UNBIND
,I/ActivityManager( 1015): Killing 5547:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5547/cgroup.procs: No such file or directory
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{24215c92 u0 com.samsung.android.MtpApplication/.MtpService}
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 350,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SensorService( 1015): [SO] 0.019 0.057 10.036,
,V/AlarmManager( 1015): waitForAlarm result :4,
D/lights  ( 1015): lcd : 1 +
D/PowerManagerService( 1015): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1015): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1015): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
D/PowerManagerService( 1015): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1015): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1015): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0,
,D/Finsky  ( 5583): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/lights  ( 1015): lcd : 1 -
,D/DisplayPowerController( 1015): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1015): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1825): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1825): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1825): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5583): Thread-963(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{188aac6d u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/System.out( 5583): Thread-963(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5583): Thread-963(ApacheHTTPLog):isShipBuild true
,I/System.out( 5583): Thread-963(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 5583): Thread-963(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10028
,I/qtaguid ( 5583): Tagging socket 44 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5583, getuid(): 10028
,I/qtaguid ( 5583): Tagging socket 48 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5583, getuid(): 10028
,D/Finsky  ( 5583): [975] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5583): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qtaguid ( 5583): Untagging socket 44
,I/System.out( 5583): Thread-963 calls detatch()
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1825): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5583): Thread-962(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5583): Thread-962(ApacheHTTPLog):isShipBuild true
I/System.out( 5583): Thread-962(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5583): Thread-962(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5583): Untagging socket 44
I/qtaguid ( 5583): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5583): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5583): untagSocket(44) failed with errno -22
I/System.out( 5583): Thread-962 calls detatch()
,D/Finsky  ( 5583): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1825): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6027): MountEmulatedStorage()
,E/Zygote  ( 6027): v2
I/libpersona( 6027): KNOX_SDCARD checking this for 10012
I/libpersona( 6027): KNOX_SDCARD not a persona
,I/SELinux ( 6027): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1015): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6027 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 6027): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6027): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/art     (  304): Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 662us total 20.483ms
,D/TimaKeyStoreProvider( 6027): TimaSignature is unavailable
D/ActivityThread( 6027): Added TimaKeyStore provider
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 745us total 20.112ms
,I/System.out( 5583): Thread-963(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5583): Thread-963(ApacheHTTPLog):isShipBuild true
I/System.out( 5583): Thread-963(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5583): Thread-963(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/ResourcesManager( 6027): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6027): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 17.921ms
,I/MultiDex( 6027): VM with version 2.1.0 has multidex support,
I/MultiDex( 6027): install
I/MultiDex( 6027): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6027): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 5583): Untagging socket 44
,I/qtaguid ( 5583): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5583): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5583): untagSocket(44) failed with errno -22
I/System.out( 5583): Thread-963 calls detatch()
,W/ActivityThread( 6027): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6027): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@862bd2e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6027): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1015): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1015): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1015): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6027): Reading stored module config
,D/WearableService( 1825): callingUid 10012, callindPid: 1825
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/MDM     ( 1825): [252] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null},
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1825): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 6027): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/LocationInitializer( 2006): Restart initialization of location
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1825): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1825): No location to return for getLastLocation()
,W/FusedLocationProvider( 1825): location=null
,D/NativeLibraryUtils( 6027): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6027): Connecting to CarCallService...
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 6027): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6027): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6027): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6027): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6027): Creating a new PhoneAdapter instance
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6027): setListener: com.google.android.gms.car.dn@f10bdd5
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6027): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6027): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 6027): Package validated; name: com.android.vending
,V/Finsky  ( 5583): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1825): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5583): Thread-962(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5583): Thread-962(ApacheHTTPLog):isShipBuild true
I/System.out( 5583): Thread-962(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5583): Thread-962(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5583): Untagging socket 44
,I/qtaguid ( 5583): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5583): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5583): untagSocket(44) failed with errno -22
I/System.out( 5583): Thread-962 calls detatch()
,W/ResourcesManager( 5583): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5583): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5583): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5583): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/DeviceConnectionService( 1825): client connected with version: 8296000
,D/Finsky  ( 5583): [985] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5583): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5583): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1825): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 5583): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5583): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5583): (HTTPLog)-Static: isShipBuild true
I/System.out( 5583): (HTTPLog)-Thread-973-124864135: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5583): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10028
,I/System.out( 5583): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/ActivityManager( 1015): Killing 5435:com.samsung.aasaservice/1000 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5435/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/IcingInternalCorpora( 2006): getNumBytesRead when not calculated.
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  287): DCD OFF,
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/AlarmManager( 1015): waitForAlarm result :8
,D/PowerManagerService( 1015): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1015): Nap time (uid 1000)...
D/PowerManagerService( 1015): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
,I/PowerManagerService( 1015): !@[ps] Screen__Off - 0 :  dream(timeout) (2)
I/PowerManagerService( 1015): Going to sleep due to screen timeout (uid 1000)...
D/DisplayPowerController( 1015): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1015): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1015): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService( 1015): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1015): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService( 1015): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1015): handleSandman : startDream(true)
V/WindowOrientationListener( 1015): WindowOrientationListener disabled
E/PowerManagerService( 1015): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1015): Sleeping (uid 1000)...
,D/PowerManagerService( 1015): [s] UserActivityState : 4 -> 0
D/SensorService( 1015): [SO] activate (ident=0xb819bbf8, enabled=0)
,I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/SurfaceFlinger(  257): id=12 createSurf (720x1280),-1 flag=20004, DolorFade
,I/Adreno-EGL( 1015): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1015): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1015): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1015): Local Branch: 
I/Adreno-EGL( 1015): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1015): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1015):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/SensorManager( 1015): unregisterListener ::   
,D/KeyguardViewMediator( 1172): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1172): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1172): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1172): notifyScreenOffLocked
,D/KeyguardViewMediator( 1172): timeout : 5000
,I/DBG_DM  ( 3089): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,D/KeyguardViewMediator( 1172): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 1172): handleNotifyScreenOff
,D/VolumePanel( 1172): onScreenTurnedOff()
,D/VolumePanel( 1172): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/PowerManagerService( 1015): Excessive delay in ColorFade : createEglContext: 49ms
,D/VolumePanel( 1172): mCoverBroadcastReceiver: Screen OFF end
,D/SecKeyguardClockSingleView( 1172): onScreenTurnedOff
,E/Watchdog( 1015): !@Sync 2
,V/ActivityThread( 3089): updateVisibility : ActivityRecord{af9edd1 token=android.os.BinderProxy@1fb536bc {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/PowerManagerService( 1015): Excessive delay in ColorFade : createEglSurface: 10ms
,D/PermissionCache(  257): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (186 us)
,E/SmartFaceService( 1015): onReceive: android.intent.action.SCREEN_ON
,W/System.err( 1015): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,W/System.err( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1015): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1015): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1015): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1015): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1015): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1015): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1015): 	at libcore.io.Posix.open(Native Method)
E/SmartFaceService( 1015): fail to set sysfs 1
W/System.err( 1015): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1015): 	... 10 more
,D/InputMethodManagerService( 1015): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/PowerManagerService( 1015): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 33ms
,I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
,D/MotionRecognitionService( 1015):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService( 1015):  handler : SCREEN_ON end
,D/NotificationService( 1015): ACTION_SCREEN_ON
D/LightsService( 1015): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1015) 
,D/LightsService( 1015): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService( 1015): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1015): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
,V/voice   (  282): voice_set_parameters: enter: screen_state=on
V/voice   (  282): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  282): adev_set_parameters: exit
,E/WifiNative-wlan0( 1015): do suspend false
,I/wpa_supplicant( 2205): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2205): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2205): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 2205): Scan requested (ret=0) - scan timeout 30 seconds
D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/IpRemoteDisplayController( 1015): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1015): Bridge Server is not available
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1015): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler( 1015): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1441): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1441): call the applyRouting
,D/PowerManagerService( 1015): Excessive delay in ColorFade : initGLShaders: 47ms
,D/PowerManagerService( 1015): Excessive delay in ColorFade prepare: 158ms
,D/accuweather( 1724): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
D/DisplayPowerController( 1015): ColorFade: onAnimationStart
,D/accuweather( 1724): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/DisplayPowerController( 1015): getFinalBrightness : Summary is 5 -> 5
D/accuweather( 1724): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/DisplayPowerController( 1015): performScreenOffTransition : no brightness animation
D/accuweather( 1724): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
,D/ActivityManager( 1015): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1788): getNextShiftState() cursorCapsMode : 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LightsService( 1015): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1015) 
,D/LightsService( 1015): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService( 1015): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,E/lights  ( 1015): write_int failed to open -1
D/LightsService( 1015): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService( 1015): turn on LED for fully charged
,E/SmartFaceService( 1015): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1015): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1015): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1015): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SmartFaceService( 1015): fail to set sysfs 0
W/System.err( 1015): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1015): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1015): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1015): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1015): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1015): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1015): 	... 10 more
,D/SSRM:n  ( 1015): SIOP:: AP = 340
,I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
,D/MotionRecognitionService( 1015):   mReceiver.onReceive : ACTION_SCREEN_OFF
,D/SamsungIME( 1788): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,E/MotionRecognitionService( 1015):  handler : SCREEN_OFF end 
,D/NotificationService( 1015): ACTION_SCREEN_OFF
D/LightsService( 1015): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1015) 
,D/LightsService( 1015): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1015): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1015): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=off
,V/voice   (  282): voice_set_parameters: enter: screen_state=off
V/voice   (  282): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
,V/audio_hw_primary(  282): adev_set_parameters: exit
,D/daemonapp( 1302): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1302): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/BackgroundCompactionService( 1015): Schedule Type1 BGCompaction
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/IpRemoteDisplayController( 1015): intent received android.intent.action.SCREEN_OFF
,D/daemonapp( 1302): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/IpRemoteDisplayController( 1015): Bridge Server is not available
,D/comsamsunglog( 1302): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1302): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1302): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1302): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1302): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1302): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/daemonapp( 1302): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1302): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1455044700000
D/daemonapp( 1302): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1455023174747
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,D/daemonapp( 1302): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,V/EmergencyMode( 1414): [EmergencyStateReceiver] binteractive [false] why[3]
,D/PersonaManagerService( 1015): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1015): MSG_ACTION_SCREEN_OFF called
,D/daemonapp( 1302): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1302): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1302): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1302): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/NfcService( 1441): call the applyRouting
,E/WifiNative-wlan0( 1015): do suspend true
,I/BatteryStatsDumper( 1015): In refreshStats isReason Screen ON/OFF: true
,D/accuweather( 1724): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1724): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/CAR.SERVICE( 6027): mConnectedToCar = false, abort
,E/ActivityThread( 6027): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3e03a81d that was originally bound here
E/ActivityThread( 6027): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3e03a81d that was originally bound here
E/ActivityThread( 6027): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6027): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6027): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6027): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6027): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6027): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6027): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6027): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6027): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6027): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6027): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6027): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6027): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6027): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 6027): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 6027): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 6027): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6027): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6027): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6027): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6027): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6027): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6027): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,E/ActivityThread( 6027): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@142128c that was originally bound here
E/ActivityThread( 6027): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@142128c that was originally bound here
E/ActivityThread( 6027): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6027): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6027): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6027): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6027): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6027): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6027): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6027): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6027): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6027): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6027): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6027): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6027): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 6027): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 6027): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 6027): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6027): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6027): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6027): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6027): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6027): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6027): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,W/ActivityManager( 1015): Unbind failed: could not find connection for android.os.BinderProxy@364ca5fc
,D/accuweather( 1724): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/DisplayPowerState( 1015): !@ ColorFade entry
,D/DisplayPowerController( 1015): ColorFade: onAnimationEnd
,I/BatteryStatsDumper( 1015): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1015): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1015): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1015): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1015): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1015): Previous Battery Level: 0 Current Level: 100 Delta: -100
,D/lights  ( 1015): lcd : 0 +
,D/DisplayPowerController( 1015): getFinalBrightness : Summary is 0 -> 0
,D/DisplayPowerController( 1015): performScreenOffTransition : no brightness animation
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/lights  ( 1015): lcd : 0 -
,D/DisplayPowerController( 1015): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1015): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1015): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1015): [PWL] sb release: PowerManagerService.Display
,D/MISC PowerHAL( 1015): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 17
D/MISC PowerHAL( 1015): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/accuweather( 1724): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1724): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1724): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1724): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/MISC PowerHAL( 1015): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1015): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1015): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1015): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1015): Got set_interactive hint
,D/DisplayManagerService( 1015): !@display_state: ON -> OFF
,D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb8039690
I/DisplayManagerService( 1015): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 0 on display: 0
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
,V/ActivityManager( 1015): Display changed displayId=0
,E/LibSecureUISvc( 1940): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/SSRM:n  ( 1015): SIOP:: AP = 340
,D/PowerManagerService( 1015): [PWL] sb release: PowerManagerService.Broadcasts
,D/StatusBar.NetworkController( 1172): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1724): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1724): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1724): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1724): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/accuweather( 1724): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1724): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1724): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/BatteryStatsDumper( 1015): Writing to database completed
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
,D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl( 1015): Excessive delay in setPowerMode(): 250ms
,D/PowerManagerService( 1015): Excessive delay in !@display_state: OFF: 256ms
,I/libsuspend( 1015): !@autosuspend_wakeup_count_enable
,I/libsuspend( 1015): !@autosuspend_wakeup_count_enable done
,D/PowerManagerService( 1015): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 270ms
I/PowerManagerService( 1015): [PWL] Off : 0s ago
,D/SSRM:a  ( 1015): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1015): SettingsAirViewInfo:: 000000000
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 2205): nl80211: Received scan results (3 BSSes),
,D/WifiP2pService( 1015): InactiveState{ what=147461 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1015): DefaultState{ what=147461 },
,E/SMD     (  287): DCD OFF
I/ServiceManager(  313): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardViewMediator( 1172): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1172): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1172): *** Keyguard wallpaper service already unbounded
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PowerManagerService( 1015): [PWL] Off : 5s ago
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1015): waitForAlarm result :8,
,D/SSRM:n  ( 1015): SIOP:: AP = 310,
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :4,
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1015): onStart. jobID=801
,I/BackgroundCompactionService( 1015): onStart done. jobID=801
,I/BackgroundCompactionService( 1015): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1015): compact_memory command done
,E/SMD     (  287): DCD OFF,
,D/Finsky  ( 5583): [975] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5583): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/PowerManagerService( 1015): [PWL] Off : 15s ago
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 300
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 3
,V/AlarmManager( 1015): waitForAlarm result :4
,I/Atfwd_Sendcmd(  313): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  313): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1015): SIOP:: AP = 290,
,I/PowerManagerService( 1015): [PWL] Off : 30s ago
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/FactoryTest( 5359): Not factory mode
,D/FactoryTest( 5359): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5359): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5359): still no open session command from host, so toast
,W/ContextImpl( 5359): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5359): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 ,
I/Timeline( 5359): Timeline: Activity_launch_request id:com.android.settings time:114015
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist,
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1015): mDVFSHelper.acquire(),
,V/ActivityManager( 1015): Display changed displayId=0
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1015): Focused application set to: xxxx
,D/InputDispatcher( 1015): Focus left window: 3089
,E/MTPRx   ( 5359): started activity for popup
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5359): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5359): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5359): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5359): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5359): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5359): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5359): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/InputDispatcher( 1015): Focused application set to: xxxx
,D/InputDispatcher( 1015): Focus entered window: 3089
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 1015): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@838d918 attribute=android.view.inputmethod.EditorInfo@12e9ef71, token = android.os.BinderProxy@33fd5d17
,D/SamsungIME( 1788): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/SettingsReceiverActivity( 5359): dev.kiessupport is : TRUE
,D/PhoneWindow( 5359): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5359): *FMB* installDecor flags : 8388610
,I/DBG_DM  ( 3089): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 3089): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 31
,I/DBG_DM  ( 3089): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 3089): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3089): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 31
,I/DBG_DM  ( 3089): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3089): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3089): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3089): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 3089): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 31
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3089): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 3089): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3089): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3089): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3089): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,I/DBG_DM  ( 3089): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] ,
,V/ActivityThread( 3089): updateVisibility : ActivityRecord{af9edd1 token=android.os.BinderProxy@1fb536bc {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,I/Timeline( 3089): Timeline: Activity_idle id: android.os.BinderProxy@1fb536bc time:114268
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/ActivityManager( 1015): mDVFSHelper.release(),
,D/TaskPersister( 1015): removeObsoleteFile: deleting file=7_task.xml,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 290,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1015): waitForAlarm result :8,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,I/PowerManagerService( 1015): [PWL] Off : 50s ago,
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :4,
,V/AlarmManager( 1015): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1015): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1015): (AppSync) ### 0 added ###,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/EventLogService( 2006): Aggregate from 1455021428487 (log), 1455021428487 (data)
,I/art     ( 1825): Explicit concurrent mark sweep GC freed 37609(2MB) AllocSpace objects, 17(272KB) LOS objects, 39% free, 12MB/21MB, paused 1.227ms total 71.737ms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1825): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1825): Vacuum at: now=1455023228834 tag=VacuumService
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 68652(3MB) AllocSpace objects, 36(1172KB) LOS objects, 33% free, 28MB/42MB, paused 2.358ms total 159.636ms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1825): Scheduling Phenotype for one-off execution 7977 seconds from now (1455023229398)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1825): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1825): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1825): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1825): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1825): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1825): (HTTPLog)-Static: isShipBuild true
I/System.out( 1825): (HTTPLog)-Thread-259-934428658: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 1825): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1825): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1825): Tagging socket 82 with tag 1000120100000000{268440065,0} for uid -1, pid: 1825, getuid(): 10012
,I/qtaguid ( 1825): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1825, getuid(): 10012
,E/SMD     (  287): DCD OFF
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1825): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1825): Tagging socket 82 with tag 1000120100000000{268440065,0} for uid -1, pid: 1825, getuid(): 10012
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1825): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1825): Tagging socket 82 with tag 1000120100000000{268440065,0} for uid -1, pid: 1825, getuid(): 10012
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 4
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 75s ago
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1015): SIOP:: AP = 270,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 5
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1015): stay LED for fully charged,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :8
,I/PowerManagerService( 1015): [PWL] Off : 105s ago
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/ClearcutLoggerApiImpl( 1825): disconnect managed GoogleApiClient
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 6
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/SecKeyguardClockView( 1172): HomeTimezone(): 1
D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,I/Atfwd_Sendcmd(  313): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  313): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 140s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/Watchdog( 1015): !@Sync 7
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :8,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1015): !@Sync 8
,I/PowerManagerService( 1015): [PWL] Off : 180s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 9
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 225s ago
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/TLC_TIMA_PKM_initialize( 1015): initializing...
D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
I/TLC_TIMA_PKM_initialize( 1015): root = /firmware/image, root_strlen = 15
D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
I/TLC_TIMA_PKM_initialize( 1015): process = tima_pkm, process_strlen = 8
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
I/TZ: qc_tlc_communication( 1015): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1015): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1015): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1015): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1015): Trustlet response is completed
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1015): !@Sync 10
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/Atfwd_Sendcmd(  313): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  313): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1015): !@Sync 11
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/PowerManagerService( 1015): [PWL] Off : 275s ago
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1015): !@Sync 12
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 13
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1015): [PWL] Off : 330s ago
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :8,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
V/AlarmManager( 1015): No more alarm at this time.nowELAPSED=423823 batch.start=798174
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 14
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Atfwd_Sendcmd(  313): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  313): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 15
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1015): [PWL] Off : 390s ago
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :8,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/bootchecker(  309): bootchecker wake up!!,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 16
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 17
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PowerManagerService( 1015): [PWL] Off : 455s ago
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged,
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 18
,I/Atfwd_Sendcmd(  313): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  313): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,I/Atfwd_Daemon(  313): Stop the daemon....,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 19
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 525s ago,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 20
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 21
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 22
,I/PowerManagerService( 1015): [PWL] Off : 600s ago,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 23
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 24
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 680s ago,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 25
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :8
,E/Watchdog( 1015): !@Sync 26
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1015): Plugged
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 27,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 765s ago,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 28,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged
D/HeadsetStateMachine( 2621): Disconnected process message: 10
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 2621): Disconnected process message: 10
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 29,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,E/SMD     (  287): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1015): !@Sync 30
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1015): [PWL] Off : 855s ago
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 31
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1015): stay LED for fully charged
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 1015): waitForAlarm result :8,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1015): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 32
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 33,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 950s ago
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 34,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 35,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 36,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService( 1015): Plugged
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 37
,I/PowerManagerService( 1015): [PWL] Off : 1050s ago,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 38
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 39
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1015): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1015): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1015): Updating Usage Statistics in DB @ 1455024312349
,I/ApplicationPolicy( 1015): updateDataUsageMap
,I/NetworkDataUsageDb( 1015): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1015): ::isTableExists: Table exists 
,I/ApplicationUsage( 1015): Done Updating Usage Statistics in DB @ 1455024312652
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 40
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,I/PowerManagerService( 1015): [PWL] Off : 1155s ago,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 41,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,TIME-OUT KILL (timeout was 1200000ms),E/SMD     (  287): DCD OFF
D/SSRM:n  ( 1015): SIOP:: AP = 260
D/AndroidRuntime( 6582): 
D/AndroidRuntime( 6582): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6582): CheckJNI is OFF
D/AndroidRuntime( 6582): readGMSProperty: start
D/AndroidRuntime( 6582): readGMSProperty: already setted!!
D/AndroidRuntime( 6582): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6582): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6582): readGMSProperty: end
D/AndroidRuntime( 6582): addProductProperty: start
E/AffinityControl( 6582): AffinityControl: registerfunction enter
D/AndroidRuntime( 6582): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1015): START PACKAGE DELETE: observer{466682946}
D/PackageManager( 1015): pkg{<packageName>}
D/PackageManager( 1015): user{0}
D/PackageManager( 1015): caller{2000}
D/PackageManager( 1015): flags{3}
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1015): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 1015): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1015): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1015): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1015): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1015): !@killApplicatoin: 10155, uninstall pkg
I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
W/ActivityManager( 1015): CustomStartingWindow se packge removed so remove capture also
W/GeofencerStateMachine( 1825): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 1788): mOCRHelper is null
I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
I/art     ( 4947): Explicit concurrent mark sweep GC freed 20902(1152KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 6MB/11MB, paused 752us total 46.565ms
I/art     ( 5453): Explicit concurrent mark sweep GC freed 355(25KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 10.866ms total 59.238ms
I/art     ( 4758): Explicit concurrent mark sweep GC freed 15317(823KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 762us total 74.944ms
D/RegisteredComponentCache( 1441): Collect Tech packages for Knox
D/PersonaManager( 1441): isKioskContainerExistOnDevice
I/KLMS-2.5.183: ( 3548): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 14:26:00 GMT+01:00 2016
D/ActivityManager( 1015): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/art     ( 2006): Explicit concurrent mark sweep GC freed 4610(316KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 14MB/18MB, paused 1.460ms total 108.757ms
I/KLMS-2.5.183: ( 3548): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1015): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1015): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
I/KLMS-2.5.183: ( 3548): KLMSIntentService(): onCreate()
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
I/KLMS-2.5.183: ( 3548): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3548): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/Zygote  ( 6595): MountEmulatedStorage()
E/Zygote  ( 6595): v2
I/libpersona( 6595): KNOX_SDCARD checking this for 10094
I/libpersona( 6595): KNOX_SDCARD not a persona
I/SELinux ( 6595): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6595): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6595): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
I/ActivityManager( 1015): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6595 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3548): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/PackagesMonitor( 4980): PackagesMonitor onReceive :com.test.thalitest
I/KLMS-2.5.183: ( 3548): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.183: ( 3548): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.183: ( 3548): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6607): MountEmulatedStorage()
I/libpersona( 6607): KNOX_SDCARD checking this for 10149
E/Zygote  ( 6607): v2
I/libpersona( 6607): KNOX_SDCARD not a persona
I/SELinux ( 6607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6607 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider( 6595): TimaSignature is unavailable
E/SELinux ( 6607): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityThread( 6595): Added TimaKeyStore provider
D/RCPManagerService( 1015): PackageReceiver onReceive()
I/HarmonyEASService( 1015): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1015): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1015): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1015): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1015): DBIntegrity::getInstance - New instance created
D/PersonaManager( 1441): isKioskContainerExistOnDevice
D/OTPFW   ( 1015): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
I/OTPFW   ( 1015): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1015): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1015): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10155
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
D/TimaKeyStoreProvider( 6607): TimaSignature is unavailable
D/ActivityThread( 6607): Added TimaKeyStore provider
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10155
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
V/AlarmManagerEXT( 1015): com.test.thalitest(10155) is removed.
D/SSRM:aZ ( 1015): MSG_TYPE_APP_REMOVED::
D/RegisteredServicesCache( 1441): empty dynamic service
I/KLMS-2.5.183: ( 3548): KLMSIntentService(): listeningToPackageRemoved().END
E/SQLiteLog( 4758): (284) automatic index on crash_info_summary(package_name_touched)
D/Mms/FreeMessageStatusReceiver( 5649): onReceive, action : android.intent.action.PACKAGE_REMOVED
I/KLMS-2.5.183: ( 3548): KLMSIntentService(): onDestroy()
D/ActivityManager( 1015): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/TactileAssist( 1015): enable value -1
I/TactileAssist( 1015): internal enable value -1
I/TactileAssist( 1015): intensity value -1
I/TactileAssist( 1015): saveAppList value true
I/TactileAssist( 1015): List of disabled apps :
D/Mms/FreeMessageReceiverService( 5649): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 5649): onHandleIntent: ACTION_PACKAGE_REMOVED
D/Compatibility( 5890): onReceive() it will make start service
D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/ThemeInfoUtil( 6607): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 6607): isCurrentFestival = false
W/ContextImpl( 5103): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
D/Compatibility( 5890): onHandleIntent()
D/Compatibility( 5890): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10155, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 5890): found: 2
D/Compatibility( 5890): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5890): skipping ResolveInfo{348603a0 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5890): considering ResolveInfo{1fea7b59 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/Compatibility( 5890): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/elm:15183( 6595): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/Compatibility( 5890): enabling receiver ResolveInfo{841d31e com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/elm:15183( 6595): ELMEngine.ELMEngine( context ).
D/elm:15183( 6595): MDMBridge.setEnterpriseBridge()
I/art     ( 4758): Explicit concurrent mark sweep GC freed 2103(99KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 11.008ms total 64.311ms
D/Compatibility( 5890): enabling receiver ResolveInfo{398e37ff com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/ActivityManager( 1015): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
D/elm:15183( 6595): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/elm:15183( 6595): ElmAgentService : onCreate()
D/elm:15183( 6595): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6595): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6595): MDMBridge.getInstance()
D/elm:15183( 6595): MDMBridge.getAllLicenseInfoFromSDK()
D/ActivityManager( 1015): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/BadgeProvider( 5833): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5833): sendNotify, [notify] : null
D/BadgeProvider( 5833): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5833): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5833): update, [UpdateCount] : 1
D/Compatibility( 5890): enabling receiver ResolveInfo{24d7b9cc com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/UpdateIcingCorporaServi( 5453): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/elm:15183( 6595): MDMBridge.getAllLicenseInfoFromSDK()
D/Compatibility( 5890): enabling receiver ResolveInfo{2a3e7415 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/art     ( 1015): Explicit concurrent mark sweep GC freed 39357(3MB) AllocSpace objects, 76(1216KB) LOS objects, 33% free, 28MB/42MB, paused 5.603ms total 305.909ms
D/Compatibility( 5890): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/RCPManager( 5531):  in createShortcut() for packageName: com.test.thalitest userId0
I/libpersona( 6632): KNOX_SDCARD checking this for 1000
D/RCPManagerService( 1015):  in createShortcut() for packageName: com.test.thalitest userId0
I/libpersona( 6632): KNOX_SDCARD not a persona
D/RCPManagerService( 1015): queryAllProviders():  providerCallBack is not register for 0
E/Zygote  ( 6632): MountEmulatedStorage()
E/Zygote  ( 6632): v2
I/SELinux ( 6632): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6632): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6632 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6632): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6632): TimaSignature is unavailable
D/ActivityThread( 6632): Added TimaKeyStore provider
D/elm:15183( 6595): ElmAgentService : onDestroy().
I/TapandpayWidget:TapandpayAppWidgetProvider( 5706): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 5706): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils( 5706): Clear T&P info.
D/TapandpayWidget:TapandpayAppWidgetProvider( 5706): Widget is not attached.
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1015): delete codoeFile: 
E/Zygote  ( 6648): MountEmulatedStorage()
E/Zygote  ( 6648): v2
I/libpersona( 6648): KNOX_SDCARD checking this for 10160
I/AASA_removePackage( 1015): UID=10155 Target=com.test.thalitest
I/libpersona( 6648): KNOX_SDCARD not a persona
D/AASAuninstall( 1015): userId = 0, info.removedAppID = -1, info.uid = 10155, packageName = com.test.thalitest
D/AASAservice-UpdateReceiver( 6632): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
I/SELinux ( 6648): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/PackageManager( 1015): result of delete: 1{466682946}
D/AndroidRuntime( 6582): Shutting down VM
W/System.err( 6632): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/SELinux ( 6648): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/System.err( 6632): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6632): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6632): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6632): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6632): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6632): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6632): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6632): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6632): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6632): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6632): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6632): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SELinux ( 6648): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6648 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6662 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
D/TimaKeyStoreProvider( 6648): TimaSignature is unavailable
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ActivityThread( 6648): Added TimaKeyStore provider
E/Zygote  ( 6662): MountEmulatedStorage()
E/Zygote  ( 6662): v2
I/libpersona( 6662): KNOX_SDCARD checking this for 10003
I/libpersona( 6662): KNOX_SDCARD not a persona
I/SELinux ( 6662): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
I/SELinux ( 6662): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6662): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6662): TimaSignature is unavailable
D/ActivityThread( 6662): Added TimaKeyStore provider
I/PCWCLIENTTRACE_PushUtil( 5670): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5670): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5670): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5670): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/ResourcesManager( 6648): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
E/Zygote  ( 6678): MountEmulatedStorage()
E/Zygote  ( 6678): v2
I/libpersona( 6678): KNOX_SDCARD checking this for 1000
I/libpersona( 6678): KNOX_SDCARD not a persona
I/SELinux ( 6678): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6678): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6678): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6678 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/[0]UMC:UMCContentProvider( 6648): @onCreate
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 5497): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/[0]UMC:Core( 6648): onCreate(): 
D/[0]UMC:Core( 6648): @isManagedProfileUser
D/[0]UMC:Core( 6648): userId: 0
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/[0]UMC:Core( 6648): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 6648): userInfo.isManagedProfile() : false
D/TimaKeyStoreProvider( 6678): TimaSignature is unavailable
D/ActivityThread( 6678): Added TimaKeyStore provider
W/ResourcesManager( 5497): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
E/Zygote  ( 6693): MountEmulatedStorage()
E/Zygote  ( 6693): v2
I/libpersona( 6693): KNOX_SDCARD checking this for 10035
I/libpersona( 6693): KNOX_SDCARD not a persona
I/SELinux ( 6693): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/UserAnalysis.PlaceProvider( 6662): PlaceProvider onCreate()
I/SELinux ( 6693): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6693 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6693): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 5497): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/ActivityManager( 1015): Killing 5473:com.google.android.partnersetup/u0a15 (adj 15): empty #31
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/[0]UMC:DeviceInfo( 6648): USA==US==
D/TimaKeyStoreProvider( 6693): TimaSignature is unavailable
D/ActivityThread( 6693): Added TimaKeyStore provider
D/UserAnalysis.SecureDbManager( 6662): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 6662): SecurePlaceDbHelper() 
D/UserAnalysis( 6662): Create SecureDbHelper
W/ResourcesManager( 5497): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/art     ( 6582): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/IntelligenceServiceApplication( 6662): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6662): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
I/ActivityManager( 1015): Killing 5688:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
W/ResourcesManager( 5497): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ContextImpl( 6678): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
I/UpdateIcingCorporaServi( 5453): UpdateCorporaTask done [took 344 ms] updated apps [took 344 ms] 
D/IntelligenceServiceApplication( 6662): no applications having user consent for prediction
D/ActivityManager( 1015): startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
V/PlaceDetection v1.0.19 ( 6662): [PlaceDetection::stopService] Service stopped.
E/Zygote  ( 6712): MountEmulatedStorage()
E/Zygote  ( 6712): v2
I/libpersona( 6712): KNOX_SDCARD checking this for 1000
I/libpersona( 6712): KNOX_SDCARD not a persona
I/SELinux ( 6712): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6712): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6712 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6712): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 5722:com.policydm/1000 (adj 15): empty #31
V/PlaceDetection v1.0.19 ( 6662): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
W/ResourcesManager( 5497): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 6712): TimaSignature is unavailable
W/ResourcesManager( 5497): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/ActivityThread( 6712): Added TimaKeyStore provider
W/ResourcesManager( 5497): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/ActivityManager( 1015): Killing 5756:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
D/USER_AGENT( 6648): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
D/[0]UMC:AdminManager( 6648): init - start

```
