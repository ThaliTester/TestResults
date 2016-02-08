#### Test 581356550b07fff_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
W/ContextImpl( 4962): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/Mms/ComposeMessageFragment( 4712): [end]    fillCache consume time = 100.146771
I/DocumentService( 4912): DocumentService onDestroy start
I/DocumentService( 4912): DocumentService onDestroy end
--------- beginning of system
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
I/DocumentService( 4912): DocumentService cleanupEverything start
I/IndexParserThreadsManager( 4912): InterruptedException: null
I/SystemInfo( 4912): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 4912): DocumentService cleanupEverything end
I/Process ( 4912): Sending signal. PID: 4912 SIG: 9
E/lowmemorykiller(  253): Error writing /proc/4912/oom_score_adj; errno=22
I/ActivityManager( 1014): Killing 3860:com.google.android.talk/u0a104 (adj 15): empty #31
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4962): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4962): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4962): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/FaceInterface( 4962): requestFaceScan() is called.
I/ActivityManager( 1014): Process com.samsung.indexservice (pid 4912)(adj 15) has died(106,1155)
I/FaceInterface( 4962): startFaceScan() : waiting 5 sec
W/LocalSuggestAlbumData( 4962): query fail: 
W/LocalSuggestAlbumData( 4962): query fail: 
W/libprocessgroup( 1014): failed to open /acct/uid_10104/pid_3860/cgroup.procs: No such file or directory
D/Mms/BubbleViewCache( 4712): fillCache bubble = 1
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
D/SettingsProvider( 1014): name = icc_lock_enable
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
I/SettingSearch/SearchIntentReceiver( 1343): action : com.samsung.settings.CHANGED_ICC_LOCK_ENABLE
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.sec.smartcard.manager
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.smartcard.manager, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4994): MountEmulatedStorage()
I/libpersona( 4994): KNOX_SDCARD checking this for 10153
E/Zygote  ( 4994): v2
I/libpersona( 4994): KNOX_SDCARD not a persona
I/SELinux ( 4994): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.smartcard.manager for broadcast com.sec.smartcard.manager/com.sec.smartcard.pinservice.SmartCardBroadcastReceiver: pid=4994 uid=10153 gids={50153, 9997, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 4994): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4994): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 4994): TimaSignature is unavailable
D/ActivityThread( 4994): Added TimaKeyStore provider
W/ResourcesManager( 4994): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
E/SmartCardContentProvider( 4994): onCreate
I/SmartCardBroadcastReceiver( 4994): SmartCardBroadcastReceiver - onReceive() 
I/SmartCardBroadcastReceiver( 4994): Broadcast received for locktype changed 
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
I/ActivityManager( 1014): Killing 4543:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
E/CscFactoryReceiver( 1452): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1452): Media DB Scanner finished.
D/CscFactoryReceiver( 1452): start service to Set Ringtone
D/ActivityManager( 1014): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/CscFactoryReceiver( 1452): start service to Set Notification
D/ActivityManager( 1014): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/CscFactoryReceiver( 1452): start service to Set Alarmtone
D/ActivityManager( 1014): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/CscUpdateService( 1452): onStart
E/CscUpdateService( 1452): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1452): only ringtone update
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/CscUpdateService( 1452): onStart
E/CscUpdateService( 1452): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1452): only notification update
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
D/CscUpdateService( 1452): onStart
E/CscUpdateService( 1452): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1452): only alarmtone update
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.indexservice, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/CscParser( 1452): update(): xml file exist
E/CscParser( 1452): update(): xml file exist
E/Zygote  ( 5013): MountEmulatedStorage()
E/Zygote  ( 5013): v2
I/libpersona( 5013): KNOX_SDCARD checking this for 10006
I/libpersona( 5013): KNOX_SDCARD not a persona
E/CscParser( 1452): update(): xml file exist
I/SELinux ( 5013): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5013 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5013): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/CSCSettings( 1452): Setting Ringtones (type) : 1
E/SELinux ( 5013): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/CscParser( 1452): RingTone: null
W/CSCSettings( 1452): 1. Tag_Str: null
W/CSCSettings( 1452): Setting Ringtones (type) : 2
D/CscParser( 1452): MessageTone: null
W/CSCSettings( 1452): 1. Tag_Str: null
W/CSCSettings( 1452): Setting Ringtones (type) : 4
D/CscParser( 1452): AlarmTone: null
W/CSCSettings( 1452): 1. Tag_Str: null
D/TimaKeyStoreProvider( 5013): TimaSignature is unavailable
D/ActivityThread( 5013): Added TimaKeyStore provider
I/ThumbnailProvider( 5013): ThumbnailProvider onCreate()
I/DocumentBroadcastReceiver( 5013): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
I/BroadcastProcessorService( 5013): [START] processBroadcastIntent ...
D/ActivityManager( 1014): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
I/BroadcastProcessorService( 5013): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
D/GalleryCacheReady( 4962): Receive action.ACTION_MEDIA_SCANNER_FINISHED
D/GalleryCacheReady( 4962): handleMeidaScanFinish()
I/SystemInfo( 5013): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 5013): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
I/BroadcastProcessorService( 5013): [START] DocumentService startDocumentService
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
D/FaceInterface( 4962): requestFaceScan() is called.
W/LocalSuggestAlbumData( 4962): query fail: 
D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
W/LocalSuggestAlbumData( 4962): query fail: 
W/ActivityManager( 1014): userId = 0, bbcId = -10000
I/FaceInterface( 4962): startFaceScan() : waiting 5 sec
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1014): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
I/DocumentService( 5013): DocumentService onCreate ... service
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.app.popupuireceiver
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 4928): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/Zygote  ( 5034): MountEmulatedStorage()
I/libpersona( 5034): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5034): v2
I/libpersona( 5034): KNOX_SDCARD not a persona
I/SELinux ( 5034): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5034 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5034): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5034): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5013): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
W/ResourcesManager( 4928): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/art     (  304): Explicit concurrent mark sweep GC freed 8707(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 667us total 21.305ms
W/ResourcesManager( 4928): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4928): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5013): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
W/libprocessgroup( 1014): failed to open /acct/uid_10113/pid_4543/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5034): TimaSignature is unavailable
D/ActivityThread( 5034): Added TimaKeyStore provider
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 17.753ms
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 16.966ms
D/PopupuiReceiver( 5034): onReceive() getAction : com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED
D/SecContentProvider2( 1014): uri = -1 selection = getSealedState
D/SecContentProvider2( 1014): mCursor = null
I/PopupuiReceiver_KNOX( 5034): getSealedState : true
D/SecContentProvider2( 1014): uri = 15 selection = getSealedHideNotificationMessages
D/SecContentProvider2( 1014): mCursor = null
I/PopupuiReceiver_KNOX( 5034): getSealedHideNotificationMessages : 1
D/SecContentProvider2( 1014): uri = 15 selection = getCheckCoverPopupState
D/SecContentProvider2( 1014): mCursor = null
I/PopupuiReceiver_KNOX( 5034): getCheckCoverPopupState : true
D/PopupuiReceiver( 5034): Action cable connected ! on - 
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.powersharing, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.samsung.android.app.powersharing
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5049): MountEmulatedStorage()
E/Zygote  ( 5049): v2
I/libpersona( 5049): KNOX_SDCARD checking this for 10122
I/libpersona( 5049): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.samsung.android.app.powersharing for broadcast com.samsung.android.app.powersharing/.service.BatteryReceiver: pid=5049 uid=10122 gids={50122, 9997} abi=armeabi-v7a
I/SELinux ( 5049): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5049): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SystemInfo( 5013): [SIOP LEVEL] : 0
E/SELinux ( 5049): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5049): TimaSignature is unavailable
D/ActivityThread( 5049): Added TimaKeyStore provider
I/DocumentService( 5013): [BEGIN SYNC] DocumentService beginIndexing :16
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5013): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
E/File    ( 5013): fail readDirectory() errno=13
E/File    ( 5013): fail readDirectory() errno=13
I/SystemInfo( 5013): [SYSTEM STATUS] Battery and Storage levels are OK:
I/PowerSharing.BatteryReceiver( 5049): onReceive : com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED
I/DocumentService( 5013): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 5013): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :44
E/DocumentService( 5013): [THUMBNAIL] Total Time taken for each file :0
E/        ( 5013): [INDEX] Total time taken for each file :0
I/DocumentService( 5013): DocumentService onDestroy start
I/DocumentService( 5013): DocumentService onDestroy end
I/DocumentService( 5013): DocumentService cleanupEverything start
I/ActivityManager( 1014): Killing 4525:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.wluc, hostingType: broadcast
I/IndexParserThreadsManager( 5013): InterruptedException: null
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1014): Start proc com.sec.android.app.wluc for broadcast com.sec.android.app.wluc/.PolicyManagerBroadcastReceiver: pid=5068 uid=10165 gids={50165, 9997} abi=armeabi-v7a
E/Zygote  ( 5068): MountEmulatedStorage()
E/Zygote  ( 5068): v2
I/libpersona( 5068): KNOX_SDCARD checking this for 10165
I/libpersona( 5068): KNOX_SDCARD not a persona
I/SELinux ( 5068): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Killing 4619:com.sec.android.cloudagent/u0a2 (adj 15): empty #31
I/SystemInfo( 5013): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5013): DocumentService cleanupEverything end
I/Process ( 5013): Sending signal. PID: 5013 SIG: 9
I/SELinux ( 5068): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5068): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5068): TimaSignature is unavailable
D/ActivityThread( 5068): Added TimaKeyStore provider
I/ActivityManager( 1014): Process com.samsung.indexservice (pid 5013)(adj 11) has died(109,1156)
I/PolicyManagerBroadcastReceiver( 5068): onReceive: action = com.sec.intent.ACTION.SSRM_HGL_UPDATE
I/PolicyManagerBroadcastReceiver( 5068): onReceive: width = 720, height = 1280
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/MediaStoreImporter( 4464): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
W/libprocessgroup( 1014): failed to open /acct/uid_10010/pid_4525/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10002/pid_4619/cgroup.procs: No such file or directory
I/ActivityManager( 1014): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuSettingSearch: pid=5083 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 5083): MountEmulatedStorage()
I/libpersona( 5083): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5083): v2
I/libpersona( 5083): KNOX_SDCARD not a persona
I/SELinux ( 5083): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5083): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Killing 4653:com.sec.android.diagmonagent/1000 (adj 15): empty #31
E/SELinux ( 5083): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5083): TimaSignature is unavailable
D/ActivityThread( 5083): Added TimaKeyStore provider
D/AssistantMenuSettingSearch( 5083): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
D/AssistantMenuSettingSearch( 5083): Make Setting DB
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.sec.providers.settingsearch
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5098): MountEmulatedStorage()
E/Zygote  ( 5098): v2
I/libpersona( 5098): KNOX_SDCARD checking this for 10150
I/libpersona( 5098): KNOX_SDCARD not a persona
I/SELinux ( 5098): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=5098 uid=10150 gids={50150, 9997} abi=armeabi-v7a
I/ActivityManager( 1014): Waited long enough for: ServiceRecord{afb3544 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
I/SELinux ( 5098): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5098): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5098): TimaSignature is unavailable
D/ActivityThread( 5098): Added TimaKeyStore provider
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4653/cgroup.procs: No such file or directory
W/ContextImpl( 5083): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:158 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:38 
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.phone
I/ActivityManager( 1014): Killing 4634:com.google.android.apps.plus/u0a120 (adj 15): empty #31
I/ActivityManager( 1014): Killing 3147:com.policydm/1000 (adj 15): empty #32
I/SettingSearchManagerReceiver( 1452): onReceive : com.samsung.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
I/SettingSearchManagerReceiver( 1452): addSearchInfoDB
I/SettingSearchManagerReceiver( 1452): endInsert
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5116): MountEmulatedStorage()
E/Zygote  ( 5116): v2
I/libpersona( 5116): KNOX_SDCARD checking this for 10101
I/libpersona( 5116): KNOX_SDCARD not a persona
W/libprocessgroup( 1014): failed to open /acct/uid_10120/pid_4634/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3147/cgroup.procs: No such file or directory
I/SELinux ( 5116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5116 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5116): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/SSRM:n  ( 1014): SIOP:: AP = 400
D/TimaKeyStoreProvider( 5116): TimaSignature is unavailable
D/ActivityThread( 5116): Added TimaKeyStore provider
D/AndroidRuntime( 5113): 
D/AndroidRuntime( 5113): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5113): CheckJNI is OFF
D/AndroidRuntime( 5113): readGMSProperty: start
D/AndroidRuntime( 5113): readGMSProperty: already setted!!
D/AndroidRuntime( 5113): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5113): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5113): readGMSProperty: end
D/AndroidRuntime( 5113): addProductProperty: start
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/AffinityControl( 5113): AffinityControl: registerfunction enter
I/Gmail   ( 5116): getAccountsCursor
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/AndroidRuntime( 5113): Calling main entry com.android.commands.am.Am
V/GLSActivity( 1786): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/PersonaManagerService( 1014): inState():  stateMachine is null !!
I/PersonaManagerService( 1014): PersonaId don't exist
I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
D/AndroidRuntime( 5113): Shutting down VM
W/GAV2    ( 5116): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 5116): Observing account changes for notifications
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 5116): Error finding the version of the Email provider.....
E/Gmail   ( 5116): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5116): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 5116): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 5116): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 5116): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5116): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5116): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 5116): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5116): We do not support migrating this version of the Email provider.
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/Gmail   ( 5116): getAccountsCursor
E/Zygote  ( 5159): MountEmulatedStorage()
E/Zygote  ( 5159): v2
I/libpersona( 5159): KNOX_SDCARD checking this for 10033
I/libpersona( 5159): KNOX_SDCARD not a persona
I/SELinux ( 5159): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=5159 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/SELinux ( 5159): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5159): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
V/GLSActivity( 1786): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1014): Killing 4230:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
D/TimaKeyStoreProvider( 5159): TimaSignature is unavailable
D/ActivityThread( 5159): Added TimaKeyStore provider
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1786): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/libprocessgroup( 1014): failed to open /acct/uid_10125/pid_4230/cgroup.procs: No such file or directory
E/SQLiteLog( 5116): (283) recovered 80 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
W/ResourcesManager( 5159): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5159): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5159): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/art     ( 5113): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ResourcesManager( 5159): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5159): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5159): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5159): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5159): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 5159): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/File    ( 5116): fail readDirectory() errno=2
,I/Gmail   ( 5116): notifyAccountChanged
,I/Gmail   ( 5116): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5116): getAccountsCursor
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1786): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5116): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5116): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,I/Gmail   ( 5116): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 5116): getAccountsCursor
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1786): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SPPClientService( 3969): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=5194 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 4473:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,E/Zygote  ( 5194): MountEmulatedStorage()
E/Zygote  ( 5194): v2
I/libpersona( 5194): KNOX_SDCARD checking this for 10035
I/libpersona( 5194): KNOX_SDCARD not a persona
I/SELinux ( 5194): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5194): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5194): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5194): TimaSignature is unavailable
,D/ActivityThread( 5194): Added TimaKeyStore provider
,E/SPPClientService( 5194): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5194): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 5194): PushLog.txt file is not deleted.
D/SPPClientService( 5194): PushLog.txt file is not deleted.
D/SPPClientService( 5194): ============PushLog. stop!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1014): failed to open /acct/uid_10009/pid_4473/cgroup.procs: No such file or directory
,E/Zygote  ( 5214): MountEmulatedStorage(),
,E/Zygote  ( 5214): v2
I/libpersona( 5214): KNOX_SDCARD checking this for 10035
I/SELinux ( 5214): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5214): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=5214 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1014): Killing 4269:com.android.calendar/u0a135 (adj 15): empty #31
,I/SELinux ( 5214): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5214): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5214): TimaSignature is unavailable
,D/ActivityThread( 5214): Added TimaKeyStore provider
,E/SPPClientService( 5214): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5214): [PushClientApplication] Push log off : This is Ship build version
,E/LNoti   ( 5214): [PhoneStatusChangeReceiver] This device doesn't register yet.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1014): Killing 4385:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,D/SPPClientService( 5214): PushLog.txt file is not deleted.
D/SPPClientService( 5214): PushLog.txt file is not deleted.
D/SPPClientService( 5214): ============PushLog. stop!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.download.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
,W/GCoreFlp( 1786): No location to return for getLastLocation()
,W/FusedLocationProvider( 1786): location=null
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_10135/pid_4269/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4385/cgroup.procs: No such file or directory
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1786): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SafeBrowsingUpdateIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  286): DCD OFF
,I/art     ( 1642): Explicit concurrent mark sweep GC freed 3446(140KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 754us total 25.800ms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=5239 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 5239): MountEmulatedStorage()
E/Zygote  ( 5239): v2
I/libpersona( 5239): KNOX_SDCARD checking this for 1000
I/libpersona( 5239): KNOX_SDCARD not a persona
I/SELinux ( 5239): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5239): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5239): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5239): TimaSignature is unavailable
,D/ActivityThread( 5239): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 5239): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 194305(6MB) AllocSpace objects, 4(64KB) LOS objects, 25% free, 46MB/62MB, paused 2.831ms total 278.054ms
,I/DIAGMON_AGENT( 5239): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 5239): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 5239): [com.diagmondm.XDMBroadcastReceiver(33/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager( 1014): Killing 4034:com.android.providers.calendar/u0a42 (adj 15): empty #31
,I/DBG_DM  ( 3083): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5254): MountEmulatedStorage(),
I/libpersona( 5254): KNOX_SDCARD checking this for 10104
E/Zygote  ( 5254): v2
I/libpersona( 5254): KNOX_SDCARD not a persona
I/SELinux ( 5254): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5254): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5254): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5254 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5254): TimaSignature is unavailable
,D/ActivityThread( 5254): Added TimaKeyStore provider
,W/ResourcesManager( 5254): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/libprocessgroup( 1014): failed to open /acct/uid_10042/pid_4034/cgroup.procs: No such file or directory
,I/Babel   ( 5254): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5254): MmsConfig.loadMmsSettings
,I/Babel   ( 5254): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel   ( 5254): MmsConfig.loadFromDatabase
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 5254): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Babel   ( 5254): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5254): MmsConfig.loadFromResources
,E/Babel   ( 5254): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5254): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel_StickerModule( 5254): App launched.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  281): getCameraInfo: X
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  281): getCameraInfo: X
,I/ActivityManager( 1014): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5279 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/Zygote  ( 5279): MountEmulatedStorage()
,E/Zygote  ( 5279): v2
I/libpersona( 5279): KNOX_SDCARD checking this for 10135
I/libpersona( 5279): KNOX_SDCARD not a persona
,I/SELinux ( 5279): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5279): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5279): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 5279): TimaSignature is unavailable,
D/ActivityThread( 5279): Added TimaKeyStore provider
,W/VideoCapabilities( 5254): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5254): Unsupported mime audio/evrc
,I/art     (  304): Explicit concurrent mark sweep GC freed 8698(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 715us total 36.648ms
,W/AudioCapabilities( 5254): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5254): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5254): Unsupported mime audio/mpeg-L2
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 979us total 20.043ms
,W/AudioCapabilities( 5254): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5254): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5254): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5254): Unsupported mime audio/evrc
,W/ResourcesManager( 5279): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5279): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5279): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 809us total 16.810ms
,W/VideoCapabilities( 5254): Unsupported mime video/wvc1
,W/VideoCapabilities( 5254): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5254): Unrecognized profile/level 32768/2 for video/mp4v-es
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/VideoCapabilities( 5254): Unsupported mime video/wvc1
,W/VideoCapabilities( 5254): Unsupported mime video/x-ms-wmv
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/VideoCapabilities( 5254): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5254): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5254): Unsupported mime video/mp43
,W/VideoCapabilities( 5254): Unsupported mime video/sorenson
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/VideoCapabilities( 5254): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5254): Unsupported profile 4 for video/mp4v-es
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5300): MountEmulatedStorage()
I/libpersona( 5300): KNOX_SDCARD checking this for 10142
E/Zygote  ( 5300): v2
I/libpersona( 5300): KNOX_SDCARD not a persona
I/SELinux ( 5300): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5300 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5300): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5300): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ActivityManager( 1014): Killing 4678:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5300): TimaSignature is unavailable
,D/ActivityThread( 5300): Added TimaKeyStore provider
,I/art     ( 1014): Background sticky concurrent mark sweep GC freed 64863(2MB) AllocSpace objects, 17(7MB) LOS objects, 13% free, 53MB/62MB, paused 4.347ms total 115.917ms
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/ActivityManager( 1014): Killing 3989:com.osp.app.signin/u0a41 (adj 15): empty #31
,V/TaskCloserActivity( 5300): TaskCloserActivity enter()
,V/TaskCloserActivity( 5300): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,W/ContextImpl( 4738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.sm.base.a.a:307 com.samsung.android.sm.contextagent.ContextAgentReceiver.onReceive:124 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5254): Creating RTCS
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1014): failed to open /acct/uid_10062/pid_4678/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10041/pid_3989/cgroup.procs: No such file or directory
,E/Zygote  ( 5319): MountEmulatedStorage()
,E/Zygote  ( 5319): v2,
I/libpersona( 5319): KNOX_SDCARD checking this for 10042
I/libpersona( 5319): KNOX_SDCARD not a persona
,I/SELinux ( 5319): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5319 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5319): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5319): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/Babel   ( 5254): Destroying RTCS
,I/ActivityManager( 1014): Killing 4696:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5319): TimaSignature is unavailable
,D/ActivityThread( 5319): Added TimaKeyStore provider
,W/ResourcesManager( 5319): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5319): CalendarProvider2.onCreate() called
,W/libprocessgroup( 1014): failed to open /acct/uid_10157/pid_4696/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 5319): (284) automatic index on view_events(_id)
,I/ActivityManager( 1014): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5337 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 5337): MountEmulatedStorage()
I/libpersona( 5337): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5337): v2
I/libpersona( 5337): KNOX_SDCARD not a persona
,I/SELinux ( 5337): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
I/SELinux ( 5337): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5337): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5337): TimaSignature is unavailable
,D/ActivityThread( 5337): Added TimaKeyStore provider
,D/CalendarAlarmManager( 5319): sys current time:1454950330770
,D/CalendarAlarmManager( 5319): reminder amount:0
,E/MTPRx   ( 5337): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1014): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1014): mCursor = null
,V/MTPRx   ( 5337): sealedState: false
,V/MTPRx   ( 5337): sealedUsbMassStorageState: false
,E/MTPRx   ( 5337): check value of boot_completed is1
E/MTPRx   ( 5337): check booting is completed_sys.boot_completed
,E/MTPRx   ( 5337): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 5337): Status for mount/Unmount :removed
E/MTPRx   ( 5337): SDcard is not available
,W/MTPRx   ( 5337): value of connected istrue
W/MTPRx   ( 5337): value of configured istrue
W/MTPRx   ( 5337): value of mtpEnabled istrue
W/MTPRx   ( 5337): value of ptpEnabled isfalse
,E/MTPRx   ( 5337): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 5337): mFirstTime: false
,D/        ( 5337): MTP: reading debug level property
,E/MTPJNIInterface( 5337): Getting CryptionKey from JAVA
,E/MTPRx   ( 5337): currentUserId is 0
,E/MTPRx   ( 5337): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 5337): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 5337): is_Privatemode is NOT 1
,D/SettingsProvider( 1014): name = mtp_usb_conditions_met
,D/SecContentProvider( 1014): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 5337): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1014): name = mtp_running_status
,D/SettingsProvider( 1014): name = mtp_usb_conditions_met
,E/MTPRx   ( 5337): else part ... so first time!!!
,E/MTPPlaObsrvr( 5337): inside setContext()
E/MTPPlaObsrvr( 5337):  inside createplafiles
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 5337): playlist count is0
E/MTPPlaObsrvr( 5337):  inside try branch createplafiles
,E/MTPPlaObsrvr( 5337):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 5337): Inside registerContentObserver
,E/MtpAdbObserver( 5337): inside setContext()
,E/MtpAdbObserver( 5337): Inside registerContentObserver
W/Settings( 5337): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1014): name = mtp_running_status
,D/SettingsProvider( 1014): name = mtp_usb_conditions_met
,E/MtpService( 5337): onCreate.
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,V/MtpMediaDBManager( 5337): inside deleteAllDB
,D/MtpService( 1228): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpService( 5337): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 5337): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,D/MediaScannerReceiver( 1228): action: com.samsung.intent.action.MTP_FILE_SCAN
E/MtpService( 5337): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,V/MtpMediaDBManager( 5337): inside Thread updateDB
,E/MtpService( 5337): onStartCommand.
W/MTPRx   ( 5337): calling native method
E/MTPJNIInterface( 5337): < MTP > Registering BroadCast receiver :::::
,E/MTPJNIInterface( 5337): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 5337): noti = 10
E/MtpService( 5337): onStartCommand.
,W/MTPRx   ( 5337): calling native method
E/MTPRx   ( 5337): Checking the driver time out
E/MTPJNIInterface( 5337): noti = 2
D/        ( 5337): deleting sockets before message queue initialization
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/        ( 5337): event handler thread is created, so set the flag
,E/MTPRx   ( 5337): called native method
E/MTPJNIInterface( 5337): setting Media scanner status0
E/MTPJNIInterface( 5337): After setting Media scanner status0
,E/MtpService( 5337): handleMessage. msg= { when=-4ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.android.settings
,I/SettingSearch/SearchIntentReceiver( 1343): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1343): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,W/MTPRx   ( 5337): notification from stack 1
,E/MtpMediaDBManager( 5337): count : 27
,E/        ( 5337): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
,E/MTPJNIInterface( 5337): Getting media scanner status0
,E/MTPJNIInterface( 5337): DeviceName is A5-1
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
,E/MtpService( 5337): handleMessage. msg= { when=-23ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,I/SettingSearch/SearchIntentReceiver( 1343): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 1343): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 1343): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/PolicyManagerBroadcastReceiver( 5068): This process will be killed soon.
I/Process ( 5068): Sending signal. PID: 5068 SIG: 9
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/MtpMediaDBManager( 5337): sending db update complete noti to stack
E/MTPJNIInterface( 5337): noti = 29
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
E/MTPJNIInterface( 5337): Status for mount/Unmount :removed
E/MTPJNIInterface( 5337): SDcard is not available
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/        ( 5337): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,E/        ( 5337): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/MTPJNIInterface( 5337): Status for mount/Unmount :removed
E/MTPJNIInterface( 5337): SDcard is not available
E/SQLiteLog( 5337): (21) API call with NULL database connection pointer
E/SQLiteLog( 5337): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 5337): (21) API call with NULL database connection pointer
E/SQLiteLog( 5337): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5337): (21) API call with NULL database connection pointer
E/SQLiteLog( 5337): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5337): (21) API call with NULL database connection pointer
E/SQLiteLog( 5337): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 5337): notification from stack 2
,D/        ( 5337): [mtp_init_device] Library open with 32 bits.
D/        ( 5337): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 5337): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 5337): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 5337):  [sua_support_present:1287] returning false 
D/        ( 5337): *****Starting mtp_io()
,W/MTPRx   ( 5337): notification from stack 3
,D/        ( 5337): [mtp_start_io] source_thread Creation 
I/ActivityManager( 1014): Process com.sec.android.app.wluc (pid 5068)(adj 15) has died(83,1165)
,D/        ( 5337): [mtp_start_io] sink_thread Creation 
D/        ( 5337): [mtp_start_io:376] sink thread created so set th_sink
,D/MediaScannerService( 1228): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SettingSearch/SettingsSearchManager( 1343): Infomation -> numtitleinfo : 0 numSearchinfo : 306
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter finished
,D/WearableService( 1786): callingUid 10012, callindPid: 1786
,I/art     ( 1014): Background partial concurrent mark sweep GC freed 378572(21MB) AllocSpace objects, 3(3MB) LOS objects, 27% free, 42MB/58MB, paused 5.451ms total 289.879ms
,D/MediaScanner( 1228): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
I/SettingSearch/SettingsSearchManager( 1343):  Infomation -> getItem size : 306
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,V/MediaScanner( 1228): processDirectory :  /storage/emulated/0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/MediaScanner( 1228): Skipping:
D/MediaScanner( 1228): 7klwibgf7fvntblfd7(75ebcf7
,D/MediaScanner( 1228): Skipping:
D/MediaScanner( 1228): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,V/MediaScanner( 1228): processDirectory :  /storage/extSdCard
W/MediaScanner( 1228): Error opening directory, reason : Permission denied.
W/MediaScanner( 1228): 7klwibgf7fxlKdCbid7
,V/MediaScanner( 1228):  prescan time: 45ms (DB items: 27)
V/MediaScanner( 1228):     scan time: 30ms (Caching mode: true), (makeEntry time: 25ms ~83%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1228): postscan time: 3ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1228):    total time: 78ms
V/MediaScanner( 1228): checked files: 10  directories : 17  (I: 0, U: 0)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/MediaScannerService( 1228): !@done scanning volume external
,E/MTPJNIInterface( 5337): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,I/iu.UploadsManager( 1981): End new media; added: 0, uploading: 0, time: 84 ms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ResourcesManager( 1343): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 1343): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1343): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1343): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/MusicLeanback( 4464): Conditions not met for autocaching.
I/MusicLeanback( 4464): Stop autocaching.
,E/GmsUtils( 4464): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 4464): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/PackageManager( 1014): verifying app can be installed or not
D/ApplicationPolicy( 1014): isApplicationInstallationEnabled
,D/ApplicationPolicy( 1014): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1014): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1014): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1014): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy( 1014): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1014): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1014): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1014): isApplicationInstallationEnabled :  Checking SIG BL - true
,D/ApplicationPolicy( 1014): isApplicationInstallationEnabled :  enabled true
,I/AASAInstall( 1014): ship mode
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
,E/CscFactoryReceiver( 1452): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1452): Media DB Scanner finished.
D/CscFactoryReceiver( 1452): start service to Set Ringtone
,D/ActivityManager( 1014): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1452): start service to Set Notification
,D/ActivityManager( 1014): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1452): start service to Set Alarmtone
,D/ActivityManager( 1014): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscUpdateService( 1452): onStart
E/CscUpdateService( 1452): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1452): only ringtone update
,D/CscUpdateService( 1452): onStart
E/CscUpdateService( 1452): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1452): only notification update
D/CscUpdateService( 1452): onStart
E/CscUpdateService( 1452): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1452): only alarmtone update
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.indexservice, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/CscParser( 1452): update(): xml file exist
,E/CscParser( 1452): update(): xml file exist
,E/Zygote  ( 5378): MountEmulatedStorage(),
I/libpersona( 5378): KNOX_SDCARD checking this for 10006
E/Zygote  ( 5378): v2
I/libpersona( 5378): KNOX_SDCARD not a persona
W/CSCSettings( 1452): Setting Ringtones (type) : 2
D/CscParser( 1452): MessageTone: null
W/CSCSettings( 1452): 1. Tag_Str: null,
I/SELinux ( 5378): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/CscParser( 1452): update(): xml file exist
,I/ActivityManager( 1014): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5378 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5378): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Waited long enough for: ServiceRecord{1afb8f4 u0 com.sec.bcservice/.BroadcastService}
E/SELinux ( 5378): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/CSCSettings( 1452): Setting Ringtones (type) : 4
D/CscParser( 1452): AlarmTone: null
W/CSCSettings( 1452): 1. Tag_Str: null
,W/CSCSettings( 1452): Setting Ringtones (type) : 1
D/CscParser( 1452): RingTone: null
W/CSCSettings( 1452): 1. Tag_Str: null
,D/TimaKeyStoreProvider( 5378): TimaSignature is unavailable
,D/ActivityThread( 5378): Added TimaKeyStore provider
,I/ThumbnailProvider( 5378): ThumbnailProvider onCreate()
,I/DocumentBroadcastReceiver( 5378): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 5378): [START] processBroadcastIntent ...
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 4962): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady( 4962): handleMeidaScanFinish()
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/FaceInterface( 4962): requestFaceScan() is called.
,W/LocalSuggestAlbumData( 4962): query fail: 
,W/LocalSuggestAlbumData( 4962): query fail: 
,I/FaceInterface( 4962): startFaceScan() : waiting 5 sec
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/BroadcastProcessorService( 5378): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SystemInfo( 5378): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 5378): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
,I/BroadcastProcessorService( 5378): [START] DocumentService startDocumentService
D/ActivityManager( 1014): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,I/DocumentService( 5378): DocumentService onCreate ... service
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5378): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5378): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,D/BluetoothMediaBrowser( 2620):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,E/SystemInfo( 5378): [SIOP LEVEL] : 0
,D/BluetoothMediaBrowser( 2620): no now playing list
D/BluetoothMediaBrowser( 2620):  getNowPlayingId now playing id : -1
,I/DocumentService( 5378): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5378): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/SettingSearch/SearchIntentReceiver( 1343): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 1343): LOCALE_CHANGED call search setting db finish!!
,I/art     ( 1228): Explicit concurrent mark sweep GC freed 7047(483KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 675us total 38.297ms
,I/MediaStoreImporter( 4464): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,E/File    ( 5378): fail readDirectory() errno=13
E/File    ( 5378): fail readDirectory() errno=13
,I/SystemInfo( 5378): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5378): [STOP DOCUMENTSERVICE] Attempting to stop the Service
,E/DocumentService( 5378): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :81
E/DocumentService( 5378): [THUMBNAIL] Total Time taken for each file :0
E/        ( 5378): [INDEX] Total time taken for each file :0
,I/DocumentService( 5378): DocumentService onDestroy start
,I/DocumentService( 5378): DocumentService onDestroy end
,I/DocumentService( 5378): DocumentService cleanupEverything start
,I/IndexParserThreadsManager( 5378): InterruptedException: null
,I/SystemInfo( 5378): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5378): DocumentService cleanupEverything end
I/Process ( 5378): Sending signal. PID: 5378 SIG: 9
,I/SettingSearch/SearchIntentReceiver( 1343): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 1343): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1343): LOCALE_CHANGED call search setting db finish!!,
,I/CalendarProvider2( 5319): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,E/lowmemorykiller(  253): Error writing /proc/5378/oom_score_adj; errno=22
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/ActivityManager( 1014): Process com.samsung.indexservice (pid 5378)(adj 11) has died(73,1166)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/PackageManager( 1014): Existing package
,D/PackageManager( 1014): Renaming /data/app/vmdl1496596263.tmp to /data/app/com.test.thalitest-1
,D/PackageManager( 1014): installNewPackageLI: Package{9a65ff2 com.test.thalitest}
,I/PackageManager( 1014): scanFileNewer : com.test.thalitest
,I/art     ( 1014): Background partial concurrent mark sweep GC freed 273146(15MB) AllocSpace objects, 3(5MB) LOS objects, 27% free, 41MB/57MB, paused 5.615ms total 225.557ms
,I/art     ( 1014): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
I/art     ( 1014): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.test.thalitest-1/arm/base.odex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
D/PackageManager( 1014): Running dexopt on: /data/app/com.test.thalitest-1/base.apk pkg=com.test.thalitest isa=arm vmSafeMode=false interpret_only=false
,I/dex2oat ( 5406): ----------------------------------------------------
I/dex2oat ( 5406): <SS>: S T A R T I N G . . .
I/dex2oat ( 5406): <SS>: going to process manifest for 32-bit...
,I/        ( 5406): SS_ART_lib [I]: Memory allocation: ctx
,I/        ( 5406): SS_ART_lib [I]: Memory allocation: manifest_buf
,I/        ( 5406): SS_ART_lib [I]: Parsing Manifest for SS stuff
I/        ( 5406): SS_ART_lib [I]: Memory allocation: ctx->libs
,I/        ( 5406): SS_ART_lib [I]: Memory allocation: ctx->package_name
I/        ( 5406): SS_ART_lib [I]: Parsing completed
,I/        ( 5406): SS_ART_lib [I]: permission is absent: /data/app/com.test.thalitest-1/base.apk
I/        ( 5406): SS_ART_lib [I]: Closing zip file: /data/app/com.test.thalitest-1/base.apk
I/        ( 5406): SS_ART_lib [I]: access to SS denied
,I/        ( 5406): SS_ART_lib [I]: ctx will be cleaned
I/        ( 5406): SS_ART_lib [I]: ctx component will be cleaned: ctx->libs
I/        ( 5406): SS_ART_lib [I]: ctx component is cleaned: ctx->libs
I/        ( 5406): SS_ART_lib [I]: ctx component will be cleaned: ctx->package_name
,I/        ( 5406): SS_ART_lib [I]: ctx component is cleaned: ctx->package_name
,I/        ( 5406): SS_ART_lib [I]: ctx is cleaned
,I/dex2oat ( 5406): /system/bin/dex2oat --zip-fd=11 --zip-location=/data/app/com.test.thalitest-1/base.apk --oat-fd=12 --art-fd=-1 --oat-location=/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/FaceInterface( 4962): startFaceScan() : going on
D/FaceInterface( 4962): startFaceScan() is called.
,D/ContentApp( 1228): startScan() is called.
,D/FaceValue( 1228): mSleepTime: 800
D/FaceValue( 1228): mMaxThreadNum: 2
,W/FaceValue( 1228): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,D/ContentApp( 1228): startScan() is end.
,D/ContentApp( 1228): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1228): isNeedToRestore : start
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/dex2oat ( 5406): dex2oat took 408.663ms (threads: 4)
,I/PackageManager( 1014): do mInstaller.dexopt : 0
,D/PackageManager( 1014): Time to dexopt: 0.483 seconds
,W/System.err( 1014): java.io.FileNotFoundException: /data/app/com.test.thalitest-1: open failed: EISDIR (Is a directory)
,W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err( 1014): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 1014): 	at android.content.pm.PackageParser.getHashValueOfPackage(PackageParser.java:5140)
W/System.err( 1014): 	at com.android.server.pm.PackageManagerService.saveHash(PackageManagerService.java:19520)
W/System.err( 1014): 	at com.android.server.pm.PackageManagerService.access$5400(PackageManagerService.java:342)
W/System.err( 1014): 	at com.android.server.pm.PackageManagerService$19.run(PackageManagerService.java:19505)
,W/System.err( 1014): Caused by: android.system.ErrnoException: open failed: EISDIR (Is a directory)
,W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:446)
W/System.err( 1014): 	... 5 more
,I/FaceInterface( 4962): startFaceScan() : going on
,D/FaceInterface( 4962): startFaceScan() is called.
,D/PackageManager( 1014): New package installed
I/HarmonyEASService( 1014): Updating for all 1
,D/ContentApp( 1228): startScan() is called.,
D/ContentApp( 1228): startScan() is end.
,D/ContentApp( 1228): face_restore FINISHED_TYPE: 3,
,D/FaceScanner( 1228): isNeedToRestore : start
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PackageManager( 1014): doPostInstall for uid{10155}
,D/PackageManager( 1014): token 1 to BM for possible restore
,V/BackupManagerService( 1014): restoreAtInstall pkg=com.test.thalitest token=1 restoreSet=0
V/BackupManagerService( 1014): Finishing install immediately
,D/PackageManager( 1014): BM finishing package install for 1
,D/PackageManager( 1014): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 1014): [MSG] MCS_UNBIND
,I/InputReader( 1014): Reconfiguring input devices.  changes=0x00000010
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PageBuddyNotiSvc( 4194): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1452): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Zygote  ( 5415): MountEmulatedStorage()
E/Zygote  ( 5415): v2
I/libpersona( 5415): KNOX_SDCARD checking this for 1000
I/libpersona( 5415): KNOX_SDCARD not a persona
,I/SELinux ( 5415): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=5415 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 5415): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5415): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PackageManager( 1014): [MSG] POST_INSTALL: observer{18434657}
D/PackageManager( 1014):           Handling post-install for 1
,D/RegisteredComponentCache( 1440): Collect Tech packages for Knox
,I/ActivityManager( 1014): Killing 4722:com.qualcomm.timeservice/1000 (adj 15): empty #31
,W/Settings( 1014): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,D/TimaKeyStoreProvider( 5415): TimaSignature is unavailable
,D/ActivityThread( 5415): Added TimaKeyStore provider
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/InputReader( 1014): Reconfiguring input devices.  changes=0x00000010
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SamsungIME( 1766): mOCRHelper is null
,D/PersonaManager( 1440): isKioskContainerExistOnDevice
,D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1014): mCursor = null
,D/PersonaManager( 1440): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1440): empty dynamic service
,D/RegisteredComponentCache( 1440): Collect Tech packages for Knox
,D/PersonaManager( 1440): isKioskContainerExistOnDevice
,D/AASAservice-UpdateReceiver( 5415): AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.google.android.gms, uid = -1
,I/splitIntent( 1014): intent=android.intent.action.PACKAGE_CHANGED will be not split. because same process=com.google.android.googlequicksearchbox:search is in other queue. index=1
,I/splitIntent( 1014): base  index=1, name=com.google.android.googlequicksearchbox com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher
,I/splitIntent( 1014): other index=7, name=com.google.android.googlequicksearchbox com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_CHANGED !! do not split it!!
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5433): MountEmulatedStorage()
E/Zygote  ( 5433): v2
I/libpersona( 5433): KNOX_SDCARD checking this for 10057
I/libpersona( 5433): KNOX_SDCARD not a persona
,I/SELinux ( 5433): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher: pid=5433 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a,
I/ActivityManager( 1014): Killing 4760:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,I/SELinux ( 5433): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5433): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1014): mCursor = null
,D/TimaKeyStoreProvider( 5433): TimaSignature is unavailable
,D/ActivityThread( 5433): Added TimaKeyStore provider
,D/PersonaManager( 1440): isKioskContainerExistOnDevice
,W/ResourceType( 1014): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/RegisteredServicesCache( 1440): empty dynamic service
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 35644(2MB) AllocSpace objects, 9(144KB) LOS objects, 27% free, 41MB/57MB, paused 2.863ms total 237.578ms
D/PackageManager( 1014): result of install: 1{18434657}
,I/PackageManager( 1014): Observer no longer exists.
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1014): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1014): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1014): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/IntentResolver( 1014): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,D/BackupManagerService( 1014): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService( 1014): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService( 1014): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.backup.TRANSPORT_HOST
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService( 1014): PackageReceiver onReceive()
D/RCPManagerService( 1014): App Installed with packageNAme = com.test.thalitest
,E/RCPManagerService( 1014):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: Attempt to invoke virtual method 'java.lang.String android.os.Bundle.getString(java.lang.String)' on a null object reference
D/RCPManagerService( 1014):  PackageReceiver onReceive() bundle null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/KnoxMUMContainerPolicy( 1014): mPackageReceiver : action - android.intent.action.PACKAGE_ADDED
,D/BackupManagerService( 1014): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/BackupManagerService( 1014): Removing schedule queue dupe of com.test.thalitest
,V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_ADDED
V/EnterpriseBillingPolicy( 1014): uID is 10155
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
,D/PersonaPolicyManagerService( 1014): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
,V/BackupManagerService( 1014): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 1014): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@b6c180b
,I/GCoreNlp( 1786): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/AlarmManagerEXT( 1014): com.test.thalitest(10155) is added to mUserAppList
,D/KnoxMUMContainerPolicy( 1014): packageInstalledForExternalStorage com.test.thalitest
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/EnterpriseDeviceManagerService( 1014): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1014): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1014): no available spell checker services found
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourceType( 1014): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/libpersona( 5452): KNOX_SDCARD checking this for 10015
E/Zygote  ( 5452): MountEmulatedStorage()
I/libpersona( 5452): KNOX_SDCARD not a persona
E/Zygote  ( 5452): v2
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SELinux ( 5452): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 5452): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5452 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 5452): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/CrashAnrDetector( 1014): onPackageAdded : com.test.thalitest
,D/LocationManagerService( 1014): getProviders()=[passive]
,D/TimaKeyStoreProvider( 5452): TimaSignature is unavailable
,D/ActivityThread( 5452): Added TimaKeyStore provider
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4722/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10085/pid_4760/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1014): applying state to connected service
,D/LocationProviderProxy( 1014): applying state to connected service
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/LocationProviderProxy( 1014): applying state to connected service
,I/GCoreNlp( 1786): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5254): Creating RTCS
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
E/Zygote  ( 5476): MountEmulatedStorage()
E/Zygote  ( 5476): v2
I/libpersona( 5476): KNOX_SDCARD checking this for 10032
I/libpersona( 5476): KNOX_SDCARD not a persona
,I/SELinux ( 5476): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5476): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5476): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5476 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
,I/ActivityManager( 1014): Killing 4786:com.wsomacp/u0a25 (adj 15): empty #31
,I/Babel   ( 5254): Destroying RTCS
,I/ActivityManager( 1014): Killing 4801:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaKeyStoreProvider( 5476): TimaSignature is unavailable
,D/ActivityThread( 5476): Added TimaKeyStore provider
,I/FeatureConfig( 5476): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/ActivityManager( 1014): Killing 4856:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/PackagesMonitor( 4962): PackagesMonitor onReceive :com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_10025/pid_4786/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10094/pid_4801/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 5476): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5476): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,I/GAV2    ( 5116): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ResourcesManager( 5476): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,I/UpdateIcingCorporaServi( 5433): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5476): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 5496): MountEmulatedStorage()
,E/Zygote  ( 5496): v2
I/libpersona( 5496): KNOX_SDCARD checking this for 10069
I/libpersona( 5496): KNOX_SDCARD not a persona
,I/SELinux ( 5496): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5496): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
W/ResourcesManager( 5476): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/SELinux ( 5496): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5496 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup( 1014): failed to open /acct/uid_10003/pid_4856/cgroup.procs: No such file or directory
,W/ResourcesManager( 5476): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 5476): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 5476): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5496): TimaSignature is unavailable
,D/ActivityThread( 5496): Added TimaKeyStore provider
,W/ResourcesManager( 5476): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5476): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5476): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5476): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/FileShare-Server( 5496): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5476): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 5511): MountEmulatedStorage(),
I/libpersona( 5511): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5511): v2
I/libpersona( 5511): KNOX_SDCARD not a persona
I/SELinux ( 5511): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5511): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5511 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 5511): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
W/ResourcesManager( 5476): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 5476): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5476): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 5476): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5476): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5476): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5511): TimaSignature is unavailable
,D/ActivityThread( 5511): Added TimaKeyStore provider
,I/UpdateIcingCorporaServi( 5433): UpdateCorporaTask done [took 126 ms] updated apps [took 126 ms] 
,W/ResourcesManager( 5476): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5511): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 5476): system/finder_cp/cpdata.xml file not found
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5527): MountEmulatedStorage(),
E/Zygote  ( 5527): v2
I/libpersona( 5527): KNOX_SDCARD checking this for 1000
I/libpersona( 5527): KNOX_SDCARD not a persona
,I/SELinux ( 5527): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5527): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5527): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1014): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=5527 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/ActivityManager( 1014): Killing 4875:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,I/art     (  304): Explicit concurrent mark sweep GC freed 8756(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 21.484ms
,D/TimaKeyStoreProvider( 5527): TimaSignature is unavailable
,D/ActivityThread( 5527): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 17.490ms,
,D/KnoxSetupWizardDbHelper( 5527): dbMigrationFlag : false
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 606us total 16.668ms
,D/ShortcutReceiver( 5527):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED,
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5545): MountEmulatedStorage(),
,E/Zygote  ( 5545): v2
I/libpersona( 5545): KNOX_SDCARD checking this for 10120
I/libpersona( 5545): KNOX_SDCARD not a persona,
,I/SELinux ( 5545): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5545 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 4712:com.android.mms/u0a46 (adj 15): empty #31
,I/SELinux ( 5545): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5545): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5545): TimaSignature is unavailable
,D/ActivityThread( 5545): Added TimaKeyStore provider
,I/ActivityManager( 1014): Killing 4994:com.sec.smartcard.manager/u0a153 (adj 15): empty #31
,W/ResourcesManager( 5545): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CountryDetector( 1014): No listener is left
,W/libprocessgroup( 1014): failed to open /acct/uid_10107/pid_4875/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10153/pid_4994/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10046/pid_4712/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5568): MountEmulatedStorage(),
E/Zygote  ( 5568): v2
I/libpersona( 5568): KNOX_SDCARD checking this for 10028
I/SELinux ( 5568): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/libpersona( 5568): KNOX_SDCARD not a persona
,I/SELinux ( 5568): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5568): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5568 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 5034:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5568): TimaSignature is unavailable
,D/ActivityThread( 5568): Added TimaKeyStore provider
,D/Finsky  ( 5568): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5034/cgroup.procs: No such file or directory
,D/Finsky  ( 5568): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5568): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5568): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/Ads     ( 5568): Skipping gmscore version check
,D/Finsky  ( 5568): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5568): [1] Libraries$2.run: Finished loading 1 libraries.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1014): Killing 5049:com.samsung.android.app.powersharing/u0a122 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5568): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/PackageBroadcastService( 1981): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PackageBroadcastService( 1981): Null package name or gms related package.  Ignoreing.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/HomeSyncInstallReceiver( 1440): This pkg do not need BT addr. Do nothing
,D/Finsky  ( 5568): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1014): Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=14, mSplitNum[1]=23, mSplitNum[2]=36, mBgSplitQueueNum=3 divideNum= 11 r.nextReceiver= 2 receivers.size=47
,I/splitIntent( 1014): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,D/AASAservice-UpdateReceiver( 5415): AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
,I/AASAservice-TokenRule( 5415): parseToken()
,W/System.err( 5415): java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
,W/System.err( 5415): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 5415): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 5415): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/System.err( 5415): 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:80)
W/System.err( 5415): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:52)
W/System.err( 5415): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 5415): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 5415): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 5415): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5415): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5415): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 5415): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5415): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5415): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5415): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 5415): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 5415): 	at libcore.io.Posix.open(Native Method)
W/System.err( 5415): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 5415): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 5415): 	... 14 more
E/AASAservice-TokenRule( 5415): parseToken() : TokenFile is null
,E/AASAservice-UpdateReceiver( 5415): AASARuleUpdateResult() : Rule file is not exist.
,I/PackagesMonitor( 4962): PackagesMonitor onReceive :com.test.thalitest
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5611): MountEmulatedStorage()
,I/libpersona( 5611): KNOX_SDCARD checking this for 10152
E/Zygote  ( 5611): v2
I/libpersona( 5611): KNOX_SDCARD not a persona
I/SELinux ( 5611): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5611 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 5611): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5611): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5620): MountEmulatedStorage()
E/Zygote  ( 5620): v2
I/libpersona( 5620): KNOX_SDCARD checking this for 10046
I/libpersona( 5620): KNOX_SDCARD not a persona
I/SELinux ( 5620): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=5620 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
I/SELinux ( 5620): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5620): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5611): TimaSignature is unavailable
,D/ActivityThread( 5611): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 5620): TimaSignature is unavailable
,D/ActivityThread( 5620): Added TimaKeyStore provider
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ContextImpl( 5083): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_10122/pid_5049/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 5611): (284) automatic index on shooting_modes(title_id)
,E/Zygote  ( 5649): MountEmulatedStorage()
,E/Zygote  ( 5649): v2
I/libpersona( 5649): KNOX_SDCARD checking this for 1000
I/libpersona( 5649): KNOX_SDCARD not a persona
,I/SELinux ( 5649): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5649 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 5649): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,E/SELinux ( 5649): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/Icing   ( 1981): Storage manager: low false usage 1.73MB avail 10.16GB capacity 11.68GB
,D/TimaKeyStoreProvider( 5649): TimaSignature is unavailable
D/ActivityThread( 5649): Added TimaKeyStore provider
,E/Zygote  ( 5667): MountEmulatedStorage()
E/Zygote  ( 5667): v2
I/libpersona( 5667): KNOX_SDCARD checking this for 1000
I/libpersona( 5667): KNOX_SDCARD not a persona
,I/SELinux ( 5667): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5667): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5667): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5667 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/ResourcesManager( 5620): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5620): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5620): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5620): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5620): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5620): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5667): TimaSignature is unavailable
,D/ActivityThread( 5667): Added TimaKeyStore provider
,E/Zygote  ( 5682): MountEmulatedStorage()
,I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5682 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,E/Zygote  ( 5682): v2,
I/libpersona( 5682): KNOX_SDCARD checking this for 10156
I/libpersona( 5682): KNOX_SDCARD not a persona
,I/SELinux ( 5682): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5682): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5682): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/PCWCLIENTTRACE_LOG( 5649): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5649): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5649): new DMDBOpenHelper instance
,W/ResourcesManager( 5667): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,D/Mms/MmsApp( 5620): [start]    onCreate() consume time = 0.0
,D/TimaKeyStoreProvider( 5682): TimaSignature is unavailable
,D/ActivityThread( 5682): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_PushUtil( 5649): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5649): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5649): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5649): [onReceive] - android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/TapandpayWidget:TapandpayAppWidgetProvider( 5682): onReceive()
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5682): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,E/Zygote  ( 5700): MountEmulatedStorage()
E/Zygote  ( 5700): v2
I/libpersona( 5700): KNOX_SDCARD checking this for 1000
I/libpersona( 5700): KNOX_SDCARD not a persona
I/SELinux ( 5700): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5700): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5700): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=5700 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/TapandpayWidget:Utils( 5682): Clear T&P info.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5682): Widget is not attached.
,E/Zygote  ( 5715): MountEmulatedStorage()
E/Zygote  ( 5715): v2
I/libpersona( 5715): KNOX_SDCARD checking this for 10091
,I/libpersona( 5715): KNOX_SDCARD not a persona
,I/SELinux ( 5715): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/TimaKeyStoreProvider( 5700): TimaSignature is unavailable
,D/ActivityThread( 5700): Added TimaKeyStore provider
,I/SELinux ( 5715): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5715): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5715 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 5159:com.sec.android.app.sns3/u0a33 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 3969:com.sec.spp.push/u0a35 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5715): TimaSignature is unavailable
,D/ActivityThread( 5715): Added TimaKeyStore provider
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5732): MountEmulatedStorage()
I/libpersona( 5732): KNOX_SDCARD checking this for 10010
E/Zygote  ( 5732): v2
I/libpersona( 5732): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5732 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 5732): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5732): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/Finsky  ( 5568): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,E/SELinux ( 5732): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Killing 5194:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31
,W/art     ( 5620): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 144.136ms
,D/TimaKeyStoreProvider( 5732): TimaSignature is unavailable
,D/ActivityThread( 5732): Added TimaKeyStore provider
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/libprocessgroup( 1014): failed to open /acct/uid_10033/pid_5159/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10035/pid_3969/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10035/pid_5194/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5700): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 5700): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,D/Mms/TelephonyPermission( 5620): start operation mode monitor
,D/Mms/ArtClassLoader( 5620): init before art
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,I/DBG_POLICYDM( 5700): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 5620): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5700): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,D/ChimeraCfgMgr( 1981): Loading module com.google.android.gms.games from APK com.google.android.play.games
,I/DBG_POLICYDM( 5700): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/ChimeraModuleLdr( 1981): Loading module APK com.google.android.play.games
,I/DBG_POLICYDM( 5700): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,D/PackageBroadcastService( 1981): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/ActivityManager( 1014): Waited long enough for: ServiceRecord{ab9235e u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/TelephonyPermission( 5620): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 5620): isDefault true
,D/Mms/MmsApp( 5620): onCreate() com.android.mms
,I/DBG_POLICYDM( 5700): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 5700): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,I/DBG_POLICYDM( 5700): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 5700): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,D/Mms/MmsApp( 5620): [start]    initCountryIso consume time = 371.2
,I/DBG_POLICYDM( 5700): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,E/PhotosPlugin( 5715): Loading PhotosPlugin
,I/DBG_POLICYDM( 5700): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 5700): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5700): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 5700): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 5700): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,I/DBG_POLICYDM( 5700): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,I/DBG_POLICYDM( 5700): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/DBG_POLICYDM( 5700): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 5700): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/DBG_POLICYDM( 5700): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 5700): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 5700): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5700): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/02/09/09:35:09
I/art     ( 1014): Explicit concurrent mark sweep GC freed 202211(13MB) AllocSpace objects, 4(3MB) LOS objects, 33% free, 27MB/40MB, paused 2.791ms total 192.263ms
,I/DBG_POLICYDM( 5700): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5700): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,I/DBG_POLICYDM( 5700): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/CountryDetector( 1014): The first listener is added
,I/DBG_POLICYDM( 5700): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 5700): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 5700): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5700): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 5700): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,I/DBG_POLICYDM( 5700): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/02/08/17:52:15
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,D/Mms/MmsApp( 5620): [end]    initCountryIso consume time = 206.438229
D/Mms/MmsConfig( 5620): [start]    MmsConfig.init() consume time = 0.129896
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5700): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 5700): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 5700): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,D/Mms/MmsConfig( 5620): before partial update
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5700): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 5700): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,E/Zygote  ( 5765): MountEmulatedStorage()
E/Zygote  ( 5765): v2
I/libpersona( 5765): KNOX_SDCARD checking this for 10035
I/libpersona( 5765): KNOX_SDCARD not a persona
,I/SELinux ( 5765): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5765): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5765): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5765 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Mms/MmsConfig( 5620): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 5620): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 5620): isAuth is false
,D/Mms/MmsConfig( 5620): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,I/art     (  304): Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 778us total 23.797ms
,D/TP/MmsSmsProvider( 1452): query,matched:2117, calling pid = 5620
,D/TP/MmsSmsProvider( 1452): match 2117:Elapsed time : 1.328 ms
,D/TimaKeyStoreProvider( 5765): TimaSignature is unavailable
,D/ActivityThread( 5765): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5700): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 747us total 20.525ms
,D/EasySignUpManager_1.0.1( 5620): isAuth is false
D/EasySignUpManager_1.0.1( 5620): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 5620): mps_code.dat does not exist
E/CscParser( 5620): customer_path =/system/csc/customer.xml
E/CscParser( 5620): fileName + /system/csc/customer.xml
,E/SMD     (  286): DCD OFF
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 748us total 18.705ms
,E/CscParser( 5620): mps_code.dat does not exist
E/CscParser( 5620): customer_path =/system/csc/customer.xml
E/CscParser( 5620): fileName + /system/csc/customer.xml
,I/DBG_POLICYDM( 5700): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,D/CscParser( 5620): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 5620):  enable multiwindow = true
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Mms/MessageUtils( 5620): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5620): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 5620): [end]    init() consume time = 138.351927
,D/Mms/Contact( 5620): [start]    init() consume time = 0.920573
,D/TP/MmsSmsProvider( 1452): query,matched:13, calling pid = 5620
,I/DBG_POLICYDM( 5700): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,D/TP/MmsSmsProvider( 1452): match 13:Elapsed time : 2.002 ms
,I/DBG_POLICYDM( 5700): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/Mms/Contact( 5620): [end]    init consume time = 31.110469
,D/Mms/DraftCache( 5620): [start]    rebuildCache consume time = 22.78651
,D/ChimeraCfgMgr( 1981): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1981): Module APK com.google.android.play.games already loaded
,D/Mms/MethodReflector( 5620): getSubId is called
D/Mms/TelephonyUtils( 5620): getLongSubId from simSlot 0, return Value = -1
,D/TP/MmsSmsProvider( 1452): query,matched:12, calling pid = 5620
,D/TP/MmsSmsProvider( 1452): match 12:Elapsed time : 2.196 ms
,D/Mms/DraftCache( 5620): [end]    rebuildCache consume time = 12.702761
,E/SPPClientService( 5765): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5765): [PushClientApplication] Push log off : This is Ship build version
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,D/ChimeraCfgMgr( 1981): Loading module com.google.android.gms.gass from APK com.google.android.gms
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/Mms/MethodReflector( 5620): getTelephonyProperty is called
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/Mms/DownloadManager( 5620): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5620): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5620): auto download without roaming -> true
D/Mms/DownloadManager( 5620): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5620): getSubId is called
,D/Mms/MethodReflector( 5620): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5620): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5620): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5620): getTelephonyProperty is called
D/Mms/DownloadManager( 5620): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5620): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5620): auto download without roaming -> true
D/Mms/DownloadManager( 5620): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5620): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5620): mAutoDownload ------> true
,D/SPPClientService( 5765): PushLog.txt file is not deleted.
,D/SPPClientService( 5765): PushLog.txt file is not deleted.
D/SPPClientService( 5765): ============PushLog. stop!
,D/AsyncTaskServiceImpl( 1981): Submit a task: k,
,E/Zygote  ( 5792): MountEmulatedStorage(),
E/Zygote  ( 5792): v2
I/libpersona( 5792): KNOX_SDCARD checking this for 10038,
I/libpersona( 5792): KNOX_SDCARD not a persona
,I/SELinux ( 5792): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5792 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 5214:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 5792): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5792): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Killing 5239:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/ChimeraCfgMgr( 1981): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/Mms/ArtClassLoader( 5620): init [DONE] art
,D/TimaKeyStoreProvider( 5792): TimaSignature is unavailable
,D/ActivityThread( 5792): Added TimaKeyStore provider
,D/ChimeraCfgMgr( 1981): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1981): Processing package: com.test.thalitest
,W/ResourcesManager( 5792): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5792): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ComposerPerformance( 5620): 1454950335672 ms / [DONE] Composer constructor
,E/CII     ( 5620): CommonIMSInterface: VoLTE CSC feature disabled.
,D/Mms/Conversation( 5620): [start]    init() consume time = 99.112916
,I/Mms/ReservationManager( 5620): ReservationManager()
I/Mms/ReservationManager( 5620): resetAfterConnected()
,D/TP/MmsSmsProvider( 1452): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1452): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1452): updateThread(), thread_id = 9223372036854775807
,D/TP/MmsSmsProvider( 1452): query,matched:7, calling pid = 5620
,V/TP/MmsSmsDatabaseHelper( 1452): sUpgradeVersion = 0, db.getVersion() = 81
,D/TP/MmsSmsProvider( 1452): match 7:Elapsed time : 3.875 ms
,D/TP/MmsSmsProvider( 1452): delete threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1452): need read changed broadcast:false
,D/Mms/Conversation( 5620): [end]    init consume time = 12.589271
,I/Mms/ReservationManager( 5620): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/MmsApp( 5620): [end]    onCreate() consume time = 4.224375
,D/Mms/MessagingNotification( 5620): [start]    init() consume time = 1.350677
,D/Mms/MessagingNotification( 5620): [end]    init consume time = 3.508386
,D/Mms/SpamFilter( 5620): [start]    SpamFilter fill() begin consume time = 2.988125
,W/libprocessgroup( 1014): failed to open /acct/uid_10035/pid_5214/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5239/cgroup.procs: No such file or directory
,D/TP/MmsSmsProvider( 1452): query,matched:400, calling pid = 5620
,D/TP/MmsSmsProvider( 1452): query,matched:0, calling pid = 5620
V/TP/MmsSmsProvider( 1452): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1452): match 0:Elapsed time : 1.017 ms
,D/Mms/Synchronizer( 5620): [start]    doSync consume time = 6.625
,D/Mms/SpamFilter( 5620): [end]    SpamFilter fill() finished consume time = 3.13375
,D/TP/MmsSmsProvider( 1452): update, matched:300, calling pid = 5620
V/TP/MmsSmsProvider( 1452): syncDBData start
,V/TP/MmsSmsProvider( 1452): syncDBData sms end
,V/TP/MmsSmsProvider( 1452): syncDBData mms end
V/TP/MmsSmsProvider( 1452): syncDBData end
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5812): MountEmulatedStorage()
E/Zygote  ( 5812): v2
I/libpersona( 5812): KNOX_SDCARD checking this for 10072
I/libpersona( 5812): KNOX_SDCARD not a persona
,I/SELinux ( 5812): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5812): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5812): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5812 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/GassUtils( 1981): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,D/k       ( 1981): Found info for package com.test.thalitest in db.
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/Synchronizer( 5620): [end]    doSync consume time = 31.321406
,D/Mms/DownloadManager( 5620): Service state changed: Bundle[mParcelledData.dataSize=744],
D/Mms/DownloadManager( 5620): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 5620): getSubId is called
D/Mms/TelephonyUtils( 5620): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 5620): getTelephonyProperty is called
D/Mms/DownloadManager( 5620): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5620): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5620): auto download without roaming -> true
D/Mms/DownloadManager( 5620): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5620): mAutoDownload ------> true
,D/TimaKeyStoreProvider( 5812): TimaSignature is unavailable
,D/ActivityThread( 5812): Added TimaKeyStore provider
,D/Mms/FreeMessageStatusReceiver( 5620): onReceive, action : android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1014): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 5812): onCreate
,D/BadgeProvider( 5812): DatabaseHelper
,D/Mms/FreeMessageReceiverService( 5620): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5620): onHandleIntent: ACTION_PACKAGE_ADDED
,E/Zygote  ( 5830): MountEmulatedStorage()
E/Zygote  ( 5830): v2
I/libpersona( 5830): KNOX_SDCARD checking this for 10047
I/libpersona( 5830): KNOX_SDCARD not a persona
,I/SELinux ( 5830): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1014): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5830 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a,
I/SELinux ( 5830): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5830): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Killing 5319:com.android.providers.calendar/u0a42 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 5300:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #32
,I/Icing   ( 1981): updateResources: need to parse f{com.google.android.gms}
,D/TimaKeyStoreProvider( 5830): TimaSignature is unavailable
,D/ActivityThread( 5830): Added TimaKeyStore provider
,D/Mms/MessagingNotification( 5620): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1452): query,matched:26, calling pid = 5620
,D/TP/SmsProvider( 1452): match 26:Elapsed time : 1.155 ms
,W/ResourcesManager( 5830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5830): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5830): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TP/MmsSmsProvider( 1452): query,matched:6, calling pid = 5620
,W/BaseAppContext( 1981): Using Auth Proxy for data requests.
W/BaseAppContext( 1981): Using Auth Proxy for data requests.
D/TP/MmsSmsProvider( 1452): match 6:Elapsed time : 1.194 ms
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5846): MountEmulatedStorage(),
E/Zygote  ( 5846): v2
I/libpersona( 5846): KNOX_SDCARD checking this for 10025
I/libpersona( 5846): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5846 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,I/SELinux ( 5846): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5846): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5846): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5846): TimaSignature is unavailable
D/ActivityThread( 5846): Added TimaKeyStore provider
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ResourcesManager( 5846): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/libprocessgroup( 1014): failed to open /acct/uid_10042/pid_5319/cgroup.procs: No such file or directory
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_10142/pid_5300/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BaseAppContext( 1981): Using Auth Proxy for data requests.
,I/ActivityManager( 1014): Killing 5098:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,I/OMACP   ( 5846): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,W/BaseAppContext( 1981): Using Auth Proxy for data requests.
,D/Mms/Omacp( 5620): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,W/BaseAppContext( 1981): Using Auth Proxy for data requests.
W/BaseAppContext( 1981): Using Auth Proxy for data requests.
,I/OMACP   ( 5846): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 5846): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 5846): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 5846): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 5846): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 5846): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 5846): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 5846): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,D/MyFiles ( 5830): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,I/OMACP   ( 5846): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 5846): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,W/BaseAppContext( 1981): Using Auth Proxy for data requests.
,I/OMACP   ( 5846): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
I/OMACP   ( 5846): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,I/OMACP   ( 5846): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,I/DBG_POLICYDM( 5700): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/TactileAssist( 1014): enable value -1
,I/TactileAssist( 1014): internal enable value -1
I/TactileAssist( 1014): intensity value -1
,I/TactileAssist( 1014): saveAppList value true
,E/installd(  282): system dir 0 : /system/app/
E/installd(  282): system dir 1 : /system/priv-app/
E/installd(  282): system dir 2 : /vendor/app/
E/installd(  282): system dir 3 : /oem/app/
,I/TactileAssist( 1014): List of disabled apps :
,I/DBG_POLICYDM( 5700): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1014): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,W/libprocessgroup( 1014): failed to open /acct/uid_10150/pid_5098/cgroup.procs: No such file or directory
,E/Zygote  ( 5869): MountEmulatedStorage()
I/libpersona( 5869): KNOX_SDCARD checking this for 10053
E/Zygote  ( 5869): v2
I/libpersona( 5869): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5869 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 5869): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5869): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5869): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5869): TimaSignature is unavailable
,D/ActivityThread( 5869): Added TimaKeyStore provider
,I/PeopleDatabaseHelper( 1981): cleanUpNonGplusAccounts done.
,W/ResourcesManager( 5869): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/Compatibility( 5869): onReceive() it will make start service
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,D/Compatibility( 5869): onHandleIntent()
,D/Compatibility( 5869): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
,D/Compatibility( 5869): found: 2
D/ActivityManager( 1014): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/UpdateIcingCorporaServi( 5433): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/SL_DEBUG( 5792): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 5792): isLoggable:: SL_DEBUG_EXIST = false
,D/Compatibility( 5869): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5869): skipping ResolveInfo{fa496c com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5869): considering ResolveInfo{22785b35 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5869): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5869): enabling receiver ResolveInfo{19072bca com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5869): enabling receiver ResolveInfo{3fa1613b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5869): enabling receiver ResolveInfo{31f89058 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5869): enabling receiver ResolveInfo{3ee075b1 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5869): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,I/UpdateIcingCorporaServi( 5433): UpdateCorporaTask done [took 84 ms] updated apps [took 84 ms] 
,I/ActivityManager( 1014): Killing 4945:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5792): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,W/libprocessgroup( 1014): failed to open /acct/uid_10040/pid_4945/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5792): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,I/FaceInterface( 4962): startFaceScan() : going on
,D/FaceInterface( 4962): startFaceScan() is called.
,D/ContentApp( 1228): startScan() is called.
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,D/ContentApp( 1228): startScan() is end.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,D/ContentApp( 1228): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1228): isNeedToRestore : start
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5897): MountEmulatedStorage()
E/Zygote  ( 5897): v2
,I/libpersona( 5897): KNOX_SDCARD checking this for 10041
I/libpersona( 5897): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5897 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5897): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5897): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5897): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/Icing   ( 1981): Internal init done: storage state 0
,D/TimaKeyStoreProvider( 5897): TimaSignature is unavailable
,D/ActivityThread( 5897): Added TimaKeyStore provider
,I/Icing   ( 1981): Post-init done
,W/GAV2    ( 5715): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager( 1014): Killing 4464:com.google.android.music:main/u0a111 (adj 15): empty #31
,I/SA      ( 5897): [SSP] onCreated
,I/SA      ( 5897): [TPM] There is no property file
,I/SA      ( 5897): [SCU] isHaveSA() - false
,I/Icing   ( 1981): updateResources: need to parse f{com.google.android.gms}
,I/SA      ( 5897): [TPM] getModelProperty : null
I/SA      ( 5897): [TPM] getCSCProperty : null
,I/SA      ( 5897): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5897): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5897): [DM] TFT FEATURE: false
,I/SA      ( 5897): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 5897): [DM] init START
,I/SA      ( 5897): [DM] This device is not a Vodafone
,W/ResourceType( 5897): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 5897): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 5897): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 5897): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 5897): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 5897): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5897): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 5897): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 5897): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 5897): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 5897): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 5897): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 5897): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 5897): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 5897): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 5897): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 5897): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 5897): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 5897): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 5897): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 5897): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 5897): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5897): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 5897): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5897): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 5897): [SCU] isHaveSA() - false
I/SA      ( 5897): support phone number id : false
I/SA      ( 5897): [DM] Supports Ref Jpn : true
,I/SA      ( 5897): [DM] init END
I/SA      ( 5897): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 5897): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
,I/ActivityManager( 1014): Killing 5116:com.google.android.gm/u0a101 (adj 15): empty #31
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_10111/pid_4464/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1014): failed to open /acct/uid_10101/pid_5116/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5928): MountEmulatedStorage()
E/Zygote  ( 5928): v2
I/libpersona( 5928): KNOX_SDCARD checking this for 10100
I/libpersona( 5928): KNOX_SDCARD not a persona
,I/SELinux ( 5928): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5928): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5928): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5928 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 4818:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,W/GAV2    ( 5715): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TimaKeyStoreProvider( 5928): TimaSignature is unavailable
,D/ActivityThread( 5928): Added TimaKeyStore provider
,D/PackageIntentReceiver( 5928): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 5928): Not GearManger package! 
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5951): MountEmulatedStorage()
E/Zygote  ( 5951): v2
I/libpersona( 5951): KNOX_SDCARD checking this for 1000
I/libpersona( 5951): KNOX_SDCARD not a persona
,I/SELinux ( 5951): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5951): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5951): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5951 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1786): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 5951): TimaSignature is unavailable
,D/ActivityThread( 5951): Added TimaKeyStore provider
,W/AccountFeatureHelper( 5715): Write apps_features disabled false
,W/libprocessgroup( 1014): failed to open /acct/uid_10134/pid_4818/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1981): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1981): Module APK com.google.android.play.games already loaded
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/SQLiteConnectionPool( 1981): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,E/Zygote  ( 5969): MountEmulatedStorage()
E/Zygote  ( 5969): v2
I/libpersona( 5969): KNOX_SDCARD checking this for 1000
I/libpersona( 5969): KNOX_SDCARD not a persona
,I/SELinux ( 5969): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5969): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5969 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 5969): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Killing 5279:com.android.calendar/u0a135 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5969): TimaSignature is unavailable
,D/ActivityThread( 5969): Added TimaKeyStore provider
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/AcmsPackageEventListener( 5969): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 5969): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/AcmsService( 5969): Enter Oncreate
,D/AcmsServiceMonitor( 5969): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 5969): creating AcmsCore
,D/AcmsCore( 5969): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 5969): AcmsCore
,D/AcmsCore( 5969): init
D/AcmsCore( 5969): Looper handler is not null
D/AcmsCore( 5969): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5969): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5969): Incrementing - Counter value: 1
D/AcmsCore( 5969): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 5969): onStartCommand
D/AcmsService( 5969): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 5969): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 5969): Incrementing - Counter value: 2
D/AcmsService( 5969): Incremented Counter Value : onStartCommand
,W/libprocessgroup( 1014): failed to open /acct/uid_10135/pid_5279/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityThread( 5969): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsCertificateMngr( 5969): AcmsCertificateMngr
,D/AcmsRevocationMngr( 5969): AcmsRevocationMngr
,I/splitIntent( 1014): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/GAV2    ( 5715): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager( 1014): Killing 5254:com.google.android.talk/u0a104 (adj 15): empty #31
,D/AcmsService( 5969): Inside handle Intent
D/AcmsService( 5969): App added - package name: com.test.thalitest
D/AcmsCore( 5969): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5969): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5969): Incrementing - Counter value: 3
D/AcmsCore( 5969): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 5969): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 5969): Decrementing - Counter value: 2
,W/libprocessgroup( 1014): failed to open /acct/uid_10104/pid_5254/cgroup.procs: No such file or directory
,V/AlarmManager( 1014): waitForAlarm result :4
,D/SensorService( 1014): [SO] 0.038 0.096 10.132
,I/CheckinService( 1981): Done disabling old GoogleServicesFramework version
,I/Mms/MmsApp( 5620):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5620): [start]    fillCache consume time = 1952.382916
D/Mms/ComposeMessageFragment( 5620): fillCache, easy = false
,I/Icing   ( 1981): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,D/AbsListView( 5620): Get MotionRecognitionManager
,D/MotionRecognitionService( 1014):  ssp status : false
,D/Mms/ComposeMessageFragment( 5620): [end]    fillCache consume time = 72.913333
,D/Mms/BubbleViewCache( 5620): fillCache bubble = 1
,D/Icing   ( 1981): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1981): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1014): Killing 5496:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_10069/pid_5496/cgroup.procs: No such file or directory
,D/SSRM:n  ( 1014): SIOP:: AP = 400
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/DBG_POLICYDM( 5700): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5700): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5700): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5700): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5700): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5700): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5700): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/AcmsKeyStoreHelper( 5969):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 5969): Key Store exist
I/AcmsKeyStoreHelper( 5969): Hence loading the keystore file
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,D/AcmsKeyStoreHelper( 5969):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5969): getKeyStoreForApplication success 
D/AcmsCore( 5969): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5969): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5969): Decrementing - Counter value: 1
D/AcmsCore( 5969): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5969): This is NOT a valid MirrorLink app
D/AcmsCore( 5969): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5969): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5969): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5969): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5969): getSvcCounter - Counter value: 0
D/AcmsService( 5969): Enter onDestroy
I/AcmsService( 5969): cleanUp(): inside service clean up
D/AcmsCore( 5969): AcmsCore: inside DeInit
D/AcmsCore( 5969): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5969): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5969): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5969): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5969): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 5969): getSvcCounter - Counter value: 0
,D/AcmsService( 5969): killing acms process
,I/Process ( 5969): Sending signal. PID: 5969 SIG: 9
,I/ActivityManager( 1014): Process ACMS.Process (pid 5969)(adj 0) has died(80,1198)
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 27295(1526KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/40MB, paused 2.449ms total 141.802ms
,I/iu.UploadsManager( 1981): End new media; added: 0, uploading: 0, time: 195 ms
,E/SMD     (  286): DCD OFF
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  286): DCD OFF,
,I/ActivityManager( 1014): Waited long enough for: ServiceRecord{2c7a1afb u0 com.samsung.android.MtpApplication/.MtpService}
,D/PackageManager( 1014): [MSG] MCS_UNBIND
,I/ActivityManager( 1014): Killing 5527:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5527/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  286): DCD OFF
,D/SensorService( 1014): [SO] 0.019 0.077 10.036
,D/SSRM:n  ( 1014): SIOP:: AP = 350,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PowerManagerService( 1014): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1014): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1014): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 1 -> 1
,D/lights  ( 1014): lcd : 1 +
,D/DisplayPowerController( 1014): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1014): lcd : 1 -
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1014): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 5568): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1786): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1786): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1786): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1014): Waited long enough for: ServiceRecord{137f0b8e u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5568): Thread-957(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5568): Thread-957(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5568): Thread-957(ApacheHTTPLog):isShipBuild true
I/System.out( 5568): Thread-957(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5568): Thread-957(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  276): uids 10028
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 502 for uid 10028
,I/qtaguid ( 5568): Tagging socket 44 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5568, getuid(): 10028
,I/qtaguid ( 5568): Tagging socket 48 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5568, getuid(): 10028
,D/Finsky  ( 5568): [970] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5568): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qtaguid ( 5568): Untagging socket 44
,I/System.out( 5568): Thread-957 calls detatch()
,E/SMD     (  286): DCD OFF,
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1786): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5568): Thread-958(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5568): Thread-958(ApacheHTTPLog):isShipBuild true
,I/System.out( 5568): Thread-958(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5568): Thread-958(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5568): Untagging socket 44
,I/qtaguid ( 5568): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5568): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5568): untagSocket(44) failed with errno -22
I/System.out( 5568): Thread-958 calls detatch()
,D/Finsky  ( 5568): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1786): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6004 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,E/Zygote  ( 6004): MountEmulatedStorage()
E/Zygote  ( 6004): v2
I/libpersona( 6004): KNOX_SDCARD checking this for 10012
I/libpersona( 6004): KNOX_SDCARD not a persona
,I/SELinux ( 6004): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6004): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6004): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6004): TimaSignature is unavailable
,I/System.out( 5568): Thread-957(ApacheHTTPLog):isSBSettingEnabled false
D/ActivityThread( 6004): Added TimaKeyStore provider
,I/System.out( 5568): Thread-957(ApacheHTTPLog):isShipBuild true
I/System.out( 5568): Thread-957(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5568): Thread-957(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/ResourcesManager( 6004): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6004): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6004): VM with version 2.1.0 has multidex support
I/MultiDex( 6004): install
I/MultiDex( 6004): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6004): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6004): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6004): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5006f32: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6004): Installed default security provider GmsCore_OpenSSL
,I/qtaguid ( 5568): Untagging socket 44
,I/qtaguid ( 5568): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5568): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5568): untagSocket(44) failed with errno -22
I/System.out( 5568): Thread-957 calls detatch()
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1014): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1014): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1014): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6004): Reading stored module config
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1786): callingUid 10012, callindPid: 1786
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6004): Loading module com.google.android.gms.car from APK com.google.android.gms
,E/MDM     ( 1786): [246] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1981): Restart initialization of location
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1786): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1786): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1786): No location to return for getLastLocation()
,W/FusedLocationProvider( 1786): location=null
,D/NativeLibraryUtils( 6004): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6004): Connecting to CarCallService...
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 6004): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6004): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6004): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6004): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6004): Creating a new PhoneAdapter instance
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6004): setListener: com.google.android.gms.car.dn@2ec567a9
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6004): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6004): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 6004): Package validated; name: com.android.vending
,V/Finsky  ( 5568): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1786): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5568): Thread-958(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5568): Thread-958(ApacheHTTPLog):isShipBuild true
I/System.out( 5568): Thread-958(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5568): Thread-958(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5568): Untagging socket 44
,I/qtaguid ( 5568): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5568): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5568): untagSocket(44) failed with errno -22
I/System.out( 5568): Thread-958 calls detatch()
,W/ResourcesManager( 5568): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5568): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5568): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5568): [1] DailyHygiene.access$600: Logging device features
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/AlarmManager( 1014): waitForAlarm result :4
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/DeviceConnectionService( 1786): client connected with version: 8296000
,D/Finsky  ( 5568): [980] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1786): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5568): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5568): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/System.out( 5568): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5568): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5568): (HTTPLog)-Static: isShipBuild true
I/System.out( 5568): (HTTPLog)-Thread-968-429187259: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5568): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  276): uids 10028
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 502 for uid 10028
,I/System.out( 5568): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/ActivityManager( 1014): Killing 5415:com.samsung.aasaservice/1000 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/IcingInternalCorpora( 1981): getNumBytesRead when not calculated.
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5415/cgroup.procs: No such file or directory
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1014): waitForAlarm result :8
,E/Watchdog( 1014): !@Sync 2
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,D/PowerManagerService( 1014): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1014): Nap time (uid 1000)...
,D/PowerManagerService( 1014): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
,I/PowerManagerService( 1014): !@[ps] Screen__Off - 0 :  dream(timeout) (2)
I/PowerManagerService( 1014): Going to sleep due to screen timeout (uid 1000)...
D/DisplayPowerController( 1014): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1014): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1014): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1014): [PWL] sb acquire: PowerManagerService.Broadcasts
,V/WindowOrientationListener( 1014): WindowOrientationListener disabled
,D/SensorService( 1014): [SO] activate (ident=0xb8746010, enabled=0)
D/PowerManagerService( 1014): SecHardwareInterface.setBatteryADC : false
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 1, handle 0, en 0,
D/PowerManagerService( 1014): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
,I/SurfaceFlinger(  256): id=12 createSurf (720x1280),-1 flag=20004, DolorFade
D/PowerManagerService( 1014): handleSandman : startDream(true)
E/PowerManagerService( 1014): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1014): Sleeping (uid 1000)...
D/PowerManagerService( 1014): [s] UserActivityState : 4 -> 0
,D/PowerManagerService( 1014): Excessive delay in ColorFade : createSurface: 11ms,
,I/Adreno-EGL( 1014): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
,I/Adreno-EGL( 1014): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1014): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1014): Local Branch: 
I/Adreno-EGL( 1014): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1014): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1014):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/SensorManager( 1014): unregisterListener ::   ,
,D/KeyguardViewMediator( 1177): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1177): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1177): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1177): notifyScreenOffLocked
,I/DBG_DM  ( 3083): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,D/KeyguardViewMediator( 1177): timeout : 5000
,V/ActivityThread( 3083): updateVisibility : ActivityRecord{5ebc8e5 token=android.os.BinderProxy@a184460 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/KeyguardViewMediator( 1177): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 1177): handleNotifyScreenOff
,D/VolumePanel( 1177): onScreenTurnedOff()
D/VolumePanel( 1177): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1177): mCoverBroadcastReceiver: Screen OFF end
,D/SecKeyguardClockSingleView( 1177): onScreenTurnedOff
,D/PowerManagerService( 1014): Excessive delay in ColorFade : createEglContext: 44ms
,E/SmartFaceService( 1014): onReceive: android.intent.action.SCREEN_ON
,W/System.err( 1014): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,W/System.err( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1014): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1014): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1014): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1014): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1014): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1014): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1014): 	at libcore.io.Posix.open(Native Method)
E/SmartFaceService( 1014): fail to set sysfs 1
W/System.err( 1014): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1014): 	... 10 more
,D/PermissionCache(  256): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (167 us)
,D/InputMethodManagerService( 1014): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,D/MotionRecognitionService( 1014):   mReceiver.onReceive : ACTION_SCREEN_ON,
E/MotionRecognitionService( 1014):  handler : SCREEN_ON end
,D/NotificationService( 1014): ACTION_SCREEN_ON
D/LightsService( 1014): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1014) 
D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/PowerManagerService( 1014): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 24ms,
,D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=on
V/voice   (  281): voice_set_parameters: enter: screen_state=on
V/voice   (  281): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=on,
V/msm8974_platform(  281): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  281): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  281): adev_set_parameters: exit
,D/IpRemoteDisplayController( 1014): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1014): Bridge Server is not available
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.intent.action.SCREEN_ON
,E/WifiNative-wlan0( 1014): do suspend false
,I/wpa_supplicant( 2142): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2142): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2142): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 2142): Scan requested (ret=0) - scan timeout 30 seconds
,D/PersonaManagerService( 1014): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1014): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1440): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/NfcService( 1440): call the applyRouting
,D/accuweather( 1724): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1724): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1724): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/PowerManagerService( 1014): Excessive delay in ColorFade : initGLShaders: 39ms
,D/accuweather( 1724): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
,D/PowerManagerService( 1014): Excessive delay in ColorFade prepare: 134ms
D/DisplayPowerController( 1014): ColorFade: onAnimationStart
D/DisplayPowerController( 1014): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1014): performScreenOffTransition : no brightness animation
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1766): getNextShiftState() cursorCapsMode : 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LightsService( 1014): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1014) 
,D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1014): turn on LED for fully charged
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1014): write_int failed to open -1
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SSRM:n  ( 1014): SIOP:: AP = 340
,E/SmartFaceService( 1014): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1014): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,W/System.err( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1014): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1014): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SmartFaceService( 1014): fail to set sysfs 0
W/System.err( 1014): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1014): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1014): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1014): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1014): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1014): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1014): 	... 10 more
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,D/SamsungIME( 1766): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/MotionRecognitionService( 1014):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 1014):  handler : SCREEN_OFF end 
,D/NotificationService( 1014): ACTION_SCREEN_OFF
D/LightsService( 1014): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1014) 
,D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=off
,V/voice   (  281): voice_set_parameters: enter: screen_state=off
V/voice   (  281): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  281): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  281): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  281): adev_set_parameters: exit
,I/BackgroundCompactionService( 1014): Schedule Type1 BGCompaction
,D/daemonapp( 1301): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1301): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/IpRemoteDisplayController( 1014): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1014): Bridge Server is not available
,D/daemonapp( 1301): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1301): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1301): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1301): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1301): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1301): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1301): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1301): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1301): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1454971860000
,D/daemonapp( 1301): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1454950355855
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1301): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,I/BatteryStatsDumper( 1014): In refreshStats isReason Screen ON/OFF: true
,D/daemonapp( 1301): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1301): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1301): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
,E/daemonapp( 1301): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
,E/WifiNative-wlan0( 1014): do suspend true
,V/EmergencyMode( 1412): [EmergencyStateReceiver] binteractive [false] why[3]
,D/PersonaManagerService( 1014): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1014): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1440): call the applyRouting
,D/DisplayPowerState( 1014): !@ ColorFade entry
,D/DisplayPowerController( 1014): ColorFade: onAnimationEnd
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 0 -> 0
D/lights  ( 1014): lcd : 0 +
D/DisplayPowerController( 1014): performScreenOffTransition : no brightness animation
,D/accuweather( 1724): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1724): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,I/BatteryStatsDumper( 1014): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1014): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1014): Previous Battery Level: 0 Current Level: 100 Delta: -100
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/lights  ( 1014): lcd : 0 -
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 0 -> 0
D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/DisplayPowerController( 1014): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1014): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1014): [PWL] sb release: PowerManagerService.Display
,D/accuweather( 1724): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
,D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1014): Got set_interactive hint
,D/DisplayManagerService( 1014): !@display_state: ON -> OFF
,D/SurfaceFlinger(  256): Set power mode=0, type=0 flinger=0xb6fc3690
D/qdhwcomposer(  256): hwc_setPowerMode: Setting mode 0 on display: 0
,I/DisplayManagerService( 1014): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
V/ActivityManager( 1014): Display changed displayId=0
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 1724): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1724): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1724): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1724): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,D/StatusBar.NetworkController( 1177): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1935): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/PowerManagerService( 1014): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:n  ( 1014): SIOP:: AP = 340
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1724): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1724): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1724): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1724): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1724): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1724): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1724): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/CAR.SERVICE( 6004): mConnectedToCar = false, abort
,E/ActivityThread( 6004): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3e5bbb71 that was originally bound here
E/ActivityThread( 6004): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3e5bbb71 that was originally bound here
E/ActivityThread( 6004): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6004): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6004): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6004): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6004): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6004): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6004): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6004): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6004): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6004): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6004): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6004): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6004): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6004): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 6004): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 6004): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 6004): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6004): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6004): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6004): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6004): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6004): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6004): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 6004): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2da2af30 that was originally bound here
E/ActivityThread( 6004): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2da2af30 that was originally bound here
E/ActivityThread( 6004): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6004): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6004): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6004): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6004): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6004): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6004): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6004): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6004): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6004): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6004): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6004): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6004): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 6004): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 6004): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 6004): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6004): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6004): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6004): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6004): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6004): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6004): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/ActivityManager( 1014): Unbind failed: could not find connection for android.os.BinderProxy@ce65d9c
I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  256): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl( 1014): Excessive delay in setPowerMode(): 256ms
E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
D/PowerManagerService( 1014): Excessive delay in !@display_state: OFF: 258ms
I/libsuspend( 1014): !@autosuspend_wakeup_count_enable
I/libsuspend( 1014): !@autosuspend_wakeup_count_enable done
D/PowerManagerService( 1014): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 273ms
I/PowerManagerService( 1014): [PWL] Off : 0s ago
I/PowerManagerService( 1014): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1014): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1014): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=1014, ws=null) (elapsedTime=367)
,I/BatteryStatsDumper( 1014): Writing to database completed
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/SSRM:a  ( 1014): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1014): SettingsAirViewInfo:: 000000000
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 2142): nl80211: Received scan results (4 BSSes),
,D/WifiP2pService( 1014): InactiveState{ what=147461 }
D/WifiP2pService( 1014): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1014): DefaultState{ what=147461 },
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardViewMediator( 1177): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1177): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1177): *** Keyguard wallpaper service already unbounded
,I/PowerManagerService( 1014): [PWL] Off : 5s ago
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  286): DCD OFF,
,V/AlarmManager( 1014): waitForAlarm result :8,
,D/SSRM:n  ( 1014): SIOP:: AP = 310
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1014): onStart. jobID=801
,I/BackgroundCompactionService( 1014): onStart done. jobID=801
,I/BackgroundCompactionService( 1014): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1014): compact_memory command done
,D/Finsky  ( 5568): [970] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5568): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/PowerManagerService( 1014): [PWL] Off : 15s ago
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged,
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 300,
,E/SMD     (  286): DCD OFF,
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF
,E/Watchdog( 1014): !@Sync 3
,I/Atfwd_Sendcmd(  312): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  312): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager( 1014): waitForAlarm result :4
,V/AlarmManager( 1014): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManagerEXT( 1014): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1014): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,I/PowerManagerService( 1014): [PWL] Off : 30s ago
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,I/art     ( 1786): Explicit concurrent mark sweep GC freed 38596(2MB) AllocSpace objects, 17(272KB) LOS objects, 40% free, 12MB/21MB, paused 1.166ms total 65.320ms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1786): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1786): Vacuum at: now=1454950389811 tag=VacuumService
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/FactoryTest( 5337): Not factory mode
,D/FactoryTest( 5337): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5337): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5337): still no open session command from host, so toast
,W/ContextImpl( 5337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
I/Timeline( 5337): Timeline: Activity_launch_request id:com.android.settings time:114101
E/PersonaManagerService( 1014): inState():  stateMachine is null !!
,I/PersonaManagerService( 1014): PersonaId don't exist
I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1014): mDVFSHelper.acquire(),
,V/ActivityManager( 1014): Display changed displayId=0
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1014): Focused application set to: xxxx
,D/InputDispatcher( 1014): Focus left window: 3083
,E/MTPRx   ( 5337): started activity for popup
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5337): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5337): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5337): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5337): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5337): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5337): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5337): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/InputDispatcher( 1014): Focused application set to: xxxx
,D/InputDispatcher( 1014): Focus entered window: 3083
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1014): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@102480d0 attribute=android.view.inputmethod.EditorInfo@2faa68c9, token = android.os.BinderProxy@297829c2
,D/SamsungIME( 1766): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/SettingsReceiverActivity( 5337): dev.kiessupport is : TRUE
,D/PhoneWindow( 5337): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5337): *FMB* installDecor flags : 8388610
,I/DBG_DM  ( 3083): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 3083): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 30
,I/DBG_DM  ( 3083): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 3083): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3083): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 30
,I/DBG_DM  ( 3083): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3083): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3083): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3083): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1014): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 3083): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 30
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3083): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 3083): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3083): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3083): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3083): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,I/DBG_DM  ( 3083): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/Timeline( 3083): Timeline: Activity_idle id: android.os.BinderProxy@a184460 time:114339
,V/ActivityThread( 3083): updateVisibility : ActivityRecord{5ebc8e5 token=android.os.BinderProxy@a184460 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 1014): mDVFSHelper.release(),
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,D/TaskPersister( 1014): removeObsoleteFile: deleting file=7_task.xml,
,E/SMD     (  286): DCD OFF
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/SSRM:n  ( 1014): SIOP:: AP = 290,
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,I/PowerManagerService( 1014): [PWL] Off : 50s ago
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 1014): !@Sync 4
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 270
,E/SMD     (  286): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 75s ago
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 270
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1014): waitForAlarm result :8,
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1014): !@Sync 5
,I/ClearcutLoggerApiImpl( 1786): disconnect managed GoogleApiClient
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1014): [PWL] Off : 105s ago,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF,
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1014): !@Sync 6
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,I/Atfwd_Sendcmd(  312): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  312): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,V/AlarmManager( 1014): waitForAlarm result :8,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/Watchdog( 1014): !@Sync 7,
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  286): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 8,
,I/PowerManagerService( 1014): [PWL] Off : 180s ago
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  286): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 9,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
I/ServiceManager(  312): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 225s ago,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1014): initializing...
,I/TLC_TIMA_PKM_initialize( 1014): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1014): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1014): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1014): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1014): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1014): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1014): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: ( 1014): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1014): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1014): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1014): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1014): Trustlet response is completed
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1014): !@Sync 10,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,I/Atfwd_Sendcmd(  312): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  312): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/Watchdog( 1014): !@Sync 11,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 2
,I/PowerManagerService( 1014): [PWL] Off : 275s ago
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 12,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,V/AlarmManager( 1014): waitForAlarm result :8,
V/AlarmManager( 1014): No more alarm at this time.nowELAPSED=403113 batch.start=797799
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 13,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1014): [PWL] Off : 330s ago,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD OFF,
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  286): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 14,
,I/Atfwd_Sendcmd(  312): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  312): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,E/SMD     (  286): DCD OFF
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1014): waitForAlarm result :8,
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 15,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,I/PowerManagerService( 1014): [PWL] Off : 390s ago
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD OFF,
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/bootchecker(  309): bootchecker wake up!!
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD OFF
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD OFF
,E/Watchdog( 1014): !@Sync 16
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
I/MotionRecognitionService( 1014): Plugged
D/HeadsetStateMachine( 2620): Disconnected process message: 10
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/Watchdog( 1014): !@Sync 17
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PowerManagerService( 1014): [PWL] Off : 455s ago
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 18,
,I/Atfwd_Sendcmd(  312): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  312): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,I/Atfwd_Daemon(  312): Stop the daemon....
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/Watchdog( 1014): !@Sync 19
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged,
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 525s ago
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1014): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 20,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 21
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 22,
,I/PowerManagerService( 1014): [PWL] Off : 600s ago,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 23,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 24,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 680s ago,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/Watchdog( 1014): !@Sync 25
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1014): Plugged
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1,
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 1981): Aggregate from 1454948815773 (log), 1454948815773 (data)
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 1014): !@Sync 26
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1014): stay LED for fully charged
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/Watchdog( 1014): !@Sync 27
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 765s ago,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 28,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 29,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK,
V/AlarmManager( 1014): waitForAlarm result :4
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  286): DCD OFF
,E/Watchdog( 1014): !@Sync 30,
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1014): [PWL] Off : 855s ago
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1786): Scheduling Phenotype for one-off execution 4591 seconds from now (1454951219461)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1786): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1786): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1786): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1786): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1786): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1786): (HTTPLog)-Static: isShipBuild true
I/System.out( 1786): (HTTPLog)-Thread-252-619766930: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1786): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  276): uids 10012
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1786): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1786): Tagging socket 80 with tag 1000120100000000{268440065,0} for uid -1, pid: 1786, getuid(): 10012
,I/qtaguid ( 1786): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1786, getuid(): 10012
,V/AlarmManager( 1014): waitForAlarm result :8
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1786): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1786): Tagging socket 80 with tag 1000120100000000{268440065,0} for uid -1, pid: 1786, getuid(): 10012
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1786): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1786): Tagging socket 80 with tag 1000120100000000{268440065,0} for uid -1, pid: 1786, getuid(): 10012
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/Watchdog( 1014): !@Sync 31,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 32,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 33,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 950s ago
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 34,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 35,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 36
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 37,
,I/PowerManagerService( 1014): [PWL] Off : 1050s ago,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 38,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged,
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,E/Watchdog( 1014): !@Sync 39,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1014): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1014): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1014): Updating Usage Statistics in DB @ 1454951492620
,I/ApplicationPolicy( 1014): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1014): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1014): ::isTableExists: Table exists 
,I/ApplicationUsage( 1014): Done Updating Usage Statistics in DB @ 1454951492936
,E/SMD     (  286): DCD OFF
,E/Watchdog( 1014): !@Sync 40,
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1014): [PWL] Off : 1155s ago,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,E/Watchdog( 1014): !@Sync 41,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF,
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6558): 
D/AndroidRuntime( 6558): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6558): CheckJNI is OFF
D/AndroidRuntime( 6558): readGMSProperty: start
D/AndroidRuntime( 6558): readGMSProperty: already setted!!
D/AndroidRuntime( 6558): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6558): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6558): readGMSProperty: end
D/AndroidRuntime( 6558): addProductProperty: start
E/SMD     (  286): DCD OFF
E/AffinityControl( 6558): AffinityControl: registerfunction enter
D/AndroidRuntime( 6558): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1014): START PACKAGE DELETE: observer{906012464}
D/PackageManager( 1014): pkg{<packageName>}
D/PackageManager( 1014): user{0}
D/PackageManager( 1014): caller{2000}
D/PackageManager( 1014): flags{3}
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1014): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1014): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1014): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1014): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1014): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1014): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1014): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1014): !@killApplicatoin: 10155, uninstall pkg
I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
W/ActivityManager( 1014): CustomStartingWindow se packge removed so remove capture also
I/art     ( 5433): Explicit concurrent mark sweep GC freed 346(24KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 702us total 30.326ms
I/art     ( 4928): Explicit concurrent mark sweep GC freed 2304(130KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 706us total 33.065ms
I/InputReader( 1014): Reconfiguring input devices.  changes=0x00000010
I/art     ( 4738): Explicit concurrent mark sweep GC freed 15317(823KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 1.167ms total 45.753ms
E/SamsungIME( 1766): mOCRHelper is null
W/GeofencerStateMachine( 1786): Ignoring removeGeofence because network location is disabled.
I/art     ( 1981): Explicit concurrent mark sweep GC freed 4735(324KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 14MB/18MB, paused 1.285ms total 75.632ms
I/KLMS-2.5.183: ( 3490): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Feb 08 18:12:19 GMT+01:00 2016
D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
D/RegisteredComponentCache( 1440): Collect Tech packages for Knox
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/PersonaManager( 1440): isKioskContainerExistOnDevice
I/KLMS-2.5.183: ( 3490): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1014): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1014): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
I/PackagesMonitor( 4962): PackagesMonitor onReceive :com.test.thalitest
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3490): KLMSIntentService(): onCreate()
E/Zygote  ( 6572): MountEmulatedStorage()
I/libpersona( 6572): KNOX_SDCARD checking this for 10149
E/Zygote  ( 6572): v2
I/libpersona( 6572): KNOX_SDCARD not a persona
I/SELinux ( 6572): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6572): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6572): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6572 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  304): Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 21.290ms
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1014): mCursor = null
D/RCPManagerService( 1014): PackageReceiver onReceive()
I/HarmonyEASService( 1014): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1014): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1014): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1014): OtpDbHelper::getInstance New instance created
I/KLMS-2.5.183: ( 3490): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/OTPFW   ( 1014): DBIntegrity::getInstance - New instance created
D/TimaKeyStoreProvider( 6572): TimaSignature is unavailable
D/ActivityThread( 6572): Added TimaKeyStore provider
D/OTPFW   ( 1014): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 17.248ms
E/SQLiteLog( 4738): (284) automatic index on crash_info_summary(package_name_touched)
I/OTPFW   ( 1014): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1014): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1014): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1014): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1014): uID is 10155
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
I/KLMS-2.5.183: ( 3490): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.183: ( 3490): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 16.885ms
I/KLMS-2.5.183: ( 3490): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.183: ( 3490): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.183: ( 3490): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
E/Zygote  ( 6587): MountEmulatedStorage()
E/Zygote  ( 6587): v2
I/libpersona( 6587): KNOX_SDCARD checking this for 10094
I/libpersona( 6587): KNOX_SDCARD not a persona
I/SELinux ( 6587): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6587 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
V/AlarmManagerEXT( 1014): com.test.thalitest(10155) is removed.
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/SSRM:aZ ( 1014): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1014): uID is 10155
I/SELinux ( 6587): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.test.thalitest
E/SELinux ( 6587): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
D/PersonaManager( 1440): isKioskContainerExistOnDevice
D/RegisteredServicesCache( 1440): empty dynamic service
D/Mms/FreeMessageStatusReceiver( 5620): onReceive, action : android.intent.action.PACKAGE_REMOVED
D/ActivityManager( 1014): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/TactileAssist( 1014): enable value -1
I/TactileAssist( 1014): internal enable value -1
I/TactileAssist( 1014): intensity value -1
I/TactileAssist( 1014): saveAppList value true
I/art     ( 4738): Explicit concurrent mark sweep GC freed 1132(55KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 996us total 56.060ms
W/ContextImpl( 5083): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
D/Mms/FreeMessageReceiverService( 5620): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 5620): onHandleIntent: ACTION_PACKAGE_REMOVED
I/TactileAssist( 1014): List of disabled apps :
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ThemeInfoUtil( 6572): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 6572): isCurrentFestival = false
D/BadgeProvider( 5812): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5812): sendNotify, [notify] : null
D/BadgeProvider( 5812): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5812): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5812): update, [UpdateCount] : 1
D/TimaKeyStoreProvider( 6587): TimaSignature is unavailable
D/ActivityThread( 6587): Added TimaKeyStore provider
E/SQLiteLog( 4738): (10) POSIX Error : 11 SQLite Error : 3850
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
E/SQLiteLog( 4738): (10) POSIX Error : 11 SQLite Error : 3850
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/RCPManager( 5511):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1014):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1014): queryAllProviders():  providerCallBack is not register for 0
I/TapandpayWidget:TapandpayAppWidgetProvider( 5682): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 5682): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils( 5682): Clear T&P info.
D/Compatibility( 5869): onReceive() it will make start service
D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
I/KLMS-2.5.183: ( 3490): KLMSIntentService(): listeningToPackageRemoved().END
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/TapandpayWidget:TapandpayAppWidgetProvider( 5682): Widget is not attached.
D/ActivityManager( 1014): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
I/KLMS-2.5.183: ( 3490): KLMSIntentService(): onDestroy()
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5869): onHandleIntent()
I/UpdateIcingCorporaServi( 5433): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 5869): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10155, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
E/Zygote  ( 6607): MountEmulatedStorage()
I/libpersona( 6607): KNOX_SDCARD checking this for 10160
E/Zygote  ( 6607): v2
I/libpersona( 6607): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6607 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/SELinux ( 6607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6607): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6607): TimaSignature is unavailable
D/ActivityThread( 6607): Added TimaKeyStore provider
I/art     ( 1014): Explicit concurrent mark sweep GC freed 68584(6MB) AllocSpace objects, 253(3MB) LOS objects, 33% free, 28MB/42MB, paused 3.333ms total 390.166ms
D/Compatibility( 5869): found: 2
D/Compatibility( 5869): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5869): skipping ResolveInfo{29925a04 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5869): considering ResolveInfo{2dd5bbed com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5869): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5869): enabling receiver ResolveInfo{29916a22 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5869): enabling receiver ResolveInfo{398cbcb3 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5869): enabling receiver ResolveInfo{7dd1270 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5869): enabling receiver ResolveInfo{275f29e9 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6622): MountEmulatedStorage()
E/Zygote  ( 6622): v2
I/libpersona( 6622): KNOX_SDCARD checking this for 1000
I/libpersona( 6622): KNOX_SDCARD not a persona
D/Compatibility( 5869): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
I/SELinux ( 6622): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6622): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/elm:15183( 6587): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
E/SELinux ( 6622): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6622 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
D/PackageManager( 1014): delete codoeFile: 
D/elm:15183( 6587): ELMEngine.ELMEngine( context ).
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 6607): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/AASAuninstall( 1014): userId = 0, info.removedAppID = -1, info.uid = 10155, packageName = com.test.thalitest
I/AASA_removePackage( 1014): UID=10155 Target=com.test.thalitest
D/PackageManager( 1014): result of delete: 1{906012464}
D/elm:15183( 6587): MDMBridge.setEnterpriseBridge()
D/AndroidRuntime( 6558): Shutting down VM
E/Zygote  ( 6633): MountEmulatedStorage()
E/Zygote  ( 6633): v2
I/libpersona( 6633): KNOX_SDCARD checking this for 10003
I/libpersona( 6633): KNOX_SDCARD not a persona
I/SELinux ( 6633): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6633 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
I/SELinux ( 6633): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6633): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/[0]UMC:UMCContentProvider( 6607): @onCreate
D/elm:15183( 6587): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/SSRM:n  ( 1014): SIOP:: AP = 260
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
D/[0]UMC:Core( 6607): onCreate(): 
D/elm:15183( 6587): ElmAgentService : onCreate()
D/[0]UMC:Core( 6607): @isManagedProfileUser
D/[0]UMC:Core( 6607): userId: 0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/[0]UMC:Core( 6607): userInfo: UserInfo{0:Thali Test:13}
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/[0]UMC:Core( 6607): userInfo.isManagedProfile() : false
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/elm:15183( 6587): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6587): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6587): MDMBridge.getInstance()
D/elm:15183( 6587): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 6587): MDMBridge.getAllLicenseInfoFromSDK()
D/TimaKeyStoreProvider( 6622): TimaSignature is unavailable
D/ActivityThread( 6622): Added TimaKeyStore provider
E/Zygote  ( 6656): MountEmulatedStorage()
I/libpersona( 6656): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6656): v2
I/libpersona( 6656): KNOX_SDCARD not a persona
I/SELinux ( 6656): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6656 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/elm:15183( 6587): ElmAgentService : onDestroy().
I/SELinux ( 6656): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6656): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6633): TimaSignature is unavailable
I/ActivityManager( 1014): Killing 5452:com.google.android.partnersetup/u0a15 (adj 15): empty #31
D/ActivityThread( 6633): Added TimaKeyStore provider
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/[0]UMC:DeviceInfo( 6607): USA==US==
D/TimaKeyStoreProvider( 6656): TimaSignature is unavailable
D/ActivityThread( 6656): Added TimaKeyStore provider
D/UserAnalysis.PlaceProvider( 6633): PlaceProvider onCreate()
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ContextImpl( 6622): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/UserAnalysis.SecureDbManager( 6633): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 6633): SecurePlaceDbHelper() 
D/UserAnalysis( 6633): Create SecureDbHelper
I/ActivityManager( 1014): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6671 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/Zygote  ( 6671): MountEmulatedStorage()
I/libpersona( 6671): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6671): v2
I/libpersona( 6671): KNOX_SDCARD not a persona
I/SELinux ( 6671): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6671): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6671): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/IntelligenceServiceApplication( 6633): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6633): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 6671): TimaSignature is unavailable
D/ActivityThread( 6671): Added TimaKeyStore provider
D/AASAservice-UpdateReceiver( 6656): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
D/USER_AGENT( 6607): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
D/IntelligenceServiceApplication( 6633): no applications having user consent for prediction
W/System.err( 6656): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6656): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6656): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6656): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6656): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6656): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6656): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6656): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6656): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6656): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6656): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6656): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6656): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/ActivityManager( 1014): Killing 5649:com.sec.pcw.device/1000 (adj 15): empty #31
W/art     ( 6558): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/[0]UMC:AdminManager( 6607): init - start
I/UpdateIcingCorporaServi( 5433): UpdateCorporaTask done [took 368 ms] updated apps [took 368 ms] 
I/ActivityManager( 1014): Killing 5667:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetection::stopService] Service stopped.
I/ActivityManager( 1014): Killing 5476:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
D/[0]UMC:AdminManager( 6607): loadAdmins
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/SQLiteLog( 4738): (284) automatic index on crash_info_summary(package_name_touched)
D/AcmsPackageEventListener( 6671): Received: android.intent.action.PACKAGE_REMOVED
D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/[0]UMC:AdminManager( 6607): init - end
D/GSLBManager( 6607): migrateStoredUrlFromOldPref
W/ContextImpl( 6671): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
D/BadgeProvider( 5812): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5812): sendNotify, [notify] : null
D/BadgeProvider( 5812): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5812): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5812): update, [UpdateCount] : 1
D/AcmsService( 6671): Enter Oncreate
D/AcmsServiceMonitor( 6671): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6671): creating AcmsCore
D/AcmsCore( 6671): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6671): AcmsCore
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
D/AcmsCore( 6671): init
D/AcmsCore( 6671): Looper handler is not null
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
D/AcmsCore( 6671): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6671): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
D/AcmsServiceMonitor( 6671): Incrementing - Counter value: 1
D/AcmsCore( 6671): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 6671): onStartCommand
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
D/AcmsService( 6671): Action: android.intent.action.PACKAGE_REMOVED
D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
D/AcmsServiceMonitor( 6671): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6671): Incrementing - Counter value: 2
D/AcmsService( 6671): Incremented Counter Value : onStartCommand
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
D/AcmsCertificateMngr( 6671): AcmsCertificateMngr
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 6633): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/AcmsRevocationMngr( 6671): AcmsRevocationMngr
D/GSLBManager( 6607): migrateStoredUrlFromOldPref : Migration Not Needed
D/[0]UMC:UMCAdmin( 6607): deactivateUMCAdminIfNotRequired : -1
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
E/[0]UMC:Utils( 6607): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 6607): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 6607): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 6607): isContainer : 0
D/BluetoothAdapter( 6633): cancelDiscovery
D/EnterpriseDeviceManagerService( 1014): isManagedProfileUser(): userId = 0
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink

```
