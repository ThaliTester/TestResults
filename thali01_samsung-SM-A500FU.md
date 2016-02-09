#### Test 587523534d3a10e_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
--------- beginning of system
I/ActivityManager( 1017): Process com.samsung.indexservice (pid 4944)(adj 13) has died(103,1158)
W/libprocessgroup( 1017): failed to open /acct/uid_10113/pid_4568/cgroup.procs: No such file or directory
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4997): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SettingsProvider( 1017): name = icc_lock_enable
W/ContextImpl( 4997): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
D/FaceInterface( 4997): requestFaceScan() is called.
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
W/LocalSuggestAlbumData( 4997): query fail: 
I/SettingSearch/SearchIntentReceiver( 1357): action : com.samsung.settings.CHANGED_ICC_LOCK_ENABLE
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.sec.smartcard.manager
I/FaceInterface( 4997): startFaceScan() : waiting 5 sec
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.smartcard.manager, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/LocalSuggestAlbumData( 4997): query fail: 
E/Zygote  ( 5025): MountEmulatedStorage()
E/Zygote  ( 5025): v2
I/SELinux ( 5025): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5025): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/libpersona( 5025): KNOX_SDCARD checking this for 10153
I/libpersona( 5025): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.smartcard.manager for broadcast com.sec.smartcard.manager/com.sec.smartcard.pinservice.SmartCardBroadcastReceiver: pid=5025 uid=10153 gids={50153, 9997, 3001, 3002} abi=armeabi-v7a
E/SELinux ( 5025): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5025): TimaSignature is unavailable
D/ActivityThread( 5025): Added TimaKeyStore provider
I/art     (  309): Explicit concurrent mark sweep GC freed 8699(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 658us total 28.058ms
W/ResourcesManager( 5025): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 17.131ms
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 746us total 17.408ms
D/Mms/BubbleViewCache( 4720): fillCache bubble = 1
E/SmartCardContentProvider( 5025): onCreate
I/SmartCardBroadcastReceiver( 5025): SmartCardBroadcastReceiver - onReceive() 
I/SmartCardBroadcastReceiver( 5025): Broadcast received for locktype changed 
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
I/ActivityManager( 1017): Killing 4539:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
E/CscFactoryReceiver( 1451): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1451): Media DB Scanner finished.
D/CscFactoryReceiver( 1451): start service to Set Ringtone
D/ActivityManager( 1017): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/CscFactoryReceiver( 1451): start service to Set Notification
D/ActivityManager( 1017): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/CscFactoryReceiver( 1451): start service to Set Alarmtone
D/ActivityManager( 1017): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/CscUpdateService( 1451): onStart
E/CscUpdateService( 1451): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1451): only ringtone update
D/CscUpdateService( 1451): onStart
E/CscUpdateService( 1451): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1451): only notification update
D/CscUpdateService( 1451): onStart
E/CscUpdateService( 1451): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1451): only alarmtone update
E/CscParser( 1451): update(): xml file exist
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.indexservice, hostingType: broadcast
E/CscParser( 1451): update(): xml file exist
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/CscParser( 1451): update(): xml file exist
W/CSCSettings( 1451): Setting Ringtones (type) : 2
D/CscParser( 1451): MessageTone: null
W/CSCSettings( 1451): 1. Tag_Str: null
W/CSCSettings( 1451): Setting Ringtones (type) : 4
D/CscParser( 1451): AlarmTone: null
W/CSCSettings( 1451): Setting Ringtones (type) : 1
D/CscParser( 1451): RingTone: null
W/CSCSettings( 1451): 1. Tag_Str: null
W/CSCSettings( 1451): 1. Tag_Str: null
E/Zygote  ( 5047): MountEmulatedStorage()
E/Zygote  ( 5047): v2
I/libpersona( 5047): KNOX_SDCARD checking this for 10006
I/libpersona( 5047): KNOX_SDCARD not a persona
I/SELinux ( 5047): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5047): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5047): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5047 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider( 5047): TimaSignature is unavailable
D/ActivityThread( 5047): Added TimaKeyStore provider
W/libprocessgroup( 1017): failed to open /acct/uid_10010/pid_4539/cgroup.procs: No such file or directory
I/ThumbnailProvider( 5047): ThumbnailProvider onCreate()
I/DocumentBroadcastReceiver( 5047): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
I/BroadcastProcessorService( 5047): [START] processBroadcastIntent ...
D/ActivityManager( 1017): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
D/GalleryCacheReady( 4997): Receive action.ACTION_MEDIA_SCANNER_FINISHED
D/GalleryCacheReady( 4997): handleMeidaScanFinish()
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
I/BroadcastProcessorService( 5047): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
D/ActivityManager( 1017): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
D/FaceInterface( 4997): requestFaceScan() is called.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
W/LocalSuggestAlbumData( 4997): query fail: 
I/SystemInfo( 5047): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 5047): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
I/BroadcastProcessorService( 5047): [START] DocumentService startDocumentService
D/ActivityManager( 1017): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
W/LocalSuggestAlbumData( 4997): query fail: 
I/FaceInterface( 4997): startFaceScan() : waiting 5 sec
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
D/ActivityManager( 1017): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
I/DocumentService( 5047): DocumentService onCreate ... service
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.app.popupuireceiver
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 5047): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5047): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
E/Zygote  ( 5068): MountEmulatedStorage()
E/Zygote  ( 5068): v2
I/libpersona( 5068): KNOX_SDCARD checking this for 1000
I/libpersona( 5068): KNOX_SDCARD not a persona
I/SELinux ( 5068): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5068 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5068): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5068): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5068): TimaSignature is unavailable
D/ActivityThread( 5068): Added TimaKeyStore provider
E/SystemInfo( 5047): [SIOP LEVEL] : 0
I/DocumentService( 5047): [BEGIN SYNC] DocumentService beginIndexing :16
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5047): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
D/PopupuiReceiver( 5068): onReceive() getAction : com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED
D/SecContentProvider2( 1017): uri = -1 selection = getSealedState
D/SecContentProvider2( 1017): mCursor = null
I/PopupuiReceiver_KNOX( 5068): getSealedState : true
D/SecContentProvider2( 1017): uri = 15 selection = getSealedHideNotificationMessages
D/SecContentProvider2( 1017): mCursor = null
I/PopupuiReceiver_KNOX( 5068): getSealedHideNotificationMessages : 1
D/SecContentProvider2( 1017): uri = 15 selection = getCheckCoverPopupState
D/SecContentProvider2( 1017): mCursor = null
I/PopupuiReceiver_KNOX( 5068): getCheckCoverPopupState : true
D/PopupuiReceiver( 5068): Action cable connected ! on - 
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.samsung.android.app.powersharing
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.powersharing, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5086): MountEmulatedStorage()
E/Zygote  ( 5086): v2
I/libpersona( 5086): KNOX_SDCARD checking this for 10122
I/libpersona( 5086): KNOX_SDCARD not a persona
I/SELinux ( 5086): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5086): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5086): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.android.app.powersharing for broadcast com.samsung.android.app.powersharing/.service.BatteryReceiver: pid=5086 uid=10122 gids={50122, 9997} abi=armeabi-v7a
W/ResourcesManager( 4960): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/File    ( 5047): fail readDirectory() errno=13
E/File    ( 5047): fail readDirectory() errno=13
I/SystemInfo( 5047): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5047): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 5047): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :65
E/DocumentService( 5047): [THUMBNAIL] Total Time taken for each file :0
E/        ( 5047): [INDEX] Total time taken for each file :0
I/DocumentService( 5047): DocumentService onDestroy start
I/DocumentService( 5047): DocumentService onDestroy end
I/ActivityManager( 1017): Killing 4627:com.sec.android.cloudagent/u0a2 (adj 15): empty #31
D/TimaKeyStoreProvider( 5086): TimaSignature is unavailable
D/ActivityThread( 5086): Added TimaKeyStore provider
I/DocumentService( 5047): DocumentService cleanupEverything start
I/IndexParserThreadsManager( 5047): InterruptedException: null
W/ResourcesManager( 4960): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4960): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4960): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/SystemInfo( 5047): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5047): DocumentService cleanupEverything end
I/Process ( 5047): Sending signal. PID: 5047 SIG: 9
I/PowerSharing.BatteryReceiver( 5086): onReceive : com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.wluc, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5102): MountEmulatedStorage()
E/Zygote  ( 5102): v2
I/libpersona( 5102): KNOX_SDCARD checking this for 10165
I/libpersona( 5102): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.android.app.wluc for broadcast com.sec.android.app.wluc/.PolicyManagerBroadcastReceiver: pid=5102 uid=10165 gids={50165, 9997} abi=armeabi-v7a
I/SELinux ( 5102): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5102): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5102): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Process com.samsung.indexservice (pid 5047)(adj 11) has died(98,1159)
D/TimaKeyStoreProvider( 5102): TimaSignature is unavailable
D/ActivityThread( 5102): Added TimaKeyStore provider
W/libprocessgroup( 1017): failed to open /acct/uid_10002/pid_4627/cgroup.procs: No such file or directory
I/PolicyManagerBroadcastReceiver( 5102): onReceive: action = com.sec.intent.ACTION.SSRM_HGL_UPDATE
D/SSRM:n  ( 1017): SIOP:: AP = 400
I/PolicyManagerBroadcastReceiver( 5102): onReceive: width = 720, height = 1280
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuSettingSearch: pid=5117 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/MediaStoreImporter( 4478): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager( 1017): Killing 4668:com.sec.android.diagmonagent/1000 (adj 15): empty #31
E/Zygote  ( 5117): MountEmulatedStorage()
E/Zygote  ( 5117): v2
I/libpersona( 5117): KNOX_SDCARD checking this for 1000
I/libpersona( 5117): KNOX_SDCARD not a persona
I/SELinux ( 5117): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Killing 3161:com.policydm/1000 (adj 15): empty #31
I/SELinux ( 5117): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5117): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5117): TimaSignature is unavailable
D/ActivityThread( 5117): Added TimaKeyStore provider
D/AssistantMenuSettingSearch( 5117): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
D/AssistantMenuSettingSearch( 5117): Make Setting DB
D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.sec.providers.settingsearch
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5132): MountEmulatedStorage()
E/Zygote  ( 5132): v2
I/libpersona( 5132): KNOX_SDCARD checking this for 10150
I/libpersona( 5132): KNOX_SDCARD not a persona
I/SELinux ( 5132): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=5132 uid=10150 gids={50150, 9997} abi=armeabi-v7a
I/SELinux ( 5132): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5132): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5132): TimaSignature is unavailable
D/ActivityThread( 5132): Added TimaKeyStore provider
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager( 1017): Waited long enough for: ServiceRecord{3eb3ba24 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4668/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3161/cgroup.procs: No such file or directory
,W/ContextImpl( 5117): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:158 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:38 
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.phone
I/ActivityManager( 1017): Killing 4226:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
I/ActivityManager( 1017): Killing 4650:com.google.android.apps.plus/u0a120 (adj 15): empty #32
I/SettingSearchManagerReceiver( 1451): onReceive : com.samsung.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
I/SettingSearchManagerReceiver( 1451): addSearchInfoDB
I/SettingSearchManagerReceiver( 1451): endInsert
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5150): MountEmulatedStorage()
E/Zygote  ( 5150): v2
I/libpersona( 5150): KNOX_SDCARD checking this for 10101
I/libpersona( 5150): KNOX_SDCARD not a persona
I/SELinux ( 5150): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5150 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5150): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5150): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1017): failed to open /acct/uid_10120/pid_4650/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10125/pid_4226/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5150): TimaSignature is unavailable
D/ActivityThread( 5150): Added TimaKeyStore provider
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/AndroidRuntime( 5147): 
D/AndroidRuntime( 5147): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5147): CheckJNI is OFF
D/AndroidRuntime( 5147): readGMSProperty: start
D/AndroidRuntime( 5147): readGMSProperty: already setted!!
D/AndroidRuntime( 5147): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5147): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5147): readGMSProperty: end
D/AndroidRuntime( 5147): addProductProperty: start
I/Gmail   ( 5150): getAccountsCursor
D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1822): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5150): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/Gmail   ( 5150): Observing account changes for notifications
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
E/Gmail   ( 5150): Error finding the version of the Email provider.....
E/Gmail   ( 5150): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5150): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 5150): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 5150): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 5150): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5150): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5150): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 5150): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5150): We do not support migrating this version of the Email provider.
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/Gmail   ( 5150): getAccountsCursor
D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1822): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/AffinityControl( 5147): AffinityControl: registerfunction enter
E/Zygote  ( 5191): MountEmulatedStorage()
E/Zygote  ( 5191): v2
I/ActivityManager( 1017): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=5191 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 4488:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
I/libpersona( 5191): KNOX_SDCARD checking this for 10033
I/libpersona( 5191): KNOX_SDCARD not a persona
I/SELinux ( 5191): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5191): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5191): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
V/GLSActivity( 1822): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/AndroidRuntime( 5147): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
D/AndroidRuntime( 5147): Shutting down VM
D/TimaKeyStoreProvider( 5191): TimaSignature is unavailable
W/libprocessgroup( 1017): failed to open /acct/uid_10009/pid_4488/cgroup.procs: No such file or directory
D/ActivityThread( 5191): Added TimaKeyStore provider
E/SQLiteLog( 5150): (283) recovered 44 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
E/File    ( 5150): fail readDirectory() errno=2
W/ResourcesManager( 5191): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5191): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5191): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/Gmail   ( 5150): notifyAccountChanged
I/Gmail   ( 5150): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5150): getAccountsCursor
D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
W/ResourcesManager( 5191): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5191): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5191): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/Gmail   ( 5150): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5150): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5150): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/GLSActivity( 1822): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1625): Explicit concurrent mark sweep GC freed 2832(113KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 755us total 28.482ms
W/ResourcesManager( 5191): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5191): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 5191): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/SMD     (  288): DCD OFF
D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
W/art     ( 5147): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/Gmail   ( 5150): getAccountsCursor
D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1822): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1017): Killing 4694:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
E/SPPClientService( 3983): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5226): MountEmulatedStorage()
,E/Zygote  ( 5226): v2
I/libpersona( 5226): KNOX_SDCARD checking this for 10035
I/libpersona( 5226): KNOX_SDCARD not a persona
,I/SELinux ( 5226): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=5226 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 5226): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5226): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5226): TimaSignature is unavailable
,D/ActivityThread( 5226): Added TimaKeyStore provider
,E/SPPClientService( 5226): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5226): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 5226): PushLog.txt file is not deleted.
,D/SPPClientService( 5226): PushLog.txt file is not deleted.
,D/SPPClientService( 5226): ============PushLog. stop!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5246): MountEmulatedStorage()
I/libpersona( 5246): KNOX_SDCARD checking this for 10035
E/Zygote  ( 5246): v2
I/libpersona( 5246): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=5246 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 4010:com.osp.app.signin/u0a41 (adj 15): empty #31
,I/SELinux ( 5246): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/libprocessgroup( 1017): failed to open /acct/uid_10062/pid_4694/cgroup.procs: No such file or directory
I/SELinux ( 5246): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5246): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5246): TimaSignature is unavailable
,D/ActivityThread( 5246): Added TimaKeyStore provider
,E/SPPClientService( 5246): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5246): [PushClientApplication] Push log off : This is Ship build version
,E/LNoti   ( 5246): [PhoneStatusChangeReceiver] This device doesn't register yet.
,W/libprocessgroup( 1017): failed to open /acct/uid_10041/pid_4010/cgroup.procs: No such file or directory
,D/SPPClientService( 5246): PushLog.txt file is not deleted.
D/SPPClientService( 5246): PushLog.txt file is not deleted.
D/SPPClientService( 5246): ============PushLog. stop!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1017): Killing 4076:com.android.providers.calendar/u0a42 (adj 15): empty #31
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1822): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.download.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10042/pid_4076/cgroup.procs: No such file or directory
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 208765(7MB) AllocSpace objects, 11(2MB) LOS objects, 23% free, 52MB/68MB, paused 3.184ms total 260.373ms
,W/GCoreFlp( 1822): No location to return for getLastLocation()
,W/FusedLocationProvider( 1822): location=null
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SafeBrowsingUpdateIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5270 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/Zygote  ( 5270): MountEmulatedStorage()
I/libpersona( 5270): KNOX_SDCARD checking this for 10104
E/Zygote  ( 5270): v2
I/libpersona( 5270): KNOX_SDCARD not a persona
,I/SELinux ( 5270): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5270): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5270): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/art     (  309): Explicit concurrent mark sweep GC freed 8686(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 22.410ms
D/TimaKeyStoreProvider( 5270): TimaSignature is unavailable
D/ActivityThread( 5270): Added TimaKeyStore provider
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 17.860ms
,W/ResourcesManager( 5270): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 17.084ms
,I/Babel   ( 5270): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5270): MmsConfig.loadMmsSettings
,I/Babel   ( 5270): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 5270): MmsConfig.loadFromDatabase
,E/Babel   ( 5270): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5270): MmsConfig.loadFromResources
,E/Babel   ( 5270): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5270): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 5270): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_StickerModule( 5270): App launched.
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5295): MountEmulatedStorage(),
E/Zygote  ( 5295): v2
,I/libpersona( 5295): KNOX_SDCARD checking this for 1000
,I/libpersona( 5295): KNOX_SDCARD not a persona
,I/SELinux ( 5295): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5295): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/art     ( 1017): Background sticky concurrent mark sweep GC freed 95318(3MB) AllocSpace objects, 11(5MB) LOS objects, 10% free, 60MB/68MB, paused 3.493ms total 126.683ms
,E/SELinux ( 5295): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=5295 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  283): getCameraInfo: X
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  283): getCameraInfo: X
,D/TimaKeyStoreProvider( 5295): TimaSignature is unavailable
,D/ActivityThread( 5295): Added TimaKeyStore provider
,W/VideoCapabilities( 5270): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5270): Unsupported mime audio/evrc
,W/AudioCapabilities( 5270): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5270): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5270): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5270): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5270): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5270): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5270): Unsupported mime audio/evrc
,W/VideoCapabilities( 5270): Unsupported mime video/wvc1
,W/VideoCapabilities( 5270): Unsupported mime video/x-ms-wmv
,I/DIAGMON_AGENT( 5295): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/VideoCapabilities( 5270): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5270): Unsupported mime video/wvc1
,W/VideoCapabilities( 5270): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5270): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5270): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5270): Unsupported mime video/mp43
,W/VideoCapabilities( 5270): Unsupported mime video/sorenson
,W/VideoCapabilities( 5270): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5270): Unsupported profile 4 for video/mp4v-es
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/ActivityManager( 1017): Killing 4263:com.android.calendar/u0a135 (adj 15): empty #31
,I/DIAGMON_AGENT( 5295): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 5295): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 5295): [com.diagmondm.XDMBroadcastReceiver(33/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager( 1017): Killing 4395:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,I/DBG_DM  ( 3103): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{2431074f u0 com.sec.bcservice/.BroadcastService}
,W/ContextImpl( 4744): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.sm.base.a.a:307 com.samsung.android.sm.contextagent.ContextAgentReceiver.onReceive:124 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5270): Creating RTCS
,W/libprocessgroup( 1017): failed to open /acct/uid_10135/pid_4263/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4395/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5314): MountEmulatedStorage(),
I/libpersona( 5314): KNOX_SDCARD checking this for 10135
,E/Zygote  ( 5314): v2
I/libpersona( 5314): KNOX_SDCARD not a persona
I/SELinux ( 5314): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5314 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux ( 5314): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5314): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Babel   ( 5270): Destroying RTCS
,D/TimaKeyStoreProvider( 5314): TimaSignature is unavailable
,D/ActivityThread( 5314): Added TimaKeyStore provider
,W/PackageManager( 1017): verifying app can be installed or not
D/ApplicationPolicy( 1017): isApplicationInstallationEnabled
,D/ApplicationPolicy( 1017): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1017): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1017): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1017): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy( 1017): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1017): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1017): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1017): isApplicationInstallationEnabled :  Checking SIG BL - true
,D/ApplicationPolicy( 1017): isApplicationInstallationEnabled :  enabled true
,I/AASAInstall( 1017): ship mode
,W/ResourcesManager( 5314): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5314): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5314): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityManager( 1017): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1017): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5335): MountEmulatedStorage(),
E/Zygote  ( 5335): v2
,I/libpersona( 5335): KNOX_SDCARD checking this for 10142
I/SELinux ( 5335): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5335): KNOX_SDCARD not a persona
,I/SELinux ( 5335): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5335 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 5335): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 4713:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5335): TimaSignature is unavailable
,D/ActivityThread( 5335): Added TimaKeyStore provider
,V/TaskCloserActivity( 5335): TaskCloserActivity enter()
,V/TaskCloserActivity( 5335): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1017): failed to open /acct/uid_10157/pid_4713/cgroup.procs: No such file or directory
,E/Zygote  ( 5350): MountEmulatedStorage()
I/libpersona( 5350): KNOX_SDCARD checking this for 10042
E/Zygote  ( 5350): v2
I/libpersona( 5350): KNOX_SDCARD not a persona
I/SELinux ( 5350): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5350 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1017): Killing 4756:com.qualcomm.timeservice/1000 (adj 15): empty #31
,I/SELinux ( 5350): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5350): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/TimaKeyStoreProvider( 5350): TimaSignature is unavailable
,D/ActivityThread( 5350): Added TimaKeyStore provider
,W/ResourcesManager( 5350): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5350): CalendarProvider2.onCreate() called
,I/art     ( 1017): Background partial concurrent mark sweep GC freed 574717(34MB) AllocSpace objects, 5(7MB) LOS objects, 27% free, 43MB/59MB, paused 3.809ms total 263.760ms
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4756/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/PolicyManagerBroadcastReceiver( 5102): This process will be killed soon.
,I/Process ( 5102): Sending signal. PID: 5102 SIG: 9
,E/Zygote  ( 5368): MountEmulatedStorage()
E/Zygote  ( 5368): v2
I/libpersona( 5368): KNOX_SDCARD checking this for 1000
I/libpersona( 5368): KNOX_SDCARD not a persona
,I/SELinux ( 5368): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5368): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5368 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 5368): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/SQLiteLog( 5350): (284) automatic index on view_events(_id)
,D/TimaKeyStoreProvider( 5368): TimaSignature is unavailable
,D/ActivityThread( 5368): Added TimaKeyStore provider
,D/CalendarAlarmManager( 5350): sys current time:1455029354242
,D/CalendarAlarmManager( 5350): reminder amount:0
,E/MTPRx   ( 5368): In MtpReceiverandroid.hardware.usb.action.USB_STATE
I/ActivityManager( 1017): Process com.sec.android.app.wluc (pid 5102)(adj 15) has died(59,1168)
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1017): mCursor = null
,V/MTPRx   ( 5368): sealedState: false
,V/MTPRx   ( 5368): sealedUsbMassStorageState: false
E/MTPRx   ( 5368): check value of boot_completed is1
,E/MTPRx   ( 5368): check booting is completed_sys.boot_completed
,E/MTPRx   ( 5368): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 5368): Status for mount/Unmount :removed
,E/MTPRx   ( 5368): SDcard is not available
,W/MTPRx   ( 5368): value of connected istrue
,W/MTPRx   ( 5368): value of configured istrue
W/MTPRx   ( 5368): value of mtpEnabled istrue
W/MTPRx   ( 5368): value of ptpEnabled isfalse
,E/MTPRx   ( 5368): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 5368): mFirstTime: false
,D/        ( 5368): MTP: reading debug level property
,E/MTPJNIInterface( 5368): Getting CryptionKey from JAVA
,E/MTPRx   ( 5368): currentUserId is 0
,E/MTPRx   ( 5368): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 5368): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 5368): is_Privatemode is NOT 1
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,D/SecContentProvider( 1017): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 5368): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1017): name = mtp_running_status
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,E/MTPRx   ( 5368): else part ... so first time!!!
,E/MTPPlaObsrvr( 5368): inside setContext()
E/MTPPlaObsrvr( 5368):  inside createplafiles
,E/MTPPlaObsrvr( 5368): playlist count is0
E/MTPPlaObsrvr( 5368):  inside try branch createplafiles
,E/MTPPlaObsrvr( 5368):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 5368): Inside registerContentObserver
,E/MtpAdbObserver( 5368): inside setContext()
E/MtpAdbObserver( 5368): Inside registerContentObserver
W/Settings( 5368): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1017): name = mtp_running_status
,V/MtpMediaDBManager( 5368): inside deleteAllDB
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,E/MtpService( 5368): onCreate.
,D/ActivityManager( 1017): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/MtpService( 1228): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpService( 5368): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 5368): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,D/MediaScannerReceiver( 1228): action: com.samsung.intent.action.MTP_FILE_SCAN
,E/MtpService( 5368): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,V/MtpMediaDBManager( 5368): inside Thread updateDB
E/MtpService( 5368): onStartCommand.
,W/MTPRx   ( 5368): calling native method
E/MtpService( 5368): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 5368): < MTP > Registering BroadCast receiver :::::
,D/ActivityManager( 1017): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,E/MTPJNIInterface( 5368): < MTP > Registering BroadCast receiver :::::::
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.android.settings
E/MTPJNIInterface( 5368): noti = 10
E/MtpService( 5368): onStartCommand.
,E/MtpService( 5368): handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/MTPRx   ( 5368): calling native method
E/MTPRx   ( 5368): Checking the driver time out
E/MTPJNIInterface( 5368): noti = 2
D/        ( 5368): deleting sockets before message queue initialization
,D/        ( 5368): event handler thread is created, so set the flag
,E/MTPRx   ( 5368): called native method
E/MTPJNIInterface( 5368): setting Media scanner status0
E/MTPJNIInterface( 5368): After setting Media scanner status0
,I/SettingSearch/SearchIntentReceiver( 1357): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 1357): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,W/MTPRx   ( 5368): notification from stack 1
E/MtpMediaDBManager( 5368): count : 27
,I/SettingSearch/SearchIntentReceiver( 1357): InitTitleDBThread start --> mDoingInitTitleDB : true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/        ( 5368): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 5368): Getting media scanner status0
,E/MTPJNIInterface( 5368): DeviceName is A5-1
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/MtpMediaDBManager( 5368): sending db update complete noti to stack
E/MTPJNIInterface( 5368): noti = 29
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/MTPJNIInterface( 5368): Status for mount/Unmount :removed
,E/MTPJNIInterface( 5368): SDcard is not available
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/        ( 5368): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,E/        ( 5368): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 5368): Status for mount/Unmount :removed
E/MTPJNIInterface( 5368): SDcard is not available
,E/SQLiteLog( 5368): (21) API call with NULL database connection pointer
E/SQLiteLog( 5368): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 5368): (21) API call with NULL database connection pointer
E/SQLiteLog( 5368): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5368): (21) API call with NULL database connection pointer
E/SQLiteLog( 5368): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5368): (21) API call with NULL database connection pointer
E/SQLiteLog( 5368): (21) misuse at line 106108 of [9491ba7d73]
W/MTPRx   ( 5368): notification from stack 2
,D/        ( 5368): [mtp_init_device] Library open with 32 bits.
,D/        ( 5368): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 5368): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 5368): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 5368):  [sua_support_present:1287] returning false 
D/        ( 5368): *****Starting mtp_io()
,D/        ( 5368): [mtp_start_io] source_thread Creation 
,W/MTPRx   ( 5368): notification from stack 3
D/        ( 5368): [mtp_start_io] sink_thread Creation 
D/        ( 5368): [mtp_start_io:376] sink thread created so set th_sink
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SettingSearch/SettingsSearchManager( 1357): Infomation -> numtitleinfo : 0 numSearchinfo : 306
,D/MediaScannerService( 1228): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/WearableService( 1822): callingUid 10012, callindPid: 1822
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter finished
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
,D/MediaScanner( 1228): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,I/SettingSearch/SearchIntentReceiver( 1357): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 1357): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,V/MediaScanner( 1228): processDirectory :  /storage/emulated/0
,I/MusicLeanback( 4478): Conditions not met for autocaching.
,I/MusicLeanback( 4478): Stop autocaching.
,I/SettingSearch/SettingsSearchManager( 1357):  Infomation -> getItem size : 306
,D/MediaScanner( 1228): Skipping:
D/MediaScanner( 1228): 7klwibgf7fvntblfd7(75ebcf7
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/MediaScanner( 1228): Skipping:
D/MediaScanner( 1228): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/PackageManager( 1017): Existing package
D/PackageManager( 1017): Renaming /data/app/vmdl456956178.tmp to /data/app/com.test.thalitest-1
,V/MediaScanner( 1228): processDirectory :  /storage/extSdCard
W/MediaScanner( 1228): Error opening directory, reason : Permission denied.
W/MediaScanner( 1228): 7klwibgf7fxlKdCbid7
,D/PackageManager( 1017): installNewPackageLI: Package{34988241 com.test.thalitest}
,I/PackageManager( 1017): scanFileNewer : com.test.thalitest
,V/MediaScanner( 1228):  prescan time: 26ms (DB items: 27)
V/MediaScanner( 1228):     scan time: 25ms (Caching mode: true), (makeEntry time: 17ms ~68%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1228): postscan time: 2ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1228):    total time: 53ms
V/MediaScanner( 1228): checked files: 10  directories : 17  (I: 0, U: 0)
,E/MTPJNIInterface( 5368): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,D/MediaScannerService( 1228): !@done scanning volume external
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ResourcesManager( 1357): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 1357): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1357): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1357): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.UploadsManager( 2016): End new media; added: 0, uploading: 0, time: 100 ms
,E/GmsUtils( 4478): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 4478): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
,E/CscFactoryReceiver( 1451): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1451): Media DB Scanner finished.
D/CscFactoryReceiver( 1451): start service to Set Ringtone
,D/ActivityManager( 1017): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1451): start service to Set Notification
,D/ActivityManager( 1017): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1451): start service to Set Alarmtone
,D/ActivityManager( 1017): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscUpdateService( 1451): onStart
E/CscUpdateService( 1451): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1451): only ringtone update
,D/CscUpdateService( 1451): onStart
E/CscUpdateService( 1451): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1451): only notification update
,D/CscUpdateService( 1451): onStart
E/CscUpdateService( 1451): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1451): only alarmtone update
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.indexservice, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/CscParser( 1451): update(): xml file exist
,E/CscParser( 1451): update(): xml file exist,
I/libpersona( 5409): KNOX_SDCARD checking this for 10006
E/Zygote  ( 5409): MountEmulatedStorage()
I/libpersona( 5409): KNOX_SDCARD not a persona
E/Zygote  ( 5409): v2
,I/ActivityManager( 1017): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5409 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/CSCSettings( 1451): Setting Ringtones (type) : 2
D/CscParser( 1451): MessageTone: null
W/CSCSettings( 1451): 1. Tag_Str: null
I/SELinux ( 5409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/CscParser( 1451): update(): xml file exist
E/SELinux ( 5409): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/CSCSettings( 1451): Setting Ringtones (type) : 1
D/CscParser( 1451): RingTone: null
W/CSCSettings( 1451): 1. Tag_Str: null,
,W/CSCSettings( 1451): Setting Ringtones (type) : 4
,D/CscParser( 1451): AlarmTone: null
W/CSCSettings( 1451): 1. Tag_Str: null
,D/TimaKeyStoreProvider( 5409): TimaSignature is unavailable
,D/ActivityThread( 5409): Added TimaKeyStore provider
,I/art     ( 1017): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
I/art     ( 1017): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.test.thalitest-1/arm/base.odex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
D/PackageManager( 1017): Running dexopt on: /data/app/com.test.thalitest-1/base.apk pkg=com.test.thalitest isa=arm vmSafeMode=false interpret_only=false
,I/ThumbnailProvider( 5409): ThumbnailProvider onCreate()
,I/DocumentBroadcastReceiver( 5409): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 5409): [START] processBroadcastIntent ...
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/dex2oat ( 5424): ----------------------------------------------------
I/dex2oat ( 5424): <SS>: S T A R T I N G . . .
I/dex2oat ( 5424): <SS>: going to process manifest for 32-bit...
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
,I/        ( 5424): SS_ART_lib [I]: Memory allocation: ctx
I/        ( 5424): SS_ART_lib [I]: Memory allocation: manifest_buf
I/        ( 5424): SS_ART_lib [I]: Parsing Manifest for SS stuff
I/        ( 5424): SS_ART_lib [I]: Memory allocation: ctx->libs
I/        ( 5424): SS_ART_lib [I]: Memory allocation: ctx->package_name
I/        ( 5424): SS_ART_lib [I]: Parsing completed
I/        ( 5424): SS_ART_lib [I]: permission is absent: /data/app/com.test.thalitest-1/base.apk
I/        ( 5424): SS_ART_lib [I]: Closing zip file: /data/app/com.test.thalitest-1/base.apk
I/        ( 5424): SS_ART_lib [I]: access to SS denied
I/        ( 5424): SS_ART_lib [I]: ctx will be cleaned
I/        ( 5424): SS_ART_lib [I]: ctx component will be cleaned: ctx->libs
I/        ( 5424): SS_ART_lib [I]: ctx component is cleaned: ctx->libs
I/        ( 5424): SS_ART_lib [I]: ctx component will be cleaned: ctx->package_name
I/        ( 5424): SS_ART_lib [I]: ctx component is cleaned: ctx->package_name
I/        ( 5424): SS_ART_lib [I]: ctx is cleaned
I/dex2oat ( 5424): /system/bin/dex2oat --zip-fd=11 --zip-location=/data/app/com.test.thalitest-1/base.apk --oat-fd=12 --art-fd=-1 --oat-location=/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/GalleryCacheReady( 4997): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 5409): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,I/SystemInfo( 5409): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 5409): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
,I/BroadcastProcessorService( 5409): [START] DocumentService startDocumentService
,D/GalleryCacheReady( 4997): handleMeidaScanFinish()
,D/FaceInterface( 4997): requestFaceScan() is called.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,W/LocalSuggestAlbumData( 4997): query fail: 
,W/LocalSuggestAlbumData( 4997): query fail: 
,I/FaceInterface( 4997): startFaceScan() : waiting 5 sec
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,I/DocumentService( 5409): DocumentService onCreate ... service
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5409): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5409): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/SystemInfo( 5409): [SIOP LEVEL] : 0
,D/BluetoothMediaBrowser( 2621):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/SettingSearch/SearchIntentReceiver( 1357): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 1357): LOCALE_CHANGED call search setting db finish!!
,D/BluetoothMediaBrowser( 2621): no now playing list
D/BluetoothMediaBrowser( 2621):  getNowPlayingId now playing id : -1
,I/DocumentService( 5409): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5409): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/File    ( 5409): fail readDirectory() errno=13
E/File    ( 5409): fail readDirectory() errno=13
,I/SystemInfo( 5409): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5409): [STOP DOCUMENTSERVICE] Attempting to stop the Service
,E/DocumentService( 5409): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :37
I/MediaStoreImporter( 4478): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,E/DocumentService( 5409): [THUMBNAIL] Total Time taken for each file :0
,E/        ( 5409): [INDEX] Total time taken for each file :0
,I/DocumentService( 5409): DocumentService onDestroy start
,I/DocumentService( 5409): DocumentService onDestroy end
,I/DocumentService( 5409): DocumentService cleanupEverything start
,I/IndexParserThreadsManager( 5409): InterruptedException: null
,I/SystemInfo( 5409): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5409): DocumentService cleanupEverything end
,I/Process ( 5409): Sending signal. PID: 5409 SIG: 9
,I/SettingSearch/SearchIntentReceiver( 1357): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/SettingSearch/SearchIntentReceiver( 1357): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1357): LOCALE_CHANGED call search setting db finish!!
,I/ActivityManager( 1017): Process com.samsung.indexservice (pid 5409)(adj 11) has died(48,1169)
,I/CalendarProvider2( 5350): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1017): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1017): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/dex2oat ( 5424): dex2oat took 456.937ms (threads: 4)
,I/PackageManager( 1017): do mInstaller.dexopt : 0
,D/PackageManager( 1017): Time to dexopt: 0.527 seconds
,W/System.err( 1017): java.io.FileNotFoundException: /data/app/com.test.thalitest-1: open failed: EISDIR (Is a directory)
,W/System.err( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err( 1017): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
,W/System.err( 1017): 	at android.content.pm.PackageParser.getHashValueOfPackage(PackageParser.java:5140)
W/System.err( 1017): 	at com.android.server.pm.PackageManagerService.saveHash(PackageManagerService.java:19520)
,W/System.err( 1017): 	at com.android.server.pm.PackageManagerService.access$5400(PackageManagerService.java:342)
W/System.err( 1017): 	at com.android.server.pm.PackageManagerService$19.run(PackageManagerService.java:19505)
W/System.err( 1017): Caused by: android.system.ErrnoException: open failed: EISDIR (Is a directory)
,W/System.err( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:446)
,W/System.err( 1017): 	... 5 more
,I/HarmonyEASService( 1017): Updating for all 1
,D/PackageManager( 1017): New package installed
,D/PackageManager( 1017): doPostInstall for uid{10155}
,D/PackageManager( 1017): token 1 to BM for possible restore
,V/BackupManagerService( 1017): restoreAtInstall pkg=com.test.thalitest token=1 restoreSet=0
,V/BackupManagerService( 1017): Finishing install immediately
,D/PackageManager( 1017): BM finishing package install for 1
,D/PackageManager( 1017): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 1017): [MSG] MCS_UNBIND
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010,
,I/PageBuddyNotiSvc( 4210): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,W/ResourcesManager( 1451): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 5443): MountEmulatedStorage()
E/Zygote  ( 5443): v2
I/libpersona( 5443): KNOX_SDCARD checking this for 1000
I/libpersona( 5443): KNOX_SDCARD not a persona
,I/SELinux ( 5443): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5443): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SELinux ( 5443): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1017): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=5443 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/PackageManager( 1017): [MSG] POST_INSTALL: observer{666169039}
D/PackageManager( 1017):           Handling post-install for 1
,I/ActivityManager( 1017): Killing 4776:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,D/RegisteredComponentCache( 1440): Collect Tech packages for Knox
,D/PersonaManager( 1440): isKioskContainerExistOnDevice
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PersonaManager( 1440): isKioskContainerExistOnDevice,
,D/TimaKeyStoreProvider( 5443): TimaSignature is unavailable
,D/ActivityThread( 5443): Added TimaKeyStore provider
,W/Settings( 1017): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,I/FaceInterface( 4997): startFaceScan() : going on
D/FaceInterface( 4997): startFaceScan() is called.
,E/SamsungIME( 1788): mOCRHelper is null
,D/RegisteredServicesCache( 1440): empty dynamic service
,D/RegisteredComponentCache( 1440): Collect Tech packages for Knox
,D/PersonaManager( 1440): isKioskContainerExistOnDevice
,D/AASAservice-UpdateReceiver( 5443): AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.google.android.gms, uid = -1
,I/splitIntent( 1017): intent=android.intent.action.PACKAGE_CHANGED will be not split. because same process=com.google.android.googlequicksearchbox:search is in other queue. index=1
I/splitIntent( 1017): base  index=1, name=com.google.android.googlequicksearchbox com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher
I/splitIntent( 1017): other index=7, name=com.google.android.googlequicksearchbox com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_CHANGED !! do not split it!!
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/art     ( 1228): Explicit concurrent mark sweep GC freed 7097(500KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 709us total 48.825ms
,D/ContentApp( 1228): startScan() is called.
,D/FaceValue( 1228): mSleepTime: 800
D/FaceValue( 1228): mMaxThreadNum: 2
,W/FaceValue( 1228): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,D/ContentApp( 1228): startScan() is end.
,E/Zygote  ( 5460): MountEmulatedStorage(),
,I/libpersona( 5460): KNOX_SDCARD checking this for 10057
E/Zygote  ( 5460): v2,
I/libpersona( 5460): KNOX_SDCARD not a persona
D/ContentApp( 1228): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1228): isNeedToRestore : start
,I/SELinux ( 5460): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5460): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5460): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher: pid=5460 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,I/ActivityManager( 1017): Killing 4800:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5460): TimaSignature is unavailable
,D/ActivityThread( 5460): Added TimaKeyStore provider
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PersonaManager( 1440): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1440): empty dynamic service
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,I/FaceInterface( 4997): startFaceScan() : going on
D/FaceInterface( 4997): startFaceScan() is called.
,D/ContentApp( 1228): startScan() is called.
,D/ContentApp( 1228): startScan() is end.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ContentApp( 1228): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1228): isNeedToRestore : start
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 120125(6MB) AllocSpace objects, 25(8MB) LOS objects, 27% free, 41MB/57MB, paused 6.119ms total 296.502ms
D/PackageManager( 1017): result of install: 1{666169039}
,I/art     ( 1017): WaitForGcToComplete blocked for 21.696ms for cause Explicit
,I/PackageManager( 1017): Observer no longer exists.
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/IntentResolver( 1017): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService( 1017): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService( 1017): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.backup.TRANSPORT_HOST
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/RCPManagerService( 1017): PackageReceiver onReceive()
D/RCPManagerService( 1017): App Installed with packageNAme = com.test.thalitest
,E/RCPManagerService( 1017):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: Attempt to invoke virtual method 'java.lang.String android.os.Bundle.getString(java.lang.String)' on a null object reference
D/RCPManagerService( 1017):  PackageReceiver onReceive() bundle null
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_ADDED
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/BackupManagerService( 1017): Removing schedule queue dupe of com.test.thalitest
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_ADDED
V/EnterpriseBillingPolicy( 1017): uID is 10155
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/PersonaPolicyManagerService( 1017): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/AlarmManagerEXT( 1017): com.test.thalitest(10155) is added to mUserAppList
D/KnoxMUMContainerPolicy( 1017): packageInstalledForExternalStorage com.test.thalitest
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 175651(11MB) AllocSpace objects, 2(3MB) LOS objects, 33% free, 27MB/41MB, paused 8.281ms total 206.860ms
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1017): no available spell checker services found
,E/Zygote  ( 5481): MountEmulatedStorage()
E/Zygote  ( 5481): v2
I/libpersona( 5481): KNOX_SDCARD checking this for 10015
I/libpersona( 5481): KNOX_SDCARD not a persona
I/SELinux ( 5481): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5481 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 5481): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux ( 5481): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/LocationManagerService( 1017): getProviders()=[passive]
,V/BackupManagerService( 1017): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 1017): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@187885c8
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/GCoreNlp( 1822): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/TimaKeyStoreProvider( 5481): TimaSignature is unavailable
,D/ActivityThread( 5481): Added TimaKeyStore provider,
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/ActivityManager( 1017): Killing 4837:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/CrashAnrDetector( 1017): onPackageAdded : com.test.thalitest
,I/Babel   ( 5270): Creating RTCS
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,W/libprocessgroup( 1017): failed to open /acct/uid_10085/pid_4776/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
W/libprocessgroup( 1017): failed to open /acct/uid_10094/pid_4800/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1017): applying state to connected service
,D/LocationProviderProxy( 1017): applying state to connected service
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5507): MountEmulatedStorage()
E/Zygote  ( 5507): v2
I/libpersona( 5507): KNOX_SDCARD checking this for 10032
I/libpersona( 5507): KNOX_SDCARD not a persona
,I/SELinux ( 5507): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5507 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
,I/SELinux ( 5507): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5507): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/Babel   ( 5270): Destroying RTCS
,I/ActivityManager( 1017): Killing 4854:com.wsomacp/u0a25 (adj 15): empty #31
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/GCoreNlp( 1822): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/TimaKeyStoreProvider( 5507): TimaSignature is unavailable
,D/ActivityThread( 5507): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 4890:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/FeatureConfig( 5507): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/PackagesMonitor( 4997): PackagesMonitor onReceive :com.google.android.gms
,W/ResourcesManager( 5507): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5507): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5507): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5507): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 5507): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 5507): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/libprocessgroup( 1017): failed to open /acct/uid_10072/pid_4837/cgroup.procs: No such file or directory
,D/LocationProviderProxy( 1017): applying state to connected service
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,W/ResourcesManager( 5507): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 5460): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5507): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 5528): MountEmulatedStorage()
E/Zygote  ( 5528): v2
I/libpersona( 5528): KNOX_SDCARD checking this for 10069
I/libpersona( 5528): KNOX_SDCARD not a persona
,I/SELinux ( 5528): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5528): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5528): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 5507): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/ActivityManager( 1017): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5528 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5528): TimaSignature is unavailable
,D/ActivityThread( 5528): Added TimaKeyStore provider
,W/ResourcesManager( 5507): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5507): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,I/art     (  309): Explicit concurrent mark sweep GC freed 8725(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 710us total 25.959ms
,W/ResourcesManager( 5507): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/libprocessgroup( 1017): failed to open /acct/uid_10025/pid_4854/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10003/pid_4890/cgroup.procs: No such file or directory
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 17.461ms
,D/FileShare-Server( 5528): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,W/ResourcesManager( 5507): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 599us total 16.806ms
,W/ResourcesManager( 5507): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 5544): MountEmulatedStorage()
,E/Zygote  ( 5544): v2
I/libpersona( 5544): KNOX_SDCARD checking this for 1000
I/SELinux ( 5544): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5544): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5544 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 5544): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5544): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/ResourcesManager( 5507): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5544): TimaSignature is unavailable
D/ActivityThread( 5544): Added TimaKeyStore provider
,I/UpdateIcingCorporaServi( 5460): UpdateCorporaTask done [took 128 ms] updated apps [took 127 ms] 
,I/ActivityManager( 1017): Killing 4907:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,W/ResourcesManager( 5507): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5544): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5507): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/GalaxyFinderApplication( 5507): system/finder_cp/cpdata.xml file not found
,E/Zygote  ( 5560): MountEmulatedStorage()
E/Zygote  ( 5560): v2
I/libpersona( 5560): KNOX_SDCARD checking this for 1000
I/libpersona( 5560): KNOX_SDCARD not a persona
,I/SELinux ( 5560): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5560): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5560): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=5560 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5025:com.sec.smartcard.manager/u0a153 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5560): TimaSignature is unavailable
,D/ActivityThread( 5560): Added TimaKeyStore provider
,D/KnoxSetupWizardDbHelper( 5560): dbMigrationFlag : false
,D/ShortcutReceiver( 5560):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5577): MountEmulatedStorage(),
I/libpersona( 5577): KNOX_SDCARD checking this for 10120
E/Zygote  ( 5577): v2,
I/libpersona( 5577): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5577 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 5577): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Killing 4720:com.android.mms/u0a46 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_10107/pid_4907/cgroup.procs: No such file or directory
,I/SELinux ( 5577): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5577): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 5577): TimaSignature is unavailable
,D/ActivityThread( 5577): Added TimaKeyStore provider
,W/ResourcesManager( 5577): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 5150): Thread[GAThread,5,main]: No campaign data found.
,D/CountryDetector( 1017): No listener is left
,W/libprocessgroup( 1017): failed to open /acct/uid_10153/pid_5025/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10046/pid_4720/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5600): MountEmulatedStorage()
,E/Zygote  ( 5600): v2
I/libpersona( 5600): KNOX_SDCARD checking this for 10028
I/libpersona( 5600): KNOX_SDCARD not a persona
,I/SELinux ( 5600): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5600): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5600): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5600 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5600): TimaSignature is unavailable
,D/ActivityThread( 5600): Added TimaKeyStore provider
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/Finsky  ( 5600): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5600): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5600): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5600): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 5600): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5600): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager( 1017): Killing 5068:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31
,D/Ads     ( 5600): Skipping gmscore version check
,D/Finsky  ( 5600): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1017): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5600): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 2016): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PackageBroadcastService( 2016): Null package name or gms related package.  Ignoreing.
,I/HomeSyncInstallReceiver( 1440): This pkg do not need BT addr. Do nothing
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1017): Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=14, mSplitNum[1]=23, mSplitNum[2]=36, mBgSplitQueueNum=3 divideNum= 11 r.nextReceiver= 2 receivers.size=47
I/splitIntent( 1017): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AASAservice-UpdateReceiver( 5443): AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
,I/AASAservice-TokenRule( 5443): parseToken()
,W/System.err( 5443): java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
W/System.err( 5443): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 5443): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
I/PackagesMonitor( 4997): PackagesMonitor onReceive :com.test.thalitest
W/System.err( 5443): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/System.err( 5443): 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:80)
W/System.err( 5443): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:52)
W/System.err( 5443): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 5443): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 5443): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 5443): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5443): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5443): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 5443): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5443): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5443): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5443): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 5443): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 5443): 	at libcore.io.Posix.open(Native Method)
W/System.err( 5443): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 5443): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 5443): 	... 14 more
E/AASAservice-TokenRule( 5443): parseToken() : TokenFile is null
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,E/AASAservice-UpdateReceiver( 5443): AASARuleUpdateResult() : Rule file is not exist.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5644): MountEmulatedStorage()
I/libpersona( 5644): KNOX_SDCARD checking this for 10152
E/Zygote  ( 5644): v2
I/libpersona( 5644): KNOX_SDCARD not a persona
I/SELinux ( 5644): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5644 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
I/SELinux ( 5644): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/SELinux ( 5644): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=5658 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/Zygote  ( 5658): MountEmulatedStorage()
E/Zygote  ( 5658): v2
,I/libpersona( 5658): KNOX_SDCARD checking this for 10046
I/libpersona( 5658): KNOX_SDCARD not a persona
D/TimaKeyStoreProvider( 5644): TimaSignature is unavailable
,D/ActivityThread( 5644): Added TimaKeyStore provider
,I/SELinux ( 5658): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5658): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5658): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5068/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5658): TimaSignature is unavailable
,D/ActivityThread( 5658): Added TimaKeyStore provider
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ContextImpl( 5117): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 5644): (284) automatic index on shooting_modes(title_id)
,W/ResourcesManager( 5658): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5658): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5658): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5658): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5658): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5658): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,I/Icing   ( 2016): Storage manager: low false usage 1.75MB avail 10.16GB capacity 11.68GB
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5684): MountEmulatedStorage()
I/libpersona( 5684): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5684): v2
I/libpersona( 5684): KNOX_SDCARD not a persona
I/SELinux ( 5684): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5684): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5684 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 5684): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
D/Mms/MmsApp( 5658): [start]    onCreate() consume time = 0.0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5684): TimaSignature is unavailable
,D/ActivityThread( 5684): Added TimaKeyStore provider
,E/Zygote  ( 5701): MountEmulatedStorage(),
I/libpersona( 5701): KNOX_SDCARD checking this for 10156
E/Zygote  ( 5701): v2
I/libpersona( 5701): KNOX_SDCARD not a persona
,I/SELinux ( 5701): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5701 uid=10156 gids={50156, 9997} abi=armeabi-v7a
I/SELinux ( 5701): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5701): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5714): MountEmulatedStorage()
,E/Zygote  ( 5714): v2
I/libpersona( 5714): KNOX_SDCARD checking this for 1000
I/libpersona( 5714): KNOX_SDCARD not a persona
,I/SELinux ( 5714): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5714 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5714): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5714): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5701): TimaSignature is unavailable
,D/ActivityThread( 5701): Added TimaKeyStore provider
,W/ResourcesManager( 5684): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5714): TimaSignature is unavailable
,D/ActivityThread( 5714): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 5086:com.samsung.android.app.powersharing/u0a122 (adj 15): empty #31
,I/TapandpayWidget:TapandpayAppWidgetProvider( 5701): onReceive()
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5701): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,I/TapandpayWidget:Utils( 5701): Clear T&P info.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_LOG( 5714): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5714): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5714): new DMDBOpenHelper instance
,E/Zygote  ( 5736): MountEmulatedStorage()
,E/Zygote  ( 5736): v2
I/libpersona( 5736): KNOX_SDCARD checking this for 10091
I/libpersona( 5736): KNOX_SDCARD not a persona
,I/SELinux ( 5736): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5736): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5736): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5736 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 5191:com.sec.android.app.sns3/u0a33 (adj 15): empty #31
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5701): Widget is not attached.
,D/TimaKeyStoreProvider( 5736): TimaSignature is unavailable
,D/ActivityThread( 5736): Added TimaKeyStore provider
,W/art     ( 5658): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 134.807ms
,I/PCWCLIENTTRACE_PushUtil( 5714): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5714): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5714): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5714): [onReceive] - android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1017): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5600): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5751): MountEmulatedStorage()
E/Zygote  ( 5751): v2
I/libpersona( 5751): KNOX_SDCARD checking this for 10010
I/libpersona( 5751): KNOX_SDCARD not a persona
,I/SELinux ( 5751): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5751): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5751): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5751 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,W/libprocessgroup( 1017): failed to open /acct/uid_10122/pid_5086/cgroup.procs: No such file or directory
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/art     (  309): Explicit concurrent mark sweep GC freed 8747(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 649us total 24.522ms,
,D/TimaKeyStoreProvider( 5751): TimaSignature is unavailable
D/ActivityThread( 5751): Added TimaKeyStore provider
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 18.262ms
,D/Mms/TelephonyPermission( 5658): start operation mode monitor
,D/Mms/ArtClassLoader( 5658): init before art
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 681us total 18.149ms
,W/ResourcesManager( 5658): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Zygote  ( 5767): MountEmulatedStorage()
,E/Zygote  ( 5767): v2
I/libpersona( 5767): KNOX_SDCARD checking this for 1000
I/libpersona( 5767): KNOX_SDCARD not a persona
,I/SELinux ( 5767): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=5767 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3983:com.sec.spp.push/u0a35 (adj 15): empty #31
,I/SELinux ( 5767): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5767): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 5226:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31
,D/Mms/TelephonyPermission( 5658): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission( 5658): isDefault true
,D/Mms/MmsApp( 5658): onCreate() com.android.mms
,D/TimaKeyStoreProvider( 5767): TimaSignature is unavailable
,D/ActivityThread( 5767): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10033/pid_5191/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10035/pid_3983/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10035/pid_5226/cgroup.procs: No such file or directory
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{36924178 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/Mms/MmsApp( 5658): [start]    initCountryIso consume time = 399.07599
,D/CountryDetector( 1017): The first listener is added
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/Mms/MmsApp( 5658): [end]    initCountryIso consume time = 19.792604
D/Mms/MmsConfig( 5658): [start]    MmsConfig.init() consume time = 0.091302
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageBroadcastService( 2016): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 2016): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2016): Loading module APK com.google.android.play.games
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/MmsConfig( 5658): before partial update
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/Mms/MmsConfig( 5658): Load Resize quality : 80
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/EasySignUpManager_1.0.1( 5658): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 5658): isAuth is false
,D/Mms/MmsConfig( 5658): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsSmsProvider( 1451): query,matched:2117, calling pid = 5658
,D/TP/MmsSmsProvider( 1451): match 2117:Elapsed time : 2.737 ms
,D/EasySignUpManager_1.0.1( 5658): isAuth is false
,D/EasySignUpManager_1.0.1( 5658): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 5658): mps_code.dat does not exist
,E/CscParser( 5658): customer_path =/system/csc/customer.xml
E/CscParser( 5658): fileName + /system/csc/customer.xml
,I/DBG_POLICYDM( 5767): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 5767): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,E/CscParser( 5658): mps_code.dat does not exist
E/CscParser( 5658): customer_path =/system/csc/customer.xml
E/CscParser( 5658): fileName + /system/csc/customer.xml
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,D/CscParser( 5658): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 5658):  enable multiwindow = true
,E/PhotosPlugin( 5736): Loading PhotosPlugin
,I/DBG_POLICYDM( 5767): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 5767): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,E/SMD     (  288): DCD OFF
,E/Mms/MessageUtils( 5658): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5658): updateCountryIso : update country iso info 
,I/DBG_POLICYDM( 5767): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 5767): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,D/Mms/MmsConfig( 5658): [end]    init() consume time = 127.454375
,D/Mms/Contact( 5658): [start]    init() consume time = 0.812031
,D/TP/MmsSmsProvider( 1451): query,matched:13, calling pid = 5658
,D/Mms/Contact( 5658): [end]    init consume time = 17.429375
,D/TP/MmsSmsProvider( 1451): match 13:Elapsed time : 1.716 ms
,D/Mms/DraftCache( 5658): [start]    rebuildCache consume time = 17.598021
,D/TP/MmsSmsProvider( 1451): query,matched:12, calling pid = 5658
,D/TP/MmsSmsProvider( 1451): match 12:Elapsed time : 1.166 ms,
D/Mms/DraftCache( 5658): [end]    rebuildCache consume time = 9.725156
,I/DBG_POLICYDM( 5767): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,I/DBG_POLICYDM( 5767): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,D/Mms/MethodReflector( 5658): getSubId is called
D/Mms/TelephonyUtils( 5658): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 5658): getTelephonyProperty is called
,D/Mms/DownloadManager( 5658): roaming -> false (slotId = 0)
,I/DBG_POLICYDM( 5767): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
D/Mms/DownloadManager( 5658): [NotificationTransaction] getAutoDownloadState simSlot : 0
,D/Mms/DownloadManager( 5658): auto download without roaming -> true
,D/Mms/DownloadManager( 5658): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,I/DBG_POLICYDM( 5767): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,D/Mms/MethodReflector( 5658): getSubId is called
,I/DBG_POLICYDM( 5767): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,D/Mms/MethodReflector( 5658): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5658): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5658): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5658): getTelephonyProperty is called
D/Mms/DownloadManager( 5658): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5658): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5658): auto download without roaming -> true
D/Mms/DownloadManager( 5658): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5658): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5658): mAutoDownload ------> true
,I/DBG_POLICYDM( 5767): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 5767): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5802): MountEmulatedStorage()
E/Zygote  ( 5802): v2
I/libpersona( 5802): KNOX_SDCARD checking this for 10035
I/libpersona( 5802): KNOX_SDCARD not a persona
,I/SELinux ( 5802): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5802): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5802): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5802 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5246:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5802): TimaSignature is unavailable
D/ActivityThread( 5802): Added TimaKeyStore provider
,D/ComposerPerformance( 5658): 1455029358297 ms / [DONE] Composer constructor
,E/CII     ( 5658): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 5658): ReservationManager()
,I/Mms/ReservationManager( 5658): resetAfterConnected()
,D/TP/MmsSmsProvider( 1451): query,matched:7, calling pid = 5658
,D/TP/MmsSmsProvider( 1451): match 7:Elapsed time : 1.659 ms
,I/DBG_POLICYDM( 5767): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/Mms/ReservationManager( 5658): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/Conversation( 5658): [start]    init() consume time = 174.555
,D/Mms/MmsApp( 5658): [end]    onCreate() consume time = 2.790313
,W/libprocessgroup( 1017): failed to open /acct/uid_10035/pid_5246/cgroup.procs: No such file or directory
,D/TP/MmsSmsProvider( 1451): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1451): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1451): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1451): sUpgradeVersion = 0, db.getVersion() = 81
,D/TP/MmsSmsProvider( 1451): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1451): need read changed broadcast:false
,D/Mms/Conversation( 5658): [end]    init consume time = 13.71151
,D/Mms/DownloadManager( 5658): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 5658): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 5658): getSubId is called
D/Mms/TelephonyUtils( 5658): getLongSubId from simSlot 0, return Value = -1
E/SPPClientService( 5802): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5802): [PushClientApplication] Push log off : This is Ship build version
D/Mms/MessagingNotification( 5658): [start]    init() consume time = 10.668906
D/Mms/MethodReflector( 5658): getTelephonyProperty is called
D/Mms/DownloadManager( 5658): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5658): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5658): auto download without roaming -> true
D/Mms/DownloadManager( 5658): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5658): mAutoDownload ------> true
,I/DBG_POLICYDM( 5767): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 5802): PushLog.txt file is not deleted.
D/SPPClientService( 5802): PushLog.txt file is not deleted.
,D/SPPClientService( 5802): ============PushLog. stop!
,I/DBG_POLICYDM( 5767): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 5767): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7,
,I/DBG_POLICYDM( 5767): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7,
,I/Icing   ( 2016): updateResources: need to parse f{com.google.android.gms}
,E/Zygote  ( 5821): MountEmulatedStorage()
I/libpersona( 5821): KNOX_SDCARD checking this for 10038
E/Zygote  ( 5821): v2
I/libpersona( 5821): KNOX_SDCARD not a persona
I/SELinux ( 5821): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5821 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 5295:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/SELinux ( 5821): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5821): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/Mms/MessagingNotification( 5658): [end]    init consume time = 34.990105
,D/Mms/FreeMessageStatusReceiver( 5658): onReceive, action : android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1017): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,I/DBG_POLICYDM( 5767): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
D/TimaKeyStoreProvider( 5821): TimaSignature is unavailable
,D/ActivityThread( 5821): Added TimaKeyStore provider
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5767): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,D/Mms/SpamFilter( 5658): [start]    SpamFilter fill() begin consume time = 33.697552
,D/Mms/Synchronizer( 5658): [start]    doSync consume time = 3.280104
,E/Zygote  ( 5840): MountEmulatedStorage()
,E/Zygote  ( 5840): v2
I/libpersona( 5840): KNOX_SDCARD checking this for 10047
I/libpersona( 5840): KNOX_SDCARD not a persona
,I/SELinux ( 5840): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5840): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/DBG_POLICYDM( 5767): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
I/ActivityManager( 1017): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5840 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/DBG_POLICYDM( 5767): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 5767): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
E/SELinux ( 5840): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5767): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 5767): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/TP/MmsSmsProvider( 1451): query,matched:400, calling pid = 5658
,I/DBG_POLICYDM( 5767): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/02/16/12:12:08
,I/DBG_POLICYDM( 5767): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/02/09/15:49:18
,D/TP/MmsSmsProvider( 1451): query,matched:0, calling pid = 5658
,I/DBG_POLICYDM( 5767): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
V/TP/MmsSmsProvider( 1451): getSimpleConversations entered.
,I/DBG_POLICYDM( 5767): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,D/Mms/FreeMessageReceiverService( 5658): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5658): onHandleIntent: ACTION_PACKAGE_ADDED
,I/DBG_POLICYDM( 5767): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 5767): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 5767): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 5767): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 5767): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 5767): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] ,
D/TP/MmsSmsProvider( 1451): match 0:Elapsed time : 21.405 ms
I/ActivityManager( 1017): Killing 5335:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
I/DBG_POLICYDM( 5767): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
I/DBG_POLICYDM( 5767): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,D/TimaKeyStoreProvider( 5840): TimaSignature is unavailable,
D/ActivityThread( 5840): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 1451): update, matched:300, calling pid = 5658
V/TP/MmsSmsProvider( 1451): syncDBData start
V/TP/MmsSmsProvider( 1451): syncDBData sms end
V/TP/MmsSmsProvider( 1451): syncDBData mms end
,V/TP/MmsSmsProvider( 1451): syncDBData end
,D/Mms/Synchronizer( 5658): [end]    doSync consume time = 73.228229
,I/DBG_POLICYDM( 5767): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Mms/ArtClassLoader( 5658): init [DONE] art
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5840): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5840): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5840): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 5821): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5821): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5767): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5295/cgroup.procs: No such file or directory
,E/Zygote  ( 5861): MountEmulatedStorage(),
E/Zygote  ( 5861): v2
I/libpersona( 5861): KNOX_SDCARD checking this for 10072
I/libpersona( 5861): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5861 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,I/SELinux ( 5861): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5861): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5861): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/SpamFilter( 5658): [end]    SpamFilter fill() finished consume time = 58.77401
,W/libprocessgroup( 1017): failed to open /acct/uid_10142/pid_5335/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5861): TimaSignature is unavailable
,D/ActivityThread( 5861): Added TimaKeyStore provider
,D/ChimeraCfgMgr( 2016): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2016): Module APK com.google.android.play.games already loaded
,D/BadgeProvider( 5861): onCreate
,D/BadgeProvider( 5861): DatabaseHelper
,D/Mms/MessagingNotification( 5658): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1451): query,matched:26, calling pid = 5658
,D/TP/SmsProvider( 1451): match 26:Elapsed time : 2.180 ms
,D/ChimeraCfgMgr( 2016): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 35678(2005KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 27MB/40MB, paused 3.067ms total 188.289ms
,D/TP/MmsSmsProvider( 1451): query,matched:6, calling pid = 5658
,D/TP/MmsSmsProvider( 1451): match 6:Elapsed time : 1.243 ms
,I/art     ( 1017): WaitForGcToComplete blocked for 125.641ms for cause HeapTrim
,D/AsyncTaskServiceImpl( 2016): Submit a task: k
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1017): Killing 5350:com.android.providers.calendar/u0a42 (adj 15): empty #31
,D/ChimeraCfgMgr( 2016): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5880): MountEmulatedStorage()
E/Zygote  ( 5880): v2
I/libpersona( 5880): KNOX_SDCARD checking this for 10025
I/libpersona( 5880): KNOX_SDCARD not a persona
,I/SELinux ( 5880): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5880): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1017): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5880 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,E/SELinux ( 5880): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5880): TimaSignature is unavailable
,D/ActivityThread( 5880): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 5132:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/ChimeraCfgMgr( 2016): Loading module com.google.android.gms.vision from APK com.google.android.gms
,W/ResourcesManager( 5880): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/k       ( 2016): Processing package: com.test.thalitest
,D/GassUtils( 2016): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,D/k       ( 2016): Found info for package com.test.thalitest in db.
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/OMACP   ( 5880): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp( 5658): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,W/libprocessgroup( 1017): failed to open /acct/uid_10042/pid_5350/cgroup.procs: No such file or directory
,I/OMACP   ( 5880): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 5880): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 5880): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 5880): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 5880): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 5880): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 5880): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,W/BaseAppContext( 2016): Using Auth Proxy for data requests.
W/BaseAppContext( 2016): Using Auth Proxy for data requests.
,I/OMACP   ( 5880): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 5880): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 5880): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 5880): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 5880): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 5880): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,W/libprocessgroup( 1017): failed to open /acct/uid_10150/pid_5132/cgroup.procs: No such file or directory
,W/BaseAppContext( 2016): Using Auth Proxy for data requests.
,W/BaseAppContext( 2016): Using Auth Proxy for data requests.
,D/MyFiles ( 5840): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,I/TactileAssist( 1017): enable value -1
,I/TactileAssist( 1017): internal enable value -1
,I/TactileAssist( 1017): intensity value -1
I/TactileAssist( 1017): saveAppList value true
,W/BaseAppContext( 2016): Using Auth Proxy for data requests.
W/BaseAppContext( 2016): Using Auth Proxy for data requests.
,I/TactileAssist( 1017): List of disabled apps :
,E/installd(  284): system dir 0 : /system/app/
,E/installd(  284): system dir 1 : /system/priv-app/
E/installd(  284): system dir 2 : /vendor/app/
E/installd(  284): system dir 3 : /oem/app/
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5901): MountEmulatedStorage(),
,D/PackageManager( 1017): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/Zygote  ( 5901): v2
I/libpersona( 5901): KNOX_SDCARD checking this for 10053,
,I/libpersona( 5901): KNOX_SDCARD not a persona
,I/SELinux ( 5901): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5901 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/BaseAppContext( 2016): Using Auth Proxy for data requests.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SELinux ( 5901): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5901): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5901): TimaSignature is unavailable
D/ActivityThread( 5901): Added TimaKeyStore provider
,W/ResourcesManager( 5901): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5767): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,D/Compatibility( 5901): onReceive() it will make start service
,D/ActivityManager( 1017): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,I/DBG_POLICYDM( 5767): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/Compatibility( 5901): onHandleIntent()
,D/Compatibility( 5901): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
,D/Compatibility( 5901): found: 2
I/UpdateIcingCorporaServi( 5460): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PeopleDatabaseHelper( 2016): cleanUpNonGplusAccounts done.
,D/Compatibility( 5901): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5901): skipping ResolveInfo{f14978f com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5901): considering ResolveInfo{398c4a1c com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5901): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5901): enabling receiver ResolveInfo{2cf84625 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5901): enabling receiver ResolveInfo{30b353fa com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5901): enabling receiver ResolveInfo{d4d1dab com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5901): enabling receiver ResolveInfo{621ec08 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/DBG_POLICYDM( 5767): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,D/Compatibility( 5901): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,I/SL_DEBUG( 5821): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 5821): isLoggable:: SL_DEBUG_EXIST = false
,I/DBG_POLICYDM( 5767): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,I/DBG_POLICYDM( 5767): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,I/UpdateIcingCorporaServi( 5460): UpdateCorporaTask done [took 114 ms] updated apps [took 114 ms] 
,I/ActivityManager( 1017): Killing 4977:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5821): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,W/SQLiteConnectionPool( 2016): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,W/libprocessgroup( 1017): failed to open /acct/uid_10040/pid_4977/cgroup.procs: No such file or directory
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5821): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,I/Icing   ( 2016): Internal init done: storage state 0
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/GAV2    ( 5736): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/Icing   ( 2016): Post-init done
,I/Icing   ( 2016): updateResources: need to parse f{com.google.android.gms}
,E/Zygote  ( 5935): MountEmulatedStorage()
E/Zygote  ( 5935): v2
I/libpersona( 5935): KNOX_SDCARD checking this for 10041
I/libpersona( 5935): KNOX_SDCARD not a persona
,I/SELinux ( 5935): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5935 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5935): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5935): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5935): TimaSignature is unavailable
,D/ActivityThread( 5935): Added TimaKeyStore provider
,I/SA      ( 5935): [SSP] onCreated
,I/ActivityManager( 1017): Killing 4478:com.google.android.music:main/u0a111 (adj 15): empty #31
,I/SA      ( 5935): [TPM] There is no property file
,I/SA      ( 5935): [SCU] isHaveSA() - false
,I/SA      ( 5935): [TPM] getModelProperty : null
I/SA      ( 5935): [TPM] getCSCProperty : null
,I/SA      ( 5935): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5935): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5935): [DM] TFT FEATURE: false
,I/SA      ( 5935): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 5935): [DM] init START
,I/SA      ( 5935): [DM] This device is not a Vodafone
,W/ResourceType( 5935): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 5935): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 5935): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 5935): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 5935): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 5935): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5935): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 5935): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 5935): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 5935): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 5935): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5935): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 5935): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 5935): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 5935): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5935): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 5935): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 5935): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 5935): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 5935): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 5935): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 5935): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 5935): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 5935): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5935): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 5935): [SCU] isHaveSA() - false
I/SA      ( 5935): support phone number id : false
I/SA      ( 5935): [DM] Supports Ref Jpn : true
,I/SA      ( 5935): [DM] init END
,I/SA      ( 5935): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 5935): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
,I/ActivityManager( 1017): Killing 5150:com.google.android.gm/u0a101 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1017): failed to open /acct/uid_10111/pid_4478/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5964): MountEmulatedStorage()
I/libpersona( 5964): KNOX_SDCARD checking this for 10100
E/Zygote  ( 5964): v2
I/libpersona( 5964): KNOX_SDCARD not a persona
I/SELinux ( 5964): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5964 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 4821:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
I/SELinux ( 5964): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5964): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,W/GAV2    ( 5736): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1822): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 5964): TimaSignature is unavailable
,D/ActivityThread( 5964): Added TimaKeyStore provider
,W/GAV2    ( 5736): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageIntentReceiver( 5964): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 5964): Not GearManger package! 
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/AccountFeatureHelper( 5736): Write apps_features disabled false
,E/Zygote  ( 5986): MountEmulatedStorage()
,E/Zygote  ( 5986): v2
I/libpersona( 5986): KNOX_SDCARD checking this for 1000
I/libpersona( 5986): KNOX_SDCARD not a persona,
,I/SELinux ( 5986): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5986): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5986): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5986 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5314:com.android.calendar/u0a135 (adj 15): empty #31
W/libprocessgroup( 1017): failed to open /acct/uid_10101/pid_5150/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10134/pid_4821/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5986): TimaSignature is unavailable
,D/ActivityThread( 5986): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 6001): MountEmulatedStorage(),
E/Zygote  ( 6001): v2
I/libpersona( 6001): KNOX_SDCARD checking this for 1000
,I/libpersona( 6001): KNOX_SDCARD not a persona
,I/SELinux ( 6001): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1017): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6001 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 5270:com.google.android.talk/u0a104 (adj 15): empty #31
,I/SELinux ( 6001): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6001): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6001): TimaSignature is unavailable
,D/ActivityThread( 6001): Added TimaKeyStore provider
,I/art     (  309): Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 643us total 23.882ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 16.748ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 16.837ms
,D/ChimeraCfgMgr( 2016): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2016): Module APK com.google.android.play.games already loaded
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/FaceInterface( 4997): startFaceScan() : going on
D/AcmsPackageEventListener( 6001): Received: android.intent.action.PACKAGE_ADDED
D/FaceInterface( 4997): startFaceScan() is called.
,W/ContextImpl( 6001): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,D/ContentApp( 1228): startScan() is called.
D/ContentApp( 1228): startScan() is end.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/AcmsService( 6001): Enter Oncreate
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/AcmsServiceMonitor( 6001): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6001): creating AcmsCore
,D/AcmsCore( 6001): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6001): AcmsCore
,D/AcmsCore( 6001): init
D/AcmsCore( 6001): Looper handler is not null
D/AcmsCore( 6001): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6001): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6001): Incrementing - Counter value: 1
D/AcmsCore( 6001): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 6001): onStartCommand
D/AcmsService( 6001): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6001): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6001): Incrementing - Counter value: 2
D/AcmsService( 6001): Incremented Counter Value : onStartCommand
,D/ContentApp( 1228): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1228): isNeedToRestore : start
,D/AcmsCertificateMngr( 6001): AcmsCertificateMngr
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityThread( 6001): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsRevocationMngr( 6001): AcmsRevocationMngr
,W/libprocessgroup( 1017): failed to open /acct/uid_10135/pid_5314/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10104/pid_5270/cgroup.procs: No such file or directory
,D/AcmsService( 6001): Inside handle Intent
,D/AcmsService( 6001): App added - package name: com.test.thalitest
,D/AcmsCore( 6001): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6001): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsServiceMonitor( 6001): Incrementing - Counter value: 3
D/AcmsCore( 6001): Incremented Counter Value: postToAcmsCoreHandler =>2
,D/AcmsService( 6001): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6001): Decrementing - Counter value: 2
,I/splitIntent( 1017): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,V/AlarmManager( 1017): waitForAlarm result :4
,I/Mms/MmsApp( 5658):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5658): [start]    fillCache consume time = 1773.150156
,D/Mms/ComposeMessageFragment( 5658): fillCache, easy = false
,D/AbsListView( 5658): Get MotionRecognitionManager
,D/MotionRecognitionService( 1017):  ssp status : false
,D/Mms/ComposeMessageFragment( 5658): [end]    fillCache consume time = 71.463125
,I/CheckinService( 2016): Done disabling old GoogleServicesFramework version
,D/Mms/BubbleViewCache( 5658): fillCache bubble = 1
,I/Icing   ( 2016): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,D/Icing   ( 2016): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2016): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1017): Killing 5528:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,D/SensorService( 1017): [SO] 0.038 0.077 10.113
,W/libprocessgroup( 1017): failed to open /acct/uid_10069/pid_5528/cgroup.procs: No such file or directory
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 400
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/DBG_POLICYDM( 5767): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5767): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5767): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5767): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5767): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5767): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5767): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/AcmsKeyStoreHelper( 6001):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 6001): Key Store exist
I/AcmsKeyStoreHelper( 6001): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 6001):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 6001): getKeyStoreForApplication success 
D/AcmsCore( 6001): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6001): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6001): Decrementing - Counter value: 1
D/AcmsCore( 6001): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6001): This is NOT a valid MirrorLink app
D/AcmsCore( 6001): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6001): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6001): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6001): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6001): getSvcCounter - Counter value: 0
,D/AcmsService( 6001): Enter onDestroy
I/AcmsService( 6001): cleanUp(): inside service clean up
D/AcmsCore( 6001): AcmsCore: inside DeInit
D/AcmsCore( 6001): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6001): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6001): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6001): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6001): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6001): getSvcCounter - Counter value: 0
,D/AcmsService( 6001): killing acms process
I/Process ( 6001): Sending signal. PID: 6001 SIG: 9
,I/ActivityManager( 1017): Process ACMS.Process (pid 6001)(adj 0) has died(84,1188)
,E/SMD     (  288): DCD OFF
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,I/iu.UploadsManager( 2016): End new media; added: 0, uploading: 0, time: 61 ms
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 5600): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1822): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PackageManager( 1017): [MSG] MCS_UNBIND
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1822): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1822): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5600): Thread-967(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5600): Thread-967(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5600): Thread-967(ApacheHTTPLog):isShipBuild true
,I/System.out( 5600): Thread-967(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5600): Thread-967(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10028
,I/qtaguid ( 5600): Tagging socket 44 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5600, getuid(): 10028
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700",
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qtaguid ( 5600): Tagging socket 48 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5600, getuid(): 10028
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{94969e5 u0 com.samsung.android.MtpApplication/.MtpService}
,I/qtaguid ( 5600): Untagging socket 44
,I/System.out( 5600): Thread-967 calls detatch()
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1822): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5600): Thread-968(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5600): Thread-968(ApacheHTTPLog):isShipBuild true
,I/System.out( 5600): Thread-968(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 5600): Thread-968(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5600): Untagging socket 44
,I/qtaguid ( 5600): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5600): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5600): untagSocket(44) failed with errno -22
I/System.out( 5600): Thread-968 calls detatch()
,D/Finsky  ( 5600): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1822): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6036): MountEmulatedStorage()
E/Zygote  ( 6036): v2
I/libpersona( 6036): KNOX_SDCARD checking this for 10012
,I/libpersona( 6036): KNOX_SDCARD not a persona
,I/SELinux ( 6036): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6036): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1017): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6036 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
E/SELinux ( 6036): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5600): Thread-967(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5600): Thread-967(ApacheHTTPLog):isShipBuild true
I/System.out( 5600): Thread-967(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5600): Thread-967(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/TimaKeyStoreProvider( 6036): TimaSignature is unavailable
,D/ActivityThread( 6036): Added TimaKeyStore provider
,W/ResourcesManager( 6036): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6036): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6036): VM with version 2.1.0 has multidex support
I/MultiDex( 6036): install
I/MultiDex( 6036): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6036): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 5600): Untagging socket 44
,I/qtaguid ( 5600): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5600): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5600): untagSocket(44) failed with errno -22
I/System.out( 5600): Thread-967 calls detatch()
,W/ActivityThread( 6036): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6036): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39aa182d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6036): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1017): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1017): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1017): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ChimeraCfgMgr( 6036): Reading stored module config
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1822): callingUid 10012, callindPid: 1822
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1822): [251] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6036): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1822): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2016): Restart initialization of location
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1822): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/NativeLibraryUtils( 6036): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6036): Connecting to CarCallService...
,E/SMD     (  288): DCD OFF
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 30889(1671KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/40MB, paused 2.696ms total 152.046ms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/GCoreFlp( 1822): No location to return for getLastLocation()
,W/FusedLocationProvider( 1822): location=null
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 6036): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6036): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6036): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6036): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6036): Creating a new PhoneAdapter instance
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6036): setListener: com.google.android.gms.car.dn@d9700e0
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6036): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6036): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 6036): Package validated; name: com.android.vending
,V/Finsky  ( 5600): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1822): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5600): Thread-968(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5600): Thread-968(ApacheHTTPLog):isShipBuild true
I/System.out( 5600): Thread-968(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5600): Thread-968(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5600): Untagging socket 44
,I/qtaguid ( 5600): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5600): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5600): untagSocket(44) failed with errno -22
I/System.out( 5600): Thread-968 calls detatch()
,W/ResourcesManager( 5600): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5600): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5600): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5600): [1] DailyHygiene.access$600: Logging device features
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/DeviceConnectionService( 1822): client connected with version: 8296000
,D/Finsky  ( 5600): [989] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1822): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5600): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5600): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/System.out( 5600): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5600): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5600): (HTTPLog)-Static: isShipBuild true
I/System.out( 5600): (HTTPLog)-Thread-978-625092720: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5600): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10028
,I/System.out( 5600): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SSRM:n  ( 1017): SIOP:: AP = 350
,I/ActivityManager( 1017): Killing 5443:com.samsung.aasaservice/1000 (adj 15): empty #31
I/ActivityManager( 1017): Killing 5560:com.sec.knox.foldercontainer/1000 (adj 15): empty #32
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SensorService( 1017): [SO] 0.019 0.057 10.075
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5560/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5443/cgroup.procs: No such file or directory
,D/PowerManagerService( 1017): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1017): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1017): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1017): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1017): getFinalBrightness : Summary is 1 -> 1
,D/lights  ( 1017): lcd : 1 +
,D/DisplayPowerController( 1017): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1017): lcd : 1 -
,D/DisplayPowerController( 1017): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1017): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{2532962b u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,E/SMD     (  288): DCD OFF,
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/CAR.SERVICE( 6036): mConnectedToCar = false, abort
,E/ActivityThread( 6036): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3926e0c8 that was originally bound here
E/ActivityThread( 6036): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3926e0c8 that was originally bound here
E/ActivityThread( 6036): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6036): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6036): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6036): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6036): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6036): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6036): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6036): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6036): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6036): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6036): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6036): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6036): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6036): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 6036): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 6036): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 6036): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6036): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6036): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6036): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6036): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6036): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6036): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 6036): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@18b89ee3 that was originally bound here
E/ActivityThread( 6036): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@18b89ee3 that was originally bound here
E/ActivityThread( 6036): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6036): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6036): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6036): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6036): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6036): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6036): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6036): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6036): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6036): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6036): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6036): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6036): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 6036): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 6036): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 6036): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6036): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6036): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6036): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6036): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6036): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6036): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1017): Unbind failed: could not find connection for android.os.BinderProxy@3b6add50
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/IcingInternalCorpora( 2016): getNumBytesRead when not calculated.
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 1017): waitForAlarm result :8
,E/Watchdog( 1017): !@Sync 2,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/PowerManagerService( 1017): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1017): Nap time (uid 1000)...
,D/PowerManagerService( 1017): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
,I/PowerManagerService( 1017): !@[ps] Screen__Off - 0 :  dream(timeout) (2)
,I/PowerManagerService( 1017): Going to sleep due to screen timeout (uid 1000)...
,D/DisplayPowerController( 1017): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1017): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1017): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService( 1017): [PWL] sb acquire: PowerManagerService.Broadcasts
,V/WindowOrientationListener( 1017): WindowOrientationListener disabled
,D/SensorService( 1017): [SO] activate (ident=0xb921db08, enabled=0)
,I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/PowerManagerService( 1017): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService( 1017): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
,D/PowerManagerService( 1017): handleSandman : startDream(true)
,E/PowerManagerService( 1017): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService( 1017): Sleeping (uid 1000)...
,D/PowerManagerService( 1017): [s] UserActivityState : 4 -> 0
,I/SurfaceFlinger(  258): id=12 createSurf (720x1280),-1 flag=20004, DolorFade
,D/SensorManager( 1017): unregisterListener ::   
,D/KeyguardViewMediator( 1180): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1180): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1180): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1180): notifyScreenOffLocked
,D/PowerManagerService( 1017): Excessive delay in ColorFade : createSurface: 18ms,
,I/Adreno-EGL( 1017): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1017): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1017): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1017): Local Branch: 
I/Adreno-EGL( 1017): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1017): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1017):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
I/DBG_DM  ( 3103): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,D/KeyguardViewMediator( 1180): timeout : 5000
,V/ActivityThread( 3103): updateVisibility : ActivityRecord{15bd3c8c token=android.os.BinderProxy@287f06d3 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,E/SmartFaceService( 1017): onReceive: android.intent.action.SCREEN_ON
,D/KeyguardViewMediator( 1180): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 1180): handleNotifyScreenOff
D/VolumePanel( 1180): onScreenTurnedOff()
D/VolumePanel( 1180): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
W/System.err( 1017): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,D/VolumePanel( 1180): mCoverBroadcastReceiver: Screen OFF end
,W/System.err( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
,W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1017): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1017): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1017): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1017): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1017): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1017): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
E/SmartFaceService( 1017): fail to set sysfs 1
W/System.err( 1017): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1017): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1017): 	... 10 more
,D/SecKeyguardClockSingleView( 1180): onScreenTurnedOff
,D/PowerManagerService( 1017): Excessive delay in ColorFade : createEglContext: 59ms
,D/InputMethodManagerService( 1017): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
,D/PowerManagerService( 1017): Excessive delay in ColorFade : createEglSurface: 12ms
,D/MotionRecognitionService( 1017):   mReceiver.onReceive : ACTION_SCREEN_ON
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (175 us)
,E/MotionRecognitionService( 1017):  handler : SCREEN_ON end
,D/NotificationService( 1017): ACTION_SCREEN_ON
D/LightsService( 1017): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1017) 
,D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=on
,V/voice   (  283): voice_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
,D/PowerManagerService( 1017): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 19ms
,E/WifiNative-wlan0( 1017): do suspend false
,D/IpRemoteDisplayController( 1017): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 1017): Bridge Server is not available
,I/wpa_supplicant( 2077): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2077): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2077): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2077): Scan requested (ret=0) - scan timeout 30 seconds
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/PowerManagerService( 1017): Excessive delay in ColorFade : initGLShaders: 34ms
,D/PowerManagerService( 1017): Excessive delay in ColorFade prepare: 153ms
,D/DisplayPowerController( 1017): ColorFade: onAnimationStart
D/DisplayPowerController( 1017): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1017): performScreenOffTransition : no brightness animation
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1017): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1017): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1440): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/accuweather( 1722): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1722): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1722): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/NfcService( 1440): call the applyRouting
,D/accuweather( 1722): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
,D/ActivityManager( 1017): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1788): getNextShiftState() cursorCapsMode : 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LightsService( 1017): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1017) 
,D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1017): write_int failed to open -1
D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService( 1017): turn on LED for fully charged
,D/SSRM:n  ( 1017): SIOP:: AP = 330
,W/System.err( 1017): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
E/SmartFaceService( 1017): onReceive: android.intent.action.SCREEN_OFF
W/System.err( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/SmartFaceService( 1017): fail to set sysfs 0
W/System.err( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1017): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1017): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1017): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1017): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1017): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1017): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1017): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1017): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1017): 	... 10 more
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
,D/MotionRecognitionService( 1017):   mReceiver.onReceive : ACTION_SCREEN_OFF
,D/SamsungIME( 1788): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,E/MotionRecognitionService( 1017):  handler : SCREEN_OFF end 
,D/NotificationService( 1017): ACTION_SCREEN_OFF
D/LightsService( 1017): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1017) 
,D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=off
V/voice   (  283): voice_set_parameters: enter: screen_state=off
D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,V/voice   (  283): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/BackgroundCompactionService( 1017): Schedule Type1 BGCompaction
,D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1305): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1305): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1305): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1305): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1455050880000
,D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1455029378960
D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/IpRemoteDisplayController( 1017): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 1017): Bridge Server is not available
,E/WifiNative-wlan0( 1017): do suspend true
D/daemonapp( 1305): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/PersonaManagerService( 1017): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1017): MSG_ACTION_SCREEN_OFF called
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1305): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,V/EmergencyMode( 1416): [EmergencyStateReceiver] binteractive [false] why[3]
,E/daemonapp( 1305): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/NfcService( 1440): call the applyRouting
,I/BatteryStatsDumper( 1017): In refreshStats isReason Screen ON/OFF: true
,D/accuweather( 1722): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1722): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
,D/DisplayPowerState( 1017): !@ ColorFade entry
,D/DisplayPowerController( 1017): ColorFade: onAnimationEnd
,D/lights  ( 1017): lcd : 0 +
,D/DisplayPowerController( 1017): getFinalBrightness : Summary is 0 -> 0
,D/DisplayPowerController( 1017): performScreenOffTransition : no brightness animation
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/lights  ( 1017): lcd : 0 -
,D/DisplayPowerController( 1017): getFinalBrightness : Summary is 0 -> 0
,D/DisplayPowerController( 1017): performScreenOffTransition : no brightness animation
,D/PowerManagerService( 1017): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1017): [PWL] sb release: PowerManagerService.Display
,D/accuweather( 1722): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
D/MISC PowerHAL( 1017): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1017): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1017): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1017): sysfs_write -: /sys/class/input/event3/device/enabled: 0,
D/MISC PowerHAL( 1017): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1017): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1017): Got set_interactive hint
,D/DisplayManagerService( 1017): !@display_state: ON -> OFF
D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb830d690
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
,I/DisplayManagerService( 1017): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager( 1017): Display changed displayId=0
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1722): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
I/BatteryStatsDumper( 1017): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1017): Screen bin #1: time=0 power=0.0
,I/BatteryStatsDumper( 1017): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1017): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1017): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1017): Previous Battery Level: 0 Current Level: 100 Delta: -100
D/accuweather( 1722): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1722): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1722): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/StatusBar.NetworkController( 1180): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  288): DCD OFF
,E/LibSecureUISvc( 1949): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/SSRM:n  ( 1017): SIOP:: AP = 330
,D/PowerManagerService( 1017): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1722): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1722): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1722): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1722): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1722): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1722): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1722): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/BatteryStatsDumper( 1017): Writing to database completed
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
,D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl( 1017): Excessive delay in setPowerMode(): 261ms
D/PowerManagerService( 1017): Excessive delay in !@display_state: OFF: 263ms
I/libsuspend( 1017): !@autosuspend_wakeup_count_enable
D/PowerManagerService( 1017): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 272ms
,I/libsuspend( 1017): !@autosuspend_wakeup_count_enable done
I/PowerManagerService( 1017): [PWL] Off : 0s ago
,D/SSRM:a  ( 1017): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1017): SettingsAirViewInfo:: 000000000
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/wpa_supplicant( 2077): nl80211: Received scan results (3 BSSes),
D/WifiP2pService( 1017): InactiveState{ what=147461 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147461 }
,D/WifiP2pService( 1017): DefaultState{ what=147461 }
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardViewMediator( 1180): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1180): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1180): *** Keyguard wallpaper service already unbounded
,I/PowerManagerService( 1017): [PWL] Off : 5s ago
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :4,
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 5600): [980] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5600): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :8
,D/SSRM:n  ( 1017): SIOP:: AP = 310
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 1017): waitForAlarm result :8,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 15s ago,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged,
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 300,
,V/AlarmManager( 1017): waitForAlarm result :8,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1017): !@Sync 3
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager( 1017): waitForAlarm result :4,
,E/SMD     (  288): DCD OFF
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: android, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,V/AlarmManager( 1017): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManagerEXT( 1017): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1017): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,I/BackgroundCompactionService( 1017): onStart. jobID=801
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,I/BackgroundCompactionService( 1017): onStart done. jobID=801
,I/BackgroundCompactionService( 1017): Execute BGCompaction (type1). (0 times)
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,I/BackgroundCompactionService( 1017): compact_memory command done
D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/PowerManagerService( 1017): [PWL] Off : 30s ago
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/art     ( 1822): Explicit concurrent mark sweep GC freed 41137(2MB) AllocSpace objects, 15(240KB) LOS objects, 39% free, 12MB/21MB, paused 1.153ms total 67.411ms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1822): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1822): Vacuum at: now=1455029413259 tag=VacuumService
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1822): Scheduling Phenotype for one-off execution 2794 seconds from now (1455029413744)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1822): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1822): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1822): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1017): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1822): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1822): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1822): (HTTPLog)-Static: isShipBuild true
I/System.out( 1822): (HTTPLog)-Thread-257-904518447: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1822): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1822): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1822): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1822, getuid(): 10012
,I/qtaguid ( 1822): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1822, getuid(): 10012
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/FactoryTest( 5368): Not factory mode
,D/FactoryTest( 5368): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5368): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5368): still no open session command from host, so toast
,W/ContextImpl( 5368): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5368): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5368): Timeline: Activity_launch_request id:com.android.settings time:115028
,E/PersonaManagerService( 1017): inState():  stateMachine is null !!
,I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1017): mDVFSHelper.acquire()
,V/ActivityManager( 1017): Display changed displayId=0
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus left window: 3103
,E/MTPRx   ( 5368): started activity for popup
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5368): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5368): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5368): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5368): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5368): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5368): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/LocationManagerService( 1017): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1822): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1822): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1822, getuid(): 10012
,E/SettingsReceiverActivity( 5368): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus entered window: 3103
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1017): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@326976e3 attribute=android.view.inputmethod.EditorInfo@2fb2f8e0, token = android.os.BinderProxy@34cedd84
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SamsungIME( 1788): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/SettingsReceiverActivity( 5368): dev.kiessupport is : TRUE
,D/PhoneWindow( 5368): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5368): *FMB* installDecor flags : 8388610
,D/LocationManagerService( 1017): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/DBG_DM  ( 3103): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 3103): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 31
,I/System.out( 1822): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1822): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1822, getuid(): 10012
,I/DBG_DM  ( 3103): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 3103): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3103): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 31
,I/DBG_DM  ( 3103): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3103): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3103): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3103): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 3103): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 31
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
,I/StatusBar( 1180): Icon Only
I/DBG_DM  ( 3103): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true,
,I/DBG_DM  ( 3103): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3103): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3103): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3103): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,I/DBG_DM  ( 3103): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/Timeline( 3103): Timeline: Activity_idle id: android.os.BinderProxy@287f06d3 time:115281
,V/ActivityThread( 3103): updateVisibility : ActivityRecord{15bd3c8c token=android.os.BinderProxy@287f06d3 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/ActivityManager( 1017): mDVFSHelper.release(),
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=7_task.xml,
,D/SSRM:n  ( 1017): SIOP:: AP = 290,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/PowerManagerService( 1017): [PWL] Off : 50s ago,
,D/SSRM:n  ( 1017): SIOP:: AP = 290,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10,
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 1017): !@Sync 4
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 280
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 75s ago
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,V/AlarmManager( 1017): waitForAlarm result :8,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1017): !@Sync 5
,I/ClearcutLoggerApiImpl( 1822): disconnect managed GoogleApiClient
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 105s ago,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1017): !@Sync 6
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2016): Aggregate from 1455027640761 (log), 1455027640761 (data)
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,V/AlarmManager( 1017): waitForAlarm result :8,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/Watchdog( 1017): !@Sync 7
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1017): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 8
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 180s ago,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 9
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 225s ago,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/TLC_TIMA_PKM_initialize( 1017): initializing...
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
I/TLC_TIMA_PKM_initialize( 1017): root = /firmware/image, root_strlen = 15
D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
I/TLC_TIMA_PKM_initialize( 1017): process = tima_pkm, process_strlen = 8
D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
I/TZ: qc_tlc_communication( 1017): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1017): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1017): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1017): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1017): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1017): Trustlet response is completed
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1017): !@Sync 10,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1017): !@Sync 11
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/PowerManagerService( 1017): [PWL] Off : 275s ago,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 12
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,V/AlarmManager( 1017): waitForAlarm result :8
,V/AlarmManager( 1017): No more alarm at this time.nowELAPSED=400572 batch.start=798113
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1017): !@Sync 13
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 330s ago,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1017): !@Sync 14
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager( 1017): waitForAlarm result :8
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1017): !@Sync 15
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 390s ago
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/bootchecker(  314): bootchecker wake up!!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 1017): !@Sync 16
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1017): !@Sync 17
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/PowerManagerService( 1017): [PWL] Off : 455s ago,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 1017): !@Sync 18
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/Atfwd_Daemon(  318): Stop the daemon....,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1017): !@Sync 19,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 525s ago,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1017): !@Sync 20,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1017): !@Sync 21,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1017): !@Sync 22,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 600s ago,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1017): !@Sync 23,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1017): !@Sync 24,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 680s ago,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1017): !@Sync 25,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,E/Watchdog( 1017): !@Sync 26
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1017): !@Sync 27
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 766s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1017): !@Sync 28
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1017): !@Sync 29
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,E/SMD     (  288): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1017): !@Sync 30
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 856s ago,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1017): !@Sync 31
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1017): !@Sync 32
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1017): !@Sync 33
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 951s ago
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1017): !@Sync 34
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1017): !@Sync 35
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1017): !@Sync 36
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :8,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1017): !@Sync 37
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 1051s ago,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1017): !@Sync 38
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1017): !@Sync 39
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate,
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1017): TimaServiceHandler.handleMessage what =1,
,I/UsageStatsService( 1017): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1017): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1017): Updating Usage Statistics in DB @ 1455030515511
,I/ApplicationPolicy( 1017): updateDataUsageMap
,I/NetworkDataUsageDb( 1017): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1017): ::isTableExists: Table exists 
,I/ApplicationUsage( 1017): Done Updating Usage Statistics in DB @ 1455030515827
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1017): !@Sync 40
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 1156s ago,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1017): !@Sync 41,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,TIME-OUT KILL (timeout was 1200000ms),D/SSRM:n  ( 1017): SIOP:: AP = 260
D/AndroidRuntime( 6594): 
D/AndroidRuntime( 6594): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6594): CheckJNI is OFF
D/AndroidRuntime( 6594): readGMSProperty: start
D/AndroidRuntime( 6594): readGMSProperty: already setted!!
D/AndroidRuntime( 6594): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6594): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6594): readGMSProperty: end
D/AndroidRuntime( 6594): addProductProperty: start
D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
E/AffinityControl( 6594): AffinityControl: registerfunction enter
D/AndroidRuntime( 6594): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1017): START PACKAGE DELETE: observer{678595781}
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): !@killApplicatoin: 10155, uninstall pkg
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
I/art     ( 4744): Explicit concurrent mark sweep GC freed 15317(823KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 771us total 29.782ms
I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
I/art     ( 5460): Explicit concurrent mark sweep GC freed 350(24KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 695us total 31.297ms
I/art     ( 4960): Explicit concurrent mark sweep GC freed 2304(130KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 742us total 35.977ms
E/SamsungIME( 1788): mOCRHelper is null
W/GeofencerStateMachine( 1822): Ignoring removeGeofence because network location is disabled.
I/art     ( 2016): Explicit concurrent mark sweep GC freed 5040(335KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 14MB/18MB, paused 1.374ms total 82.497ms
D/RegisteredComponentCache( 1440): Collect Tech packages for Knox
D/PersonaManager( 1440): isKioskContainerExistOnDevice
I/KLMS-2.5.183: ( 3549): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 16:09:24 GMT+01:00 2016
D/ActivityManager( 1017): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.183: ( 3549): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1017): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1017): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6607): MountEmulatedStorage()
I/libpersona( 6607): KNOX_SDCARD checking this for 10094
E/Zygote  ( 6607): v2
I/libpersona( 6607): KNOX_SDCARD not a persona
I/KLMS-2.5.183: ( 3549): KLMSIntentService(): onCreate()
I/SELinux ( 6607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6607): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6607 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3549): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
I/PackagesMonitor( 4997): PackagesMonitor onReceive :com.test.thalitest
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
D/PersonaManager( 1440): isKioskContainerExistOnDevice
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3549): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/RCPManagerService( 1017): PackageReceiver onReceive()
I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1017): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1017): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1017): DBIntegrity::getInstance - New instance created
E/Zygote  ( 6620): MountEmulatedStorage()
E/Zygote  ( 6620): v2
I/libpersona( 6620): KNOX_SDCARD checking this for 10149
I/libpersona( 6620): KNOX_SDCARD not a persona
I/SELinux ( 6620): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/KLMS-2.5.183: ( 3549): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/SELinux ( 6620): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6620 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/RegisteredServicesCache( 1440): empty dynamic service
I/KLMS-2.5.183: ( 3549): KLMSIntentService(): PACKAGE_REMOVED
E/SELinux ( 6620): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/OTPFW   ( 1017): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
I/OTPFW   ( 1017): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1017): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10155
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
I/KLMS-2.5.183: ( 3549): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.183: ( 3549): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/TimaKeyStoreProvider( 6607): TimaSignature is unavailable
V/AlarmManagerEXT( 1017): com.test.thalitest(10155) is removed.
D/ActivityThread( 6607): Added TimaKeyStore provider
D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
D/Mms/FreeMessageStatusReceiver( 5658): onReceive, action : android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10155
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
D/ActivityManager( 1017): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/TimaKeyStoreProvider( 6620): TimaSignature is unavailable
D/ActivityThread( 6620): Added TimaKeyStore provider
D/Mms/FreeMessageReceiverService( 5658): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 5658): onHandleIntent: ACTION_PACKAGE_REMOVED
I/TactileAssist( 1017): enable value -1
I/TactileAssist( 1017): internal enable value -1
I/TactileAssist( 1017): intensity value -1
I/TactileAssist( 1017): saveAppList value true
I/TactileAssist( 1017): List of disabled apps :
E/SQLiteLog( 4744): (284) automatic index on crash_info_summary(package_name_touched)
I/art     ( 4744): Explicit concurrent mark sweep GC freed 1017(49KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 801us total 39.333ms
D/Compatibility( 5901): onReceive() it will make start service
D/ActivityManager( 1017): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
I/KLMS-2.5.183: ( 3549): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.183: ( 3549): KLMSIntentService(): onDestroy()
D/BadgeProvider( 5861): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5861): sendNotify, [notify] : null
D/BadgeProvider( 5861): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5861): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5861): update, [UpdateCount] : 1
D/ActivityManager( 1017): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/Compatibility( 5901): onHandleIntent()
D/Compatibility( 5901): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10155, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/UpdateIcingCorporaServi( 5460): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 5901): found: 2
D/Compatibility( 5901): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5901): skipping ResolveInfo{263de987 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5901): considering ResolveInfo{aedc0b4 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5901): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/elm:15183( 6607): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/Compatibility( 5901): enabling receiver ResolveInfo{172a14dd com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/elm:15183( 6607): ELMEngine.ELMEngine( context ).
D/elm:15183( 6607): MDMBridge.setEnterpriseBridge()
D/ActivityManager( 1017): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15183( 6607): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5901): enabling receiver ResolveInfo{2f346852 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6642): MountEmulatedStorage()
I/libpersona( 6642): KNOX_SDCARD checking this for 10003
E/Zygote  ( 6642): v2
I/libpersona( 6642): KNOX_SDCARD not a persona
I/SELinux ( 6642): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6642 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
D/elm:15183( 6607): ElmAgentService : onCreate()
W/ContextImpl( 5117): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
I/SELinux ( 6642): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/elm:15183( 6607): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
E/SELinux ( 6642): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:15183( 6607): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6607): MDMBridge.getInstance()
D/elm:15183( 6607): MDMBridge.getAllLicenseInfoFromSDK()
D/Compatibility( 5901): enabling receiver ResolveInfo{12859723 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/elm:15183( 6607): MDMBridge.getAllLicenseInfoFromSDK()
E/SMD     (  288): DCD OFF
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5901): enabling receiver ResolveInfo{1f003420 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5901): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/TimaKeyStoreProvider( 6642): TimaSignature is unavailable
E/Zygote  ( 6658): MountEmulatedStorage()
E/Zygote  ( 6658): v2
I/libpersona( 6658): KNOX_SDCARD checking this for 1000
I/libpersona( 6658): KNOX_SDCARD not a persona
I/SELinux ( 6658): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityThread( 6642): Added TimaKeyStore provider
I/SELinux ( 6658): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6658): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6658 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/elm:15183( 6607): ElmAgentService : onDestroy().
D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ThemeInfoUtil( 6620): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 6620): isCurrentFestival = false
D/TimaKeyStoreProvider( 6658): TimaSignature is unavailable
D/ActivityThread( 6658): Added TimaKeyStore provider
D/RCPManager( 5544):  in createShortcut() for packageName: com.test.thalitest userId0
D/UserAnalysis.PlaceProvider( 6642): PlaceProvider onCreate()
D/RCPManagerService( 1017):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1017): queryAllProviders():  providerCallBack is not register for 0
D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
I/art     ( 1017): Explicit concurrent mark sweep GC freed 57607(6MB) AllocSpace objects, 235(3MB) LOS objects, 33% free, 28MB/42MB, paused 3.902ms total 421.088ms
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
D/AASAservice-UpdateReceiver( 6658): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/System.err( 6658): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
D/UserAnalysis.SecureDbManager( 6642): Key for secure DB is newly created
W/System.err( 6658): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6658): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6658): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6658): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6658): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6658): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6658): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6658): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6658): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6658): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6658): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6658): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/UserAnalysis.SecurePlaceDbHelper( 6642): SecurePlaceDbHelper() 
D/UserAnalysis( 6642): Create SecureDbHelper
I/TapandpayWidget:TapandpayAppWidgetProvider( 5701): onReceive()
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TapandpayWidget:TapandpayAppWidgetProvider( 5701): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
D/IntelligenceServiceApplication( 6642): onCreate()
I/TapandpayWidget:Utils( 5701): Clear T&P info.
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6642): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
D/TapandpayWidget:TapandpayAppWidgetProvider( 5701): Widget is not attached.
D/IntelligenceServiceApplication( 6642): no applications having user consent for prediction
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetection::stopService] Service stopped.
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/PCWCLIENTTRACE_PushUtil( 5714): SPPPushClient is installed : true
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
D/PackageManager( 1017): delete codoeFile: 
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10155, packageName = com.test.thalitest
I/AASA_removePackage( 1017): UID=10155 Target=com.test.thalitest
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/PackageManager( 1017): result of delete: 1{678595781}
I/PCWCLIENTTRACE_PushUtil( 5714): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5714): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5714): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/AndroidRuntime( 6594): Shutting down VM
E/Zygote  ( 6676): MountEmulatedStorage()
I/libpersona( 6676): KNOX_SDCARD checking this for 10160
E/Zygote  ( 6676): v2
I/libpersona( 6676): KNOX_SDCARD not a persona
I/SELinux ( 6676): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6676 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/SELinux ( 6676): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6676): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
D/TimaKeyStoreProvider( 6676): TimaSignature is unavailable
D/ActivityThread( 6676): Added TimaKeyStore provider
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/BluetoothAdapter( 6642): cancelDiscovery
E/Zygote  ( 6691): MountEmulatedStorage()
E/Zygote  ( 6691): v2
I/libpersona( 6691): KNOX_SDCARD checking this for 1000
I/libpersona( 6691): KNOX_SDCARD not a persona
I/SELinux ( 6691): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6691 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5481:com.google.android.partnersetup/u0a15 (adj 15): empty #31
I/SELinux ( 6691): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6691): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 5507): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
D/BluetoothAdapterProperties( 2621): mDiscovering is false
W/ResourcesManager( 5507): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/BluetoothAdapterService( 2621): This is not a scanning status. cancelDiscovery() will be not called.
D/BluetoothAdapter( 6642): cancelDiscovery = true
V/PlaceDetection v1.0.19 ( 6642): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
W/ResourcesManager( 6676): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
W/ResourcesManager( 5507): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 6691): TimaSignature is unavailable
W/ResourcesManager( 5507): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ActivityThread( 6691): Added TimaKeyStore provider
I/UpdateIcingCorporaServi( 5460): UpdateCorporaTask done [took 344 ms] updated apps [took 344 ms] 
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetection::stopService] Service stopped.
V/PlaceDetection v1.0.19 ( 6642): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6707): MountEmulatedStorage()
I/libpersona( 6707): KNOX_SDCARD checking this for 10035
E/Zygote  ( 6707): v2
I/libpersona( 6707): KNOX_SDCARD not a persona
I/SELinux ( 6707): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6707 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6707): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Killing 5684:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
E/SELinux ( 6707): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 5507): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/[0]UMC:UMCContentProvider( 6676): @onCreate
I/ActivityManager( 1017): Killing 5751:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
D/[0]UMC:Core( 6676): onCreate(): 
D/[0]UMC:Core( 6676): @isManagedProfileUser
D/[0]UMC:Core( 6676): userId: 0
D/[0]UMC:Core( 6676): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 6676): userInfo.isManagedProfile() : false
W/ResourcesManager( 5507): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ContextImpl( 6691): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
D/TimaKeyStoreProvider( 6707): TimaSignature is unavailable
D/ActivityManager( 1017): startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
D/ActivityThread( 6707): Added TimaKeyStore provider
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
W/ResourcesManager( 5507): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/[0]UMC:DeviceInfo( 6676): USA==US==
W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
E/Zygote  ( 6724): MountEmulatedStorage()
W/art     ( 6594): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/ActivityManager( 1017): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6724 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 6724): v2
I/libpersona( 6724): KNOX_SDCARD checking this for 1000
I/libpersona( 6724): KNOX_SDCARD not a persona
I/SELinux ( 6724): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6724): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ResourcesManager( 5507): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/SELinux ( 6724): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6724): TimaSignature is unavailable
D/ActivityThread( 6724): Added TimaKeyStore provider
I/ActivityManager( 1017): Killing 5767:com.policydm/1000 (adj 15): empty #31
E/SQLiteLog( 4744): (284) automatic index on crash_info_summary(package_name_touched)
W/ResourcesManager( 5507): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/BadgeProvider( 5861): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5861): sendNotify, [notify] : null
D/BadgeProvider( 5861): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5861): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5861): update, [UpdateCount] : 1
W/ResourcesManager( 5507): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/AcmsPackageEventListener( 6724): Received: android.intent.action.PACKAGE_REMOVED
W/ContextImpl( 6724): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 

```
