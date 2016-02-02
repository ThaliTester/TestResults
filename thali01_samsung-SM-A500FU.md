#### Test 575312431be71d2_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
I/SystemInfo( 5030): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5030): DocumentService is process the pending files at end
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
--------- beginning of system
D/ActivityManager( 1016): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
I/DocumentService( 5030): DocumentService onCreate ... service
W/LocalSuggestAlbumData( 5062): query fail: 
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
W/LocalSuggestAlbumData( 5062): query fail: 
W/LocalSuggestAlbumData( 5062): query fail: 
W/LocalSuggestAlbumData( 5062): query fail: 
W/ContextImpl( 5030): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
D/SettingsProvider( 1016): name = icc_lock_enable
W/ContextImpl( 5030): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
I/SettingSearch/SearchIntentReceiver( 1336): action : com.samsung.settings.CHANGED_ICC_LOCK_ENABLE
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
E/SystemInfo( 5030): [SIOP LEVEL] : 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.sec.smartcard.manager
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.smartcard.manager, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5102): MountEmulatedStorage()
E/Zygote  ( 5102): v2
I/SELinux ( 5102): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5102): KNOX_SDCARD checking this for 10153
I/libpersona( 5102): KNOX_SDCARD not a persona
I/SELinux ( 5102): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5102): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.smartcard.manager for broadcast com.sec.smartcard.manager/com.sec.smartcard.pinservice.SmartCardBroadcastReceiver: pid=5102 uid=10153 gids={50153, 9997, 3001, 3002} abi=armeabi-v7a
I/DocumentService( 5030): [BEGIN SYNC] DocumentService beginIndexing :16
W/ContextImpl( 5030): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
D/SSRM:n  ( 1016): SIOP:: AP = 390
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
D/TimaKeyStoreProvider( 5102): TimaSignature is unavailable
D/ActivityThread( 5102): Added TimaKeyStore provider
W/libprocessgroup( 1016): failed to open /acct/uid_10113/pid_4651/cgroup.procs: No such file or directory
E/File    ( 5030): fail readDirectory() errno=13
E/File    ( 5030): fail readDirectory() errno=13
W/ResourcesManager( 5102): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/SystemInfo( 5030): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5030): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 5030): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :47
E/DocumentService( 5030): [THUMBNAIL] Total Time taken for each file :0
E/        ( 5030): [INDEX] Total time taken for each file :0
I/DocumentService( 5030): DocumentService onDestroy start
I/DocumentService( 5030): DocumentService onDestroy end
I/DocumentService( 5030): DocumentService cleanupEverything start
I/IndexParserThreadsManager( 5030): InterruptedException: null
I/SystemInfo( 5030): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5030): DocumentService cleanupEverything end
I/Process ( 5030): Sending signal. PID: 5030 SIG: 9
I/Mms/MmsApp( 4823):  start initViewCache mms
D/Mms/ComposeMessageFragment( 4823): [start]    fillCache consume time = 1953.665988
D/Mms/ComposeMessageFragment( 4823): fillCache, easy = false
E/SmartCardContentProvider( 5102): onCreate
I/SmartCardBroadcastReceiver( 5102): SmartCardBroadcastReceiver - onReceive() 
I/SmartCardBroadcastReceiver( 5102): Broadcast received for locktype changed 
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.app.popupuireceiver
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5123): MountEmulatedStorage()
E/Zygote  ( 5123): v2
I/libpersona( 5123): KNOX_SDCARD checking this for 1000
I/libpersona( 5123): KNOX_SDCARD not a persona
E/lowmemorykiller(  255): Error writing /proc/5030/oom_score_adj; errno=22
I/ActivityManager( 1016): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5123 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5123): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SELinux ( 5123): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5123): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Process com.samsung.indexservice (pid 5030)(adj 11) has died(101,1165)
D/TimaKeyStoreProvider( 5123): TimaSignature is unavailable
D/ActivityThread( 5123): Added TimaKeyStore provider
D/PopupuiReceiver( 5123): onReceive() getAction : com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED
D/SecContentProvider2( 1016): uri = -1 selection = getSealedState
D/SecContentProvider2( 1016): mCursor = null
I/PopupuiReceiver_KNOX( 5123): getSealedState : true
D/SecContentProvider2( 1016): uri = 15 selection = getSealedHideNotificationMessages
D/SecContentProvider2( 1016): mCursor = null
I/PopupuiReceiver_KNOX( 5123): getSealedHideNotificationMessages : 1
D/SecContentProvider2( 1016): uri = 15 selection = getCheckCoverPopupState
D/SecContentProvider2( 1016): mCursor = null
I/PopupuiReceiver_KNOX( 5123): getCheckCoverPopupState : true
D/PopupuiReceiver( 5123): Action cable connected ! on - 
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.samsung.android.app.powersharing
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.powersharing, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/AbsListView( 4823): Get MotionRecognitionManager
D/MotionRecognitionService( 1016):  ssp status : false
E/Zygote  ( 5139): MountEmulatedStorage()
E/Zygote  ( 5139): v2
I/libpersona( 5139): KNOX_SDCARD checking this for 10122
I/libpersona( 5139): KNOX_SDCARD not a persona
I/SELinux ( 5139): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/Mms/ComposeMessageFragment( 4823): [end]    fillCache consume time = 135.748177
I/SELinux ( 5139): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5139): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.samsung.android.app.powersharing for broadcast com.samsung.android.app.powersharing/.service.BatteryReceiver: pid=5139 uid=10122 gids={50122, 9997} abi=armeabi-v7a
I/ActivityManager( 1016): Waited long enough for: ServiceRecord{3a911b1a u0 com.samsung.hs20settings/.WifiHs20UtilityService}
I/ActivityManager( 1016): Killing 4626:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
D/TimaKeyStoreProvider( 5139): TimaSignature is unavailable
D/ActivityThread( 5139): Added TimaKeyStore provider
W/art     ( 4823): Suspending all threads took: 10.122ms
I/MediaStoreImporter( 4565): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
W/libprocessgroup( 1016): failed to open /acct/uid_10010/pid_4626/cgroup.procs: No such file or directory
I/ActivityManager( 1016): Killing 4721:com.sec.android.cloudagent/u0a2 (adj 15): empty #31
I/PowerSharing.BatteryReceiver( 5139): onReceive : com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.wluc, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5155): MountEmulatedStorage()
E/Zygote  ( 5155): v2
I/libpersona( 5155): KNOX_SDCARD checking this for 10165
I/libpersona( 5155): KNOX_SDCARD not a persona
I/SELinux ( 5155): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.android.app.wluc for broadcast com.sec.android.app.wluc/.PolicyManagerBroadcastReceiver: pid=5155 uid=10165 gids={50165, 9997} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 4758:com.sec.android.diagmonagent/1000 (adj 15): empty #31
I/SELinux ( 5155): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5155): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5155): TimaSignature is unavailable
D/ActivityThread( 5155): Added TimaKeyStore provider
D/Mms/BubbleViewCache( 4823): fillCache bubble = 1
I/PolicyManagerBroadcastReceiver( 5155): onReceive: action = com.sec.intent.ACTION.SSRM_HGL_UPDATE
I/PolicyManagerBroadcastReceiver( 5155): onReceive: width = 720, height = 1280
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5171): MountEmulatedStorage()
E/Zygote  ( 5171): v2
I/libpersona( 5171): KNOX_SDCARD checking this for 1000
I/libpersona( 5171): KNOX_SDCARD not a persona
I/SELinux ( 5171): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuSettingSearch: pid=5171 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 4736:com.google.android.apps.plus/u0a120 (adj 15): empty #31
I/SELinux ( 5171): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5171): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1016): failed to open /acct/uid_10002/pid_4721/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5171): TimaSignature is unavailable
D/ActivityThread( 5171): Added TimaKeyStore provider
D/AssistantMenuSettingSearch( 5171): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
D/AssistantMenuSettingSearch( 5171): Make Setting DB
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.sec.providers.settingsearch
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4758/cgroup.procs: No such file or directory
E/Zygote  ( 5186): MountEmulatedStorage()
E/Zygote  ( 5186): v2
I/libpersona( 5186): KNOX_SDCARD checking this for 10150
I/libpersona( 5186): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=5186 uid=10150 gids={50150, 9997} abi=armeabi-v7a
I/SELinux ( 5186): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/libprocessgroup( 1016): failed to open /acct/uid_10120/pid_4736/cgroup.procs: No such file or directory
I/SELinux ( 5186): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5186): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5186): TimaSignature is unavailable
D/ActivityThread( 5186): Added TimaKeyStore provider
W/ContextImpl( 5171): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:158 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:38 
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.phone
I/ActivityManager( 1016): Killing 4027:com.policydm/1000 (adj 15): empty #31
I/ActivityManager( 1016): Killing 4258:com.samsung.android.sconnect/u0a125 (adj 15): empty #32
I/SettingSearchManagerReceiver( 1460): onReceive : com.samsung.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
I/SettingSearchManagerReceiver( 1460): addSearchInfoDB
I/SettingSearchManagerReceiver( 1460): endInsert
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/WearableService( 1869): callingUid 10012, callindPid: 1869
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/MDM     ( 1869): [247] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/LocationInitializer( 3470): Restart initialization of location
D/AuthorizationBluetoothService( 1869): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5207): MountEmulatedStorage()
I/libpersona( 5207): KNOX_SDCARD checking this for 10101
E/Zygote  ( 5207): v2
I/libpersona( 5207): KNOX_SDCARD not a persona
I/SELinux ( 5207): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5207 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5207): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/GCoreFlp( 1869): No location to return for getLastLocation()
W/FusedLocationProvider( 1869): location=null
E/SELinux ( 5207): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1016): failed to open /acct/uid_10125/pid_4258/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5207): TimaSignature is unavailable
D/ActivityThread( 5207): Added TimaKeyStore provider
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4027/cgroup.procs: No such file or directory
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5207): getAccountsCursor
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5207): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5207): Observing account changes for notifications
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 5207): Error finding the version of the Email provider.....
E/Gmail   ( 5207): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5207): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 5207): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 5207): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 5207): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5207): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5207): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 5207): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5207): We do not support migrating this version of the Email provider.
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/Gmail   ( 5207): getAccountsCursor
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5241): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=5241 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/Zygote  ( 5241): v2
I/libpersona( 5241): KNOX_SDCARD checking this for 10033
I/SELinux ( 5241): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5241): KNOX_SDCARD not a persona
I/SELinux ( 5241): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5241): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimaKeyStoreProvider( 5241): TimaSignature is unavailable
D/ActivityThread( 5241): Added TimaKeyStore provider
E/SQLiteLog( 5207): (283) recovered 108 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
W/ResourcesManager( 5241): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5241): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5241): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/File    ( 5207): fail readDirectory() errno=2
I/Gmail   ( 5207): notifyAccountChanged
I/Gmail   ( 5207): getAccountsCursor
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
W/ResourcesManager( 5241): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5241): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5241): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 5241): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5241): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 5241): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/Gmail   ( 5207): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5207): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5207): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
I/Gmail   ( 5207): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
I/Gmail   ( 5207): getAccountsCursor
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 5258): 
D/AndroidRuntime( 5258): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5258): CheckJNI is OFF
D/AndroidRuntime( 5258): readGMSProperty: start
D/AndroidRuntime( 5258): readGMSProperty: already setted!!
D/AndroidRuntime( 5258): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5258): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5258): readGMSProperty: end
D/AndroidRuntime( 5258): addProductProperty: start
E/SMD     (  291): DCD OFF
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1016): Killing 4575:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/GCM     ( 1869): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
E/AffinityControl( 5258): AffinityControl: registerfunction enter
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.download.DownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AndroidRuntime( 5258): Calling main entry com.android.commands.am.Am
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
D/AndroidRuntime( 5258): Shutting down VM
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/GCoreFlp( 1869): No location to return for getLastLocation()
W/FusedLocationProvider( 1869): location=null
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SafeBrowsingUpdateIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1016): failed to open /acct/uid_10009/pid_4575/cgroup.procs: No such file or directory
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
E/SPPClientService( 4097): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=5292 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 5292): MountEmulatedStorage()
I/libpersona( 5292): KNOX_SDCARD checking this for 10035
E/Zygote  ( 5292): v2
I/libpersona( 5292): KNOX_SDCARD not a persona
I/SELinux ( 5292): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5292): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5292): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5292): TimaSignature is unavailable
D/ActivityThread( 5292): Added TimaKeyStore provider
W/art     ( 5258): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
E/SPPClientService( 5292): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5292): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 5292): PushLog.txt file is not deleted.
D/SPPClientService( 5292): PushLog.txt file is not deleted.
D/SPPClientService( 5292): ============PushLog. stop!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5312): MountEmulatedStorage(),
E/Zygote  ( 5312): v2
I/libpersona( 5312): KNOX_SDCARD checking this for 10035,
I/libpersona( 5312): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=5312 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5312): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Killing 4781:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,I/SELinux ( 5312): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5312): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/art     (  308): Explicit concurrent mark sweep GC freed 8698(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 639us total 21.154ms
,D/TimaKeyStoreProvider( 5312): TimaSignature is unavailable
D/ActivityThread( 5312): Added TimaKeyStore provider
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 17.942ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 17.250ms
,E/SPPClientService( 5312): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5312): [PushClientApplication] Push log off : This is Ship build version
,W/libprocessgroup( 1016): failed to open /acct/uid_10062/pid_4781/cgroup.procs: No such file or directory
,E/LNoti   ( 5312): [PhoneStatusChangeReceiver] This device doesn't register yet.
,D/SPPClientService( 5312): PushLog.txt file is not deleted.
D/SPPClientService( 5312): PushLog.txt file is not deleted.
D/SPPClientService( 5312): ============PushLog. stop!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Killing 4301:com.android.calendar/u0a135 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5330): MountEmulatedStorage()
E/Zygote  ( 5330): v2
I/libpersona( 5330): KNOX_SDCARD checking this for 10104
I/libpersona( 5330): KNOX_SDCARD not a persona
I/SELinux ( 5330): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5330 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/SELinux ( 5330): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5330): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1016): failed to open /acct/uid_10135/pid_4301/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5330): TimaSignature is unavailable
,D/ActivityThread( 5330): Added TimaKeyStore provider,
,W/ResourcesManager( 5330): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel   ( 5330): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 5330): MmsConfig.loadMmsSettings
I/Babel   ( 5330): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 5330): MmsConfig.loadFromDatabase
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/Babel   ( 5330): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5330): MmsConfig.loadFromResources
,E/Babel   ( 5330): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5330): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
W/Settings( 5330): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_StickerModule( 5330): App launched.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5355): MountEmulatedStorage(),
I/ActivityManager( 1016): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=5355 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 5355): v2,
I/libpersona( 5355): KNOX_SDCARD checking this for 1000
I/SELinux ( 5355): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5355): KNOX_SDCARD not a persona,
I/SELinux ( 5355): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5355): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5355): TimaSignature is unavailable
,D/ActivityThread( 5355): Added TimaKeyStore provider
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  283): getCameraInfo: X
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  283): getCameraInfo: X
,W/VideoCapabilities( 5330): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5330): Unsupported mime audio/evrc
,W/AudioCapabilities( 5330): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5330): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5330): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5330): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5330): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5330): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5330): Unsupported mime audio/evrc
,W/VideoCapabilities( 5330): Unsupported mime video/wvc1
,W/VideoCapabilities( 5330): Unsupported mime video/x-ms-wmv
,I/DIAGMON_AGENT( 5355): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/VideoCapabilities( 5330): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5330): Unsupported mime video/wvc1
,W/VideoCapabilities( 5330): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5330): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5330): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5330): Unsupported mime video/mp43
,W/VideoCapabilities( 5330): Unsupported mime video/sorenson
,W/VideoCapabilities( 5330): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5330): Unsupported profile 4 for video/mp4v-es
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/ActivityManager( 1016): Killing 4198:com.android.providers.calendar/u0a42 (adj 15): empty #31
,I/DIAGMON_AGENT( 5355): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 5355): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 5355): [com.diagmondm.XDMBroadcastReceiver(33/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager( 1016): Killing 4436:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,I/DBG_DM  ( 3086): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5371): MountEmulatedStorage()
,E/Zygote  ( 5371): v2
I/libpersona( 5371): KNOX_SDCARD checking this for 10142
I/libpersona( 5371): KNOX_SDCARD not a persona
,I/SELinux ( 5371): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5371 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5371): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5371): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5371): TimaSignature is unavailable
,D/ActivityThread( 5371): Added TimaKeyStore provider
,V/TaskCloserActivity( 5371): TaskCloserActivity enter()
,V/TaskCloserActivity( 5371): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5386 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
I/ActivityManager( 1016): Killing 4165:com.osp.app.signin/u0a41 (adj 15): empty #31
,E/Zygote  ( 5386): MountEmulatedStorage()
E/Zygote  ( 5386): v2
I/libpersona( 5386): KNOX_SDCARD checking this for 10135
I/libpersona( 5386): KNOX_SDCARD not a persona
,I/SELinux ( 5386): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5386): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5386): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5386): TimaSignature is unavailable
,D/ActivityThread( 5386): Added TimaKeyStore provider
,W/ResourcesManager( 5386): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5386): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5386): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/libprocessgroup( 1016): failed to open /acct/uid_10042/pid_4198/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4436/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10041/pid_4165/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5407): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5407 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 5407): v2
I/libpersona( 5407): KNOX_SDCARD checking this for 10042
I/SELinux ( 5407): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5407): KNOX_SDCARD not a persona
,I/SELinux ( 5407): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Killing 4799:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,E/SELinux ( 5407): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5407): TimaSignature is unavailable
,D/ActivityThread( 5407): Added TimaKeyStore provider
,W/ResourcesManager( 5407): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5407): CalendarProvider2.onCreate() called
,W/libprocessgroup( 1016): failed to open /acct/uid_10157/pid_4799/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5425 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 5425): MountEmulatedStorage()
E/Zygote  ( 5425): v2
I/libpersona( 5425): KNOX_SDCARD checking this for 1000
I/libpersona( 5425): KNOX_SDCARD not a persona
,I/SELinux ( 5425): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
I/SELinux ( 5425): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5425): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SQLiteLog( 5407): (284) automatic index on view_events(_id)
,D/TimaKeyStoreProvider( 5425): TimaSignature is unavailable
,D/ActivityThread( 5425): Added TimaKeyStore provider
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{3aac73a7 u0 com.sec.bcservice/.BroadcastService}
,I/PolicyManagerBroadcastReceiver( 5155): This process will be killed soon.
,I/Process ( 5155): Sending signal. PID: 5155 SIG: 9
,I/ActivityManager( 1016): Process com.sec.android.app.wluc (pid 5155)(adj 15) has died(82,1174)
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 313246(10MB) AllocSpace objects, 5(80KB) LOS objects, 25% free, 47MB/63MB, paused 4.313ms total 298.453ms
,E/MTPRx   ( 5425): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedState
D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1016): mCursor = null
,V/MTPRx   ( 5425): sealedState: false
,V/MTPRx   ( 5425): sealedUsbMassStorageState: false
,E/MTPRx   ( 5425): check value of boot_completed is1
E/MTPRx   ( 5425): check booting is completed_sys.boot_completed
,E/MTPRx   ( 5425): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 5425): Status for mount/Unmount :removed
E/MTPRx   ( 5425): SDcard is not available
,W/MTPRx   ( 5425): value of connected istrue
W/MTPRx   ( 5425): value of configured istrue
W/MTPRx   ( 5425): value of mtpEnabled istrue
W/MTPRx   ( 5425): value of ptpEnabled isfalse
,E/MTPRx   ( 5425): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 5425): mFirstTime: false
,D/        ( 5425): MTP: reading debug level property
,E/MTPJNIInterface( 5425): Getting CryptionKey from JAVA
,E/MTPRx   ( 5425): currentUserId is 0
,D/CalendarAlarmManager( 5407): sys current time:1454419032290
,D/CalendarAlarmManager( 5407): reminder amount:0
,E/MTPRx   ( 5425): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 5425): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 5425): is_Privatemode is NOT 1
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,D/SecContentProvider( 1016): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 5425): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1016): name = mtp_running_status
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/MTPRx   ( 5425): else part ... so first time!!!
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
E/MTPPlaObsrvr( 5425): inside setContext()
E/MTPPlaObsrvr( 5425):  inside createplafiles
,E/MTPPlaObsrvr( 5425): playlist count is0
,E/MTPPlaObsrvr( 5425):  inside try branch createplafiles
,E/MTPPlaObsrvr( 5425):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 5425): Inside registerContentObserver
,E/MtpAdbObserver( 5425): inside setContext()
,E/MtpAdbObserver( 5425): Inside registerContentObserver
,W/Settings( 5425): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1016): name = mtp_running_status
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MtpService( 5425): onCreate.
,V/MtpMediaDBManager( 5425): inside deleteAllDB
,D/MtpService( 1226): updating state; isCurrentUser=true, mMtpLocked=false
,D/MediaScannerReceiver( 1226): action: com.samsung.intent.action.MTP_FILE_SCAN
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.android.settings
,I/SettingSearch/SearchIntentReceiver( 1336): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 1336): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,E/MtpService( 5425): < MTP > Registering BroadCast receiver :::::
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
,I/SettingSearch/SearchIntentReceiver( 1336): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1336): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/SettingSearch/SearchIntentReceiver( 1336): InitTitleDBThread start --> mDoingInitTitleDB : true
,E/MtpService( 5425): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/MtpService( 5425): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/MtpService( 5425): onStartCommand.
,W/MTPRx   ( 5425): calling native method
E/MTPJNIInterface( 5425): < MTP > Registering BroadCast receiver :::::
,E/MTPJNIInterface( 5425): < MTP > Registering BroadCast receiver :::::::
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/MtpService( 5425): handleMessage. msg= { when=-3ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 5425): noti = 10
,E/MtpService( 5425): onStartCommand.
,W/MTPRx   ( 5425): calling native method
,E/MTPRx   ( 5425): Checking the driver time out
,E/MTPJNIInterface( 5425): noti = 2
,D/        ( 5425): deleting sockets before message queue initialization
,D/        ( 5425): event handler thread is created, so set the flag
E/MtpService( 5425): handleMessage. msg= { when=-4ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPRx   ( 5425): called native method
E/MTPJNIInterface( 5425): setting Media scanner status0
E/MTPJNIInterface( 5425): After setting Media scanner status0
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/MTPRx   ( 5425): notification from stack 1
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,V/MtpMediaDBManager( 5425): inside Thread updateDB
,E/        ( 5425): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 5425): Getting media scanner status0
,E/MTPJNIInterface( 5425): DeviceName is A5-1
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/MediaScannerService( 1226): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,E/MtpMediaDBManager( 5425): count : 27
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/MtpMediaDBManager( 5425): sending db update complete noti to stack
,E/MTPJNIInterface( 5425): noti = 29
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,E/SQLiteLog( 5425): (5) database is locked
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SettingSearch/SettingsSearchManager( 1336): Infomation -> numtitleinfo : 0 numSearchinfo : 306
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/MTPJNIInterface( 5425): Status for mount/Unmount :removed
,E/MTPJNIInterface( 5425): SDcard is not available
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter finished
,E/        ( 5425): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,E/        ( 5425): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/MTPJNIInterface( 5425): Status for mount/Unmount :removed
E/MTPJNIInterface( 5425): SDcard is not available
,E/SQLiteLog( 5425): (21) API call with NULL database connection pointer
E/SQLiteLog( 5425): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 5425): (21) API call with NULL database connection pointer
E/SQLiteLog( 5425): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5425): (21) API call with NULL database connection pointer
E/SQLiteLog( 5425): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5425): (21) API call with NULL database connection pointer
E/SQLiteLog( 5425): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 5425): notification from stack 2
,D/MediaScanner( 1226): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/        ( 5425): [mtp_init_device] Library open with 32 bits.
D/        ( 5425): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 5425): [mtp_init_device 702]  After open the MTP fd = 33 and line = 702...
,D/        ( 5425): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,E/        ( 5425):  [sua_support_present:1287] returning false 
D/        ( 5425): *****Starting mtp_io()
,D/        ( 5425): [mtp_start_io] source_thread Creation 
D/        ( 5425): [mtp_start_io] sink_thread Creation 
,W/MTPRx   ( 5425): notification from stack 3
,D/        ( 5425): [mtp_start_io:376] sink thread created so set th_sink
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,V/MediaScanner( 1226): processDirectory :  /storage/emulated/0
,I/iu.UploadsManager( 3470): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,D/MediaScanner( 1226): Skipping:
D/MediaScanner( 1226): 7klwibgf7fvntblfd7(75ebcf7
,I/SettingSearch/SettingsSearchManager( 1336):  Infomation -> getItem size : 306
,D/MediaScanner( 1226): Skipping:
D/MediaScanner( 1226): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,V/MediaScanner( 1226): processDirectory :  /storage/extSdCard
W/MediaScanner( 1226): Error opening directory, reason : Permission denied.
W/MediaScanner( 1226): 7klwibgf7fxlKdCbid7
,V/MediaScanner( 1226):  prescan time: 35ms (DB items: 27)
V/MediaScanner( 1226):     scan time: 18ms (Caching mode: true), (makeEntry time: 11ms ~61%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1226): postscan time: 3ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1226):    total time: 56ms
V/MediaScanner( 1226): checked files: 10  directories : 17  (I: 0, U: 0)
,E/MTPJNIInterface( 5425): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,D/MediaScannerService( 1226): !@done scanning volume external
,W/ResourcesManager( 1336): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 1336): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1336): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1336): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/iu.UploadsManager( 3470): End new media; added: 0, uploading: 0, time: 66 ms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 4565): Conditions not met for autocaching.
I/MusicLeanback( 4565): Stop autocaching.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/GmsUtils( 4565): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 4565): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
,E/CscFactoryReceiver( 1460): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,D/CscFactoryReceiver( 1460): Media DB Scanner finished.
D/CscFactoryReceiver( 1460): start service to Set Ringtone
,D/ActivityManager( 1016): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1460): start service to Set Notification
,D/ActivityManager( 1016): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1460): start service to Set Alarmtone
,D/ActivityManager( 1016): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscUpdateService( 1460): onStart
E/CscUpdateService( 1460): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1460): only ringtone update
,D/CscUpdateService( 1460): onStart
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
E/CscUpdateService( 1460): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1460): only notification update
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.indexservice, hostingType: broadcast
,D/CscUpdateService( 1460): onStart
E/CscUpdateService( 1460): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1460): only alarmtone update
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/CscParser( 1460): update(): xml file exist
E/CscParser( 1460): update(): xml file exist
,E/CscParser( 1460): update(): xml file exist
I/libpersona( 5470): KNOX_SDCARD checking this for 10006
E/Zygote  ( 5470): MountEmulatedStorage()
I/libpersona( 5470): KNOX_SDCARD not a persona
E/Zygote  ( 5470): v2
I/SELinux ( 5470): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5470): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5470): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/CSCSettings( 1460): Setting Ringtones (type) : 4
,D/CscParser( 1460): AlarmTone: null
W/CSCSettings( 1460): 1. Tag_Str: null
W/CSCSettings( 1460): Setting Ringtones (type) : 1
D/CscParser( 1460): RingTone: null
,W/CSCSettings( 1460): 1. Tag_Str: null
,I/ActivityManager( 1016): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5470 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
,W/CSCSettings( 1460): Setting Ringtones (type) : 2
,D/CscParser( 1460): MessageTone: null
W/CSCSettings( 1460): 1. Tag_Str: null
,D/TimaKeyStoreProvider( 5470): TimaSignature is unavailable,
,D/ActivityThread( 5470): Added TimaKeyStore provider
,I/CalendarProvider2( 5407): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/ThumbnailProvider( 5470): ThumbnailProvider onCreate()
,I/DocumentBroadcastReceiver( 5470): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 5470): [START] processBroadcastIntent ...
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 5062): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 5470): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
D/GalleryCacheReady( 5062): handleMeidaScanFinish()
,D/FaceInterface( 5062): requestFaceScan() is called.
,W/LocalSuggestAlbumData( 5062): query fail: 
,W/LocalSuggestAlbumData( 5062): query fail: 
,I/SystemInfo( 5470): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 5470): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
,I/BroadcastProcessorService( 5470): [START] DocumentService startDocumentService
D/ActivityManager( 1016): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
,I/FaceInterface( 5062): startFaceScan() : waiting 5 sec
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,I/DocumentService( 5470): DocumentService onCreate ... service
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/BluetoothMediaBrowser( 2595):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5470): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5470): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/SettingSearch/SearchIntentReceiver( 1336): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 1336): LOCALE_CHANGED call search setting db finish!!
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/BluetoothMediaBrowser( 2595): no now playing list
D/BluetoothMediaBrowser( 2595):  getNowPlayingId now playing id : -1
,I/SettingSearch/SearchIntentReceiver( 1336): InitTitleDBThread start --> mDoingInitTitleDB : true
,E/SystemInfo( 5470): [SIOP LEVEL] : 0
,I/SettingSearch/SearchIntentReceiver( 1336): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1336): LOCALE_CHANGED call search setting db finish!!
,I/DocumentService( 5470): [BEGIN SYNC] DocumentService beginIndexing :16
,I/MediaStoreImporter( 4565): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5470): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/File    ( 5470): fail readDirectory() errno=13
,E/File    ( 5470): fail readDirectory() errno=13
,I/SystemInfo( 5470): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5470): [STOP DOCUMENTSERVICE] Attempting to stop the Service
,E/DocumentService( 5470): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :31
E/DocumentService( 5470): [THUMBNAIL] Total Time taken for each file :0
E/        ( 5470): [INDEX] Total time taken for each file :0
,I/DocumentService( 5470): DocumentService onDestroy start
,I/DocumentService( 5470): DocumentService onDestroy end
,I/ActivityManager( 1016): Killing 4816:com.samsung.android.sm/1000 (adj 15): empty #31
,I/DocumentService( 5470): DocumentService cleanupEverything start
,I/SystemInfo( 5470): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5470): DocumentService cleanupEverything end
,I/Process ( 5470): Sending signal. PID: 5470 SIG: 9
,I/ActivityManager( 1016): Process com.samsung.indexservice (pid 5470)(adj 11) has died(76,1175)
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4816/cgroup.procs: No such file or directory
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1016): Plugged,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/FaceInterface( 5062): startFaceScan() : going on
I/FaceInterface( 5062): startFaceScan() : going on
D/FaceInterface( 5062): startFaceScan() is called.
,D/FaceInterface( 5062): startFaceScan() is called.
,D/ContentApp( 1226): startScan() is called.
,D/FaceValue( 1226): mSleepTime: 800
,D/FaceValue( 1226): mMaxThreadNum: 2
,W/FaceValue( 1226): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,D/ContentApp( 1226): startScan() is end.
,D/ContentApp( 1226): startScan() is called.
D/ContentApp( 1226): face_restore mRestartScanner 1 FINISHED_TYPE: 3
D/ContentApp( 1226): startScan() is end.
,D/ContentApp( 1226): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1226): isNeedToRestore : start
,I/art     ( 1226): Explicit concurrent mark sweep GC freed 7730(497KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 814us total 22.605ms
,D/ContentApp( 1226): face_restore mRestartScanner 2 FINISHED_TYPE: 3
D/FaceScanner( 1226): isNeedToRestore : start
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/PackageManager( 1016): verifying app can be installed or not
D/ApplicationPolicy( 1016): isApplicationInstallationEnabled
,D/ApplicationPolicy( 1016): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1016): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1016): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1016): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy( 1016): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1016): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1016): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1016): isApplicationInstallationEnabled :  Checking SIG BL - true
,D/ApplicationPolicy( 1016): isApplicationInstallationEnabled :  enabled true
,I/AASAInstall( 1016): ship mode
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/art     ( 1016): Background partial concurrent mark sweep GC freed 347709(21MB) AllocSpace objects, 2(1839KB) LOS objects, 24% free, 48MB/64MB, paused 7.530ms total 268.214ms
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 5207): Thread[GAThread,5,main]: No campaign data found.
,D/PackageManager( 1016): Existing package
,D/PackageManager( 1016): Renaming /data/app/vmdl630098608.tmp to /data/app/com.test.thalitest-1
,D/PackageManager( 1016): installNewPackageLI: Package{859dfae com.test.thalitest}
,I/PackageManager( 1016): scanFileNewer : com.test.thalitest
,I/art     ( 1016): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory,
I/art     ( 1016): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.test.thalitest-1/arm/base.odex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
D/PackageManager( 1016): Running dexopt on: /data/app/com.test.thalitest-1/base.apk pkg=com.test.thalitest isa=arm vmSafeMode=false interpret_only=false
,I/dex2oat ( 5501): ----------------------------------------------------,
I/dex2oat ( 5501): <SS>: S T A R T I N G . . .
I/dex2oat ( 5501): <SS>: going to process manifest for 32-bit...
,I/        ( 5501): SS_ART_lib [I]: Memory allocation: ctx,
I/        ( 5501): SS_ART_lib [I]: Memory allocation: manifest_buf
I/        ( 5501): SS_ART_lib [I]: Parsing Manifest for SS stuff
I/        ( 5501): SS_ART_lib [I]: Memory allocation: ctx->libs
I/        ( 5501): SS_ART_lib [I]: Memory allocation: ctx->package_name
,I/        ( 5501): SS_ART_lib [I]: Parsing completed
I/        ( 5501): SS_ART_lib [I]: permission is absent: /data/app/com.test.thalitest-1/base.apk
I/        ( 5501): SS_ART_lib [I]: Closing zip file: /data/app/com.test.thalitest-1/base.apk
I/        ( 5501): SS_ART_lib [I]: access to SS denied
I/        ( 5501): SS_ART_lib [I]: ctx will be cleaned
I/        ( 5501): SS_ART_lib [I]: ctx component will be cleaned: ctx->libs
,I/        ( 5501): SS_ART_lib [I]: ctx component is cleaned: ctx->libs
I/        ( 5501): SS_ART_lib [I]: ctx component will be cleaned: ctx->package_name
I/        ( 5501): SS_ART_lib [I]: ctx component is cleaned: ctx->package_name
I/        ( 5501): SS_ART_lib [I]: ctx is cleaned
I/dex2oat ( 5501): /system/bin/dex2oat --zip-fd=11 --zip-location=/data/app/com.test.thalitest-1/base.apk --oat-fd=12 --art-fd=-1 --oat-location=/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/dex2oat ( 5501): dex2oat took 374.299ms (threads: 4)
,I/PackageManager( 1016): do mInstaller.dexopt : 0
,D/PackageManager( 1016): Time to dexopt: 0.435 seconds
,W/System.err( 1016): java.io.FileNotFoundException: /data/app/com.test.thalitest-1: open failed: EISDIR (Is a directory)
,W/System.err( 1016): ,	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1016): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 1016): 	at android.content.pm.PackageParser.getHashValueOfPackage(PackageParser.java:5140)
W/System.err( 1016): ,	at com.android.server.pm.PackageManagerService.saveHash(PackageManagerService.java:19520)
W/System.err( 1016): 	at com.android.server.pm.PackageManagerService.access$5400(PackageManagerService.java:342)
W/System.err( 1016): 	at com.android.server.pm.PackageManagerService$19.run(PackageManagerService.java:19505)
W/System.err( 1016): Caused by: android.system.ErrnoException: open failed: EISDIR (Is a directory)
,W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:446)
W/System.err( 1016): 	... 5 more
,I/HarmonyEASService( 1016): Updating for all 1
,D/PackageManager( 1016): New package installed
,D/PackageManager( 1016): doPostInstall for uid{10155}
,D/PackageManager( 1016): token 1 to BM for possible restore
,V/BackupManagerService( 1016): restoreAtInstall pkg=com.test.thalitest token=1 restoreSet=0
V/BackupManagerService( 1016): Finishing install immediately
,D/PackageManager( 1016): BM finishing package install for 1
,D/PackageManager( 1016): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 1016): [MSG] MCS_UNBIND
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PageBuddyNotiSvc( 4240): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,W/ResourcesManager( 1460): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5508): MountEmulatedStorage()
E/Zygote  ( 5508): v2
I/libpersona( 5508): KNOX_SDCARD checking this for 1000
I/libpersona( 5508): KNOX_SDCARD not a persona
,I/SELinux ( 5508): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5508): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=5508 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 5508): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PackageManager( 1016): [MSG] POST_INSTALL: observer{402295286}
D/PackageManager( 1016):           Handling post-install for 1
,D/RegisteredComponentCache( 1444): Collect Tech packages for Knox
,I/ActivityManager( 1016): Killing 4847:com.qualcomm.timeservice/1000 (adj 15): empty #31
,D/PersonaManager( 1444): isKioskContainerExistOnDevice
,W/Settings( 1016): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{2f0e9cc5 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,D/TimaKeyStoreProvider( 5508): TimaSignature is unavailable
,D/ActivityThread( 5508): Added TimaKeyStore provider
,D/PersonaManager( 1444): isKioskContainerExistOnDevice,
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1790): mOCRHelper is null
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,D/RegisteredServicesCache( 1444): empty dynamic service
,D/RegisteredComponentCache( 1444): Collect Tech packages for Knox
,D/PersonaManager( 1444): isKioskContainerExistOnDevice
,D/AASAservice-UpdateReceiver( 5508): AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.google.android.gms, uid = -1
D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,I/splitIntent( 1016): intent=android.intent.action.PACKAGE_CHANGED will be not split. because same process=com.google.android.googlequicksearchbox:search is in other queue. index=1
,I/splitIntent( 1016): base  index=1, name=com.google.android.googlequicksearchbox com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher
I/splitIntent( 1016): other index=7, name=com.google.android.googlequicksearchbox com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_CHANGED !! do not split it!!
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher: pid=5526 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a,
,E/Zygote  ( 5526): MountEmulatedStorage()
E/Zygote  ( 5526): v2
I/ActivityManager( 1016): Killing 4864:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,I/libpersona( 5526): KNOX_SDCARD checking this for 10057
I/libpersona( 5526): KNOX_SDCARD not a persona
,I/SELinux ( 5526): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,D/PersonaManager( 1444): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1444): empty dynamic service
I/SELinux ( 5526): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75),
,E/SELinux ( 5526): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5526): TimaSignature is unavailable
,D/ActivityThread( 5526): Added TimaKeyStore provider
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/IntentResolver( 1016): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1016): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/BackupManagerService( 1016): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.backup.TRANSPORT_HOST
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 284311(17MB) AllocSpace objects, 11(3MB) LOS objects, 27% free, 41MB/57MB, paused 3.487ms total 342.827ms
D/PackageManager( 1016): result of install: 1{402295286}
,I/PackageManager( 1016): Observer no longer exists.
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,I/GCoreNlp( 1869): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/RCPManagerService( 1016): PackageReceiver onReceive()
D/RCPManagerService( 1016): App Installed with packageNAme = com.test.thalitest
,E/RCPManagerService( 1016):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: Attempt to invoke virtual method 'java.lang.String android.os.Bundle.getString(java.lang.String)' on a null object reference
D/RCPManagerService( 1016):  PackageReceiver onReceive() bundle null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_ADDED
,D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,W/BackupManagerService( 1016): Removing schedule queue dupe of com.test.thalitest
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_ADDED
V/EnterpriseBillingPolicy( 1016): uID is 10155
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,D/PersonaPolicyManagerService( 1016): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
,V/BackupManagerService( 1016): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 1016): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@20b54ff0
,V/AlarmManagerEXT( 1016): com.test.thalitest(10155) is added to mUserAppList
,D/KnoxMUMContainerPolicy( 1016): packageInstalledForExternalStorage com.test.thalitest
,D/EnterpriseDeviceManagerService( 1016): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1016): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1016): no available spell checker services found
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/CrashAnrDetector( 1016): onPackageAdded : com.test.thalitest
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4847/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10085/pid_4864/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1016): applying state to connected service
,D/LocationProviderProxy( 1016): applying state to connected service
,E/SMD     (  291): DCD OFF
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/LocationProviderProxy( 1016): applying state to connected service
,I/GCoreNlp( 1869): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Zygote  ( 5546): MountEmulatedStorage()
E/Zygote  ( 5546): v2
I/libpersona( 5546): KNOX_SDCARD checking this for 10015
I/libpersona( 5546): KNOX_SDCARD not a persona
,I/SELinux ( 5546): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5546): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5546 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a,
E/SELinux ( 5546): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5546): TimaSignature is unavailable
,D/ActivityThread( 5546): Added TimaKeyStore provider
,D/LocationManagerService( 1016): getProviders()=[passive]
,I/ActivityManager( 1016): Killing 4884:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5330): Creating RTCS
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5569): MountEmulatedStorage()
E/Zygote  ( 5569): v2
I/libpersona( 5569): KNOX_SDCARD checking this for 10032
I/libpersona( 5569): KNOX_SDCARD not a persona
I/SELinux ( 5569): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5569): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5569): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5569 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,W/libprocessgroup( 1016): failed to open /acct/uid_10094/pid_4884/cgroup.procs: No such file or directory
,I/Babel   ( 5330): Destroying RTCS
,I/art     (  308): Explicit concurrent mark sweep GC freed 8739(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 647us total 21.076ms
,I/ActivityManager( 1016): Killing 4923:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5569): TimaSignature is unavailable
,D/ActivityThread( 5569): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 17.560ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 605us total 16.876ms
,I/FeatureConfig( 5569): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/ActivityManager( 1016): Killing 4955:com.wsomacp/u0a25 (adj 15): empty #31
,I/PackagesMonitor( 5062): PackagesMonitor onReceive :com.google.android.gms
,W/ResourcesManager( 5569): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5569): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5569): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 5569): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 5569): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ResourcesManager( 5569): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/UpdateIcingCorporaServi( 5526): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5569): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 5587): MountEmulatedStorage()
W/ResourcesManager( 5569): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
E/Zygote  ( 5587): v2
W/ResourcesManager( 5569): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/SELinux ( 5587): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ResourcesManager( 5569): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/libpersona( 5587): KNOX_SDCARD checking this for 10069
I/libpersona( 5587): KNOX_SDCARD not a persona
I/SELinux ( 5587): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5587 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 5587): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_10072/pid_4923/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10025/pid_4955/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5587): TimaSignature is unavailable
,D/ActivityThread( 5587): Added TimaKeyStore provider
,W/ResourcesManager( 5569): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5569): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 5569): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/FileShare-Server( 5587): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5569): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/Zygote  ( 5603): MountEmulatedStorage()
I/libpersona( 5603): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5603): v2
I/libpersona( 5603): KNOX_SDCARD not a persona
,I/SELinux ( 5603): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5603): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5603): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5603 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/ResourcesManager( 5569): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5569): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5569): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5603): TimaSignature is unavailable
W/ResourcesManager( 5569): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityThread( 5603): Added TimaKeyStore provider
,W/GalaxyFinderApplication( 5569): system/finder_cp/cpdata.xml file not found
,W/ResourcesManager( 5603): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 5526): UpdateCorporaTask done [took 141 ms] updated apps [took 141 ms] 
,I/ActivityManager( 1016): Killing 4976:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5619): MountEmulatedStorage()
,I/libpersona( 5619): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5619): v2
I/libpersona( 5619): KNOX_SDCARD not a persona
I/SELinux ( 5619): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=5619 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 4994:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,I/SELinux ( 5619): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5619): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5619): TimaSignature is unavailable
,D/ActivityThread( 5619): Added TimaKeyStore provider
,D/KnoxSetupWizardDbHelper( 5619): dbMigrationFlag : false
,D/ShortcutReceiver( 5619):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5635): MountEmulatedStorage(),
E/Zygote  ( 5635): v2
I/libpersona( 5635): KNOX_SDCARD checking this for 10120
I/libpersona( 5635): KNOX_SDCARD not a persona
,I/SELinux ( 5635): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1016): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5635 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 4823:com.android.mms/u0a46 (adj 15): empty #31
,I/SELinux ( 5635): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5635): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1016): failed to open /acct/uid_10003/pid_4976/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5635): TimaSignature is unavailable
,D/ActivityThread( 5635): Added TimaKeyStore provider,
,W/ResourcesManager( 5635): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CountryDetector( 1016): No listener is left
,W/libprocessgroup( 1016): failed to open /acct/uid_10107/pid_4994/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10046/pid_4823/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5656): MountEmulatedStorage()
I/libpersona( 5656): KNOX_SDCARD checking this for 10028
E/Zygote  ( 5656): v2
I/libpersona( 5656): KNOX_SDCARD not a persona
I/SELinux ( 5656): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5656 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5656): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5656): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 5102:com.sec.smartcard.manager/u0a153 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5656): TimaSignature is unavailable
,D/ActivityThread( 5656): Added TimaKeyStore provider
,D/Finsky  ( 5656): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/libprocessgroup( 1016): failed to open /acct/uid_10153/pid_5102/cgroup.procs: No such file or directory
,D/Finsky  ( 5656): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5656): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
W/Settings( 5656): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 5656): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5656): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5656): Skipping gmscore version check
,D/Finsky  ( 5656): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5656): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 3470): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PackageBroadcastService( 3470): Null package name or gms related package.  Ignoreing.
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/HomeSyncInstallReceiver( 1444): This pkg do not need BT addr. Do nothing
,I/splitIntent( 1016): Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=14, mSplitNum[1]=23, mSplitNum[2]=36, mBgSplitQueueNum=3 divideNum= 11 r.nextReceiver= 2 receivers.size=47
I/splitIntent( 1016): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,D/AASAservice-UpdateReceiver( 5508): AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
,I/AASAservice-TokenRule( 5508): parseToken()
,W/System.err( 5508): java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
W/System.err( 5508): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 5508): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 5508): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/System.err( 5508): 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:80)
W/System.err( 5508): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:52)
W/System.err( 5508): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 5508): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 5508): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 5508): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5508): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5508): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 5508): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5508): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5508): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5508): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 5508): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 5508): 	at libcore.io.Posix.open(Native Method)
W/System.err( 5508): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 5508): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 5508): 	... 14 more
E/AASAservice-TokenRule( 5508): parseToken() : TokenFile is null
,E/AASAservice-UpdateReceiver( 5508): AASARuleUpdateResult() : Rule file is not exist.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/PackagesMonitor( 5062): PackagesMonitor onReceive :com.test.thalitest
,E/Zygote  ( 5700): MountEmulatedStorage()
,E/Zygote  ( 5700): v2
I/libpersona( 5700): KNOX_SDCARD checking this for 1000
I/libpersona( 5700): KNOX_SDCARD not a persona
,I/SELinux ( 5700): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=5700 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 5700): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/SELinux ( 5700): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5700): TimaSignature is unavailable
,D/ActivityThread( 5700): Added TimaKeyStore provider
,E/Zygote  ( 5714): MountEmulatedStorage()
,E/Zygote  ( 5714): v2
I/libpersona( 5714): KNOX_SDCARD checking this for 10152
I/libpersona( 5714): KNOX_SDCARD not a persona
,I/SELinux ( 5714): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5714 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 5714): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5714): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5724): MountEmulatedStorage(),
E/Zygote  ( 5724): v2
I/libpersona( 5724): KNOX_SDCARD checking this for 10046,
,I/SELinux ( 5724): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5724): KNOX_SDCARD not a persona,
I/ActivityManager( 1016): Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=5724 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,I/SELinux ( 5724): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5724): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/TimaKeyStoreProvider( 5714): TimaSignature is unavailable
,D/ActivityThread( 5714): Added TimaKeyStore provider
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ResourcesManager( 5700): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5724): TimaSignature is unavailable
,D/ActivityThread( 5724): Added TimaKeyStore provider
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 5714): (284) automatic index on shooting_modes(title_id),
,E/Zygote  ( 5751): MountEmulatedStorage()
E/Zygote  ( 5751): v2
I/libpersona( 5751): KNOX_SDCARD checking this for 1000
I/libpersona( 5751): KNOX_SDCARD not a persona
,I/SELinux ( 5751): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,V/AlarmManager( 1016): waitForAlarm result :4
,I/ActivityManager( 1016): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5751 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5751): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5751): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5751): TimaSignature is unavailable
W/ResourcesManager( 5724): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5724): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ActivityThread( 5751): Added TimaKeyStore provider
W/ResourcesManager( 5724): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5724): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5724): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5724): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 5767): MountEmulatedStorage()
I/libpersona( 5767): KNOX_SDCARD checking this for 10156
E/Zygote  ( 5767): v2
I/libpersona( 5767): KNOX_SDCARD not a persona
I/SELinux ( 5767): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5767): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5767): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5767 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 5123:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/ActivityManager( 1016): Killing 5139:com.samsung.android.app.powersharing/u0a122 (adj 15): empty #31
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/MmsApp( 5724): [start]    onCreate() consume time = 0.0
,I/Icing   ( 3470): Storage manager: low false usage 1.73MB avail 10.16GB capacity 11.68GB
D/TimaKeyStoreProvider( 5767): TimaSignature is unavailable
,D/ActivityThread( 5767): Added TimaKeyStore provider
,W/ContextImpl( 5171): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,I/PCWCLIENTTRACE_LOG( 5751): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 5751): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5751): new DMDBOpenHelper instance
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/TapandpayWidget:TapandpayAppWidgetProvider( 5767): onReceive(),
D/TapandpayWidget:TapandpayAppWidgetProvider( 5767): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,E/Zygote  ( 5788): MountEmulatedStorage()
I/libpersona( 5788): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5788): v2
I/libpersona( 5788): KNOX_SDCARD not a persona
I/SELinux ( 5788): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5788 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 5788): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5788): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5123/cgroup.procs: No such file or directory
,I/TapandpayWidget:Utils( 5767): Clear T&P info.
,W/libprocessgroup( 1016): failed to open /acct/uid_10122/pid_5139/cgroup.procs: No such file or directory
,I/PCWCLIENTTRACE_PushUtil( 5751): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5751): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5751): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5751): [onReceive] - android.intent.action.PACKAGE_ADDED
,D/TimaKeyStoreProvider( 5788): TimaSignature is unavailable
,D/ActivityThread( 5788): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 8746(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 697us total 24.872ms
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5767): Widget is not attached.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5788): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 657us total 18.435ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 17.211ms
,E/Zygote  ( 5805): MountEmulatedStorage()
E/Zygote  ( 5805): v2
I/libpersona( 5805): KNOX_SDCARD checking this for 1000
I/libpersona( 5805): KNOX_SDCARD not a persona
I/SELinux ( 5805): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=5805 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5805): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5805): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 5186:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5816): MountEmulatedStorage()
,I/libpersona( 5816): KNOX_SDCARD checking this for 10091
E/Zygote  ( 5816): v2,
I/libpersona( 5816): KNOX_SDCARD not a persona
I/SELinux ( 5816): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5816): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5816): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,I/ActivityManager( 1016): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5816 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1016): Killing 5241:com.sec.android.app.sns3/u0a33 (adj 15): empty #31
,D/Finsky  ( 5656): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5835): MountEmulatedStorage(),
E/Zygote  ( 5835): v2
I/libpersona( 5835): KNOX_SDCARD checking this for 10010
,I/SELinux ( 5835): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5835): KNOX_SDCARD not a persona
,I/SELinux ( 5835): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5835 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5805): TimaSignature is unavailable,
E/SELinux ( 5835): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/ActivityThread( 5805): Added TimaKeyStore provider,
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5816): TimaSignature is unavailable
D/ActivityThread( 5816): Added TimaKeyStore provider
W/art     ( 5724): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 154.507ms
,I/ActivityManager( 1016): Killing 4097:com.sec.spp.push/u0a35 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5835): TimaSignature is unavailable
,D/ActivityThread( 5835): Added TimaKeyStore provider
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/libprocessgroup( 1016): failed to open /acct/uid_10150/pid_5186/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10033/pid_5241/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1016): failed to open /acct/uid_10035/pid_4097/cgroup.procs: No such file or directory
I/FaceInterface( 5062): startFaceScan() : going on
D/FaceInterface( 5062): startFaceScan() is called.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ContentApp( 1226): startScan() is called.
,D/ContentApp( 1226): startScan() is end.
,D/ContentApp( 1226): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1226): isNeedToRestore : start
,I/CheckinService( 3470): Done disabling old GoogleServicesFramework version
,D/Mms/ArtClassLoader( 5724): init before art
,D/Mms/TelephonyPermission( 5724): start operation mode monitor
,W/ResourcesManager( 5724): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5805): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 5805): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,E/PhotosPlugin( 5816): Loading PhotosPlugin
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 206129(13MB) AllocSpace objects, 4(3MB) LOS objects, 33% free, 27MB/40MB, paused 2.708ms total 185.054ms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageBroadcastService( 3470): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 3470): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3470): Loading module APK com.google.android.play.games
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 5805): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5805): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 5805): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,D/Mms/TelephonyPermission( 5724): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 5724): isDefault true
,D/Mms/MmsApp( 5724): onCreate() com.android.mms
,I/DBG_POLICYDM( 5805): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,D/Mms/MmsApp( 5724): [start]    initCountryIso consume time = 627.400156
,D/CountryDetector( 1016): The first listener is added
,D/Mms/MmsApp( 5724): [end]    initCountryIso consume time = 9.898646
D/Mms/MmsConfig( 5724): [start]    MmsConfig.init() consume time = 0.124896
,I/DBG_POLICYDM( 5805): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 5805): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 5805): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 5805): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,D/Mms/MmsConfig( 5724): before partial update
,I/DBG_POLICYDM( 5805): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 5805): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/Mms/MmsConfig( 5724): Load Resize quality : 80
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/EasySignUpManager_1.0.1( 5724): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 5724): isAuth is false
D/Mms/MmsConfig( 5724): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,E/Zygote  ( 5870): MountEmulatedStorage(),
E/Zygote  ( 5870): v2
I/libpersona( 5870): KNOX_SDCARD checking this for 10035
,I/libpersona( 5870): KNOX_SDCARD not a persona
,I/SELinux ( 5870): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5870 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5870): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5870): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TP/MmsSmsProvider( 1460): query,matched:2117, calling pid = 5724
,D/TP/MmsSmsProvider( 1460): match 2117:Elapsed time : 0.789 ms
,D/TimaKeyStoreProvider( 5870): TimaSignature is unavailable
,D/ActivityThread( 5870): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5805): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,D/EasySignUpManager_1.0.1( 5724): isAuth is false
D/EasySignUpManager_1.0.1( 5724): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 5724): mps_code.dat does not exist
E/CscParser( 5724): customer_path =/system/csc/customer.xml
E/CscParser( 5724): fileName + /system/csc/customer.xml
,I/DBG_POLICYDM( 5805): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,E/CscParser( 5724): mps_code.dat does not exist
,E/CscParser( 5724): customer_path =/system/csc/customer.xml
E/CscParser( 5724): fileName + /system/csc/customer.xml
,I/DBG_POLICYDM( 5805): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 5805): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,D/CscParser( 5724): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 5724):  enable multiwindow = true
,I/DBG_POLICYDM( 5805): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,D/Mms/ArtClassLoader( 5724): init [DONE] art
,E/Mms/MessageUtils( 5724): setCountryDetector : update country detector info 
,E/Mms/MessageUtils( 5724): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 5724): [end]    init() consume time = 129.641302
,D/Mms/Contact( 5724): [start]    init() consume time = 0.872864
,D/Mms/Contact( 5724): [end]    init consume time = 11.047761
,D/TP/MmsSmsProvider( 1460): query,matched:13, calling pid = 5724
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,D/TP/MmsSmsProvider( 1460): match 13:Elapsed time : 2.040 ms
,D/Mms/DraftCache( 5724): [start]    rebuildCache consume time = 7.861041
,D/TP/MmsSmsProvider( 1460): query,matched:12, calling pid = 5724
,D/TP/MmsSmsProvider( 1460): match 12:Elapsed time : 3.203 ms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 5805): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,E/SPPClientService( 5870): ============PushLog. commonIsShipBuild. stop!
,D/Mms/MethodReflector( 5724): getSubId is called
D/Mms/TelephonyUtils( 5724): getLongSubId from simSlot 0, return Value = -1
,E/Zygote  ( 5892): MountEmulatedStorage()
,E/Zygote  ( 5892): v2
I/libpersona( 5892): KNOX_SDCARD checking this for 10038
I/DBG_POLICYDM( 5805): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,I/libpersona( 5892): KNOX_SDCARD not a persona
,I/DBG_POLICYDM( 5805): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
I/ActivityManager( 1016): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5892 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 5892): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Killing 5292:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31
,I/DBG_POLICYDM( 5805): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/Mms/DraftCache( 5724): [end]    rebuildCache consume time = 40.968282
E/SPPClientService( 5870): [PushClientApplication] Push log off : This is Ship build version
,D/Mms/MethodReflector( 5724): getTelephonyProperty is called
D/Mms/DownloadManager( 5724): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5724): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5724): auto download without roaming -> true
D/Mms/DownloadManager( 5724): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5724): getSubId is called
,I/SELinux ( 5892): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5892): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/SPPClientService( 5870): PushLog.txt file is not deleted.
D/SPPClientService( 5870): PushLog.txt file is not deleted.
D/SPPClientService( 5870): ============PushLog. stop!
,D/Mms/MethodReflector( 5724): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5724): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5724): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5724): getTelephonyProperty is called
D/Mms/DownloadManager( 5724): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5724): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5724): auto download without roaming -> true
D/Mms/DownloadManager( 5724): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5724): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5724): mAutoDownload ------> true
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5805): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 5805): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 5805): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 5805): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 5805): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,D/TimaKeyStoreProvider( 5892): TimaSignature is unavailable
,D/ActivityThread( 5892): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5805): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/DBG_POLICYDM( 5805): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/02/02/14:24:23
,I/DBG_POLICYDM( 5805): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/02/02/14:17:18
,I/DBG_POLICYDM( 5805): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 5805): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,W/libprocessgroup( 1016): failed to open /acct/uid_10035/pid_5292/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,W/ResourcesManager( 5892): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5892): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ComposerPerformance( 5724): 1454419038991 ms / [DONE] Composer constructor
,E/CII     ( 5724): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 5724): ReservationManager()
I/Mms/ReservationManager( 5724): resetAfterConnected()
,D/TP/MmsSmsProvider( 1460): query,matched:7, calling pid = 5724
,D/TP/MmsSmsProvider( 1460): match 7:Elapsed time : 2.431 ms
,I/DBG_POLICYDM( 5805): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,D/Mms/Conversation( 5724): [start]    init() consume time = 100.145052
,I/Mms/ReservationManager( 5724): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1460): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1460): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1460): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1460): sUpgradeVersion = 0, db.getVersion() = 81
,D/Mms/MmsApp( 5724): [end]    onCreate() consume time = 12.064166
,D/TP/MmsSmsProvider( 1460): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1460): need read changed broadcast:false
,D/Mms/Conversation( 5724): [end]    init consume time = 10.00349
,D/Mms/MessagingNotification( 5724): [start]    init() consume time = 4.615677
,D/Mms/MessagingNotification( 5724): [end]    init consume time = 2.954635
,D/TP/MmsSmsProvider( 1460): query,matched:0, calling pid = 5724
V/TP/MmsSmsProvider( 1460): getSimpleConversations entered.
,D/Mms/SpamFilter( 5724): [start]    SpamFilter fill() begin consume time = 3.46125
,D/TP/MmsSmsProvider( 1460): match 0:Elapsed time : 1.049 ms
,D/Mms/Synchronizer( 5724): [start]    doSync consume time = 1.967761
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,D/TP/MmsSmsProvider( 1460): update, matched:300, calling pid = 5724
V/TP/MmsSmsProvider( 1460): syncDBData start
,V/TP/MmsSmsProvider( 1460): syncDBData sms end
D/TP/MmsSmsProvider( 1460): query,matched:400, calling pid = 5724
V/TP/MmsSmsProvider( 1460): syncDBData mms end
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
V/TP/MmsSmsProvider( 1460): syncDBData end
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5916): MountEmulatedStorage()
,I/libpersona( 5916): KNOX_SDCARD checking this for 10072
E/Zygote  ( 5916): v2
I/libpersona( 5916): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5916 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,I/SELinux ( 5916): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/Mms/Synchronizer( 5724): [end]    doSync consume time = 25.160885
I/SELinux ( 5916): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/Mms/SpamFilter( 5724): [end]    SpamFilter fill() finished consume time = 2.12125
E/SELinux ( 5916): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/Mms/DownloadManager( 5724): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 5724): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5724): getSubId is called
D/Mms/TelephonyUtils( 5724): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 5724): getTelephonyProperty is called
D/Mms/DownloadManager( 5724): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5724): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5724): auto download without roaming -> true
D/Mms/DownloadManager( 5724): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5724): mAutoDownload ------> true
,D/TimaKeyStoreProvider( 5916): TimaSignature is unavailable
,D/ActivityThread( 5916): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,D/Mms/FreeMessageStatusReceiver( 5724): onReceive, action : android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1016): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/Mms/FreeMessageReceiverService( 5724): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5724): onHandleIntent: ACTION_PACKAGE_ADDED
,D/BadgeProvider( 5916): onCreate
,D/BadgeProvider( 5916): DatabaseHelper
,E/Zygote  ( 5932): MountEmulatedStorage(),
E/Zygote  ( 5932): v2
I/libpersona( 5932): KNOX_SDCARD checking this for 10047
I/libpersona( 5932): KNOX_SDCARD not a persona
I/SELinux ( 5932): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5932): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5932 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,E/SELinux ( 5932): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 5355:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 5312:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #32
,D/TimaKeyStoreProvider( 5932): TimaSignature is unavailable
,D/ActivityThread( 5932): Added TimaKeyStore provider
,D/SSRM:n  ( 1016): SIOP:: AP = 380
,D/Mms/MessagingNotification( 5724): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1460): query,matched:26, calling pid = 5724
,D/TP/SmsProvider( 1460): match 26:Elapsed time : 6.285 ms
,W/ResourcesManager( 5932): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5932): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5932): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5805): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsSmsProvider( 1460): query,matched:6, calling pid = 5724
,D/TP/MmsSmsProvider( 1460): match 6:Elapsed time : 1.352 ms
,I/DBG_POLICYDM( 5805): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/ChimeraCfgMgr( 3470): Loading module com.google.android.gms.games from APK com.google.android.play.games
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ChimeraModuleLdr( 3470): Module APK com.google.android.play.games already loaded
,E/Zygote  ( 5954): MountEmulatedStorage()
I/libpersona( 5954): KNOX_SDCARD checking this for 10025
E/Zygote  ( 5954): v2
I/libpersona( 5954): KNOX_SDCARD not a persona
,I/SELinux ( 5954): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5954 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,I/SELinux ( 5954): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5954): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Icing   ( 3470): updateResources: need to parse f{com.google.android.gms}
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5355/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5954): TimaSignature is unavailable
W/libprocessgroup( 1016): failed to open /acct/uid_10035/pid_5312/cgroup.procs: No such file or directory
,D/ActivityThread( 5954): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 5371:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,D/ChimeraCfgMgr( 3470): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 3470): Submit a task: k
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ResourcesManager( 5954): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Killing 5407:com.android.providers.calendar/u0a42 (adj 15): empty #31
,D/ChimeraCfgMgr( 3470): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/OMACP   ( 5954): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/ChimeraCfgMgr( 3470): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 3470): Processing package: com.test.thalitest
,D/Mms/Omacp( 5724): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/MyFiles ( 5932): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,I/OMACP   ( 5954): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,E/installd(  284): system dir 0 : /system/app/,
E/installd(  284): system dir 1 : /system/priv-app/
I/TactileAssist( 1016): enable value -1
E/installd(  284): system dir 2 : /vendor/app/
E/installd(  284): system dir 3 : /oem/app/
I/TactileAssist( 1016): internal enable value -1
,I/TactileAssist( 1016): intensity value -1
I/TactileAssist( 1016): saveAppList value true
I/TactileAssist( 1016): List of disabled apps :
I/OMACP   ( 5954): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369,
I/OMACP   ( 5954): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 5954): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 5954): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 5954): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 5954): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 5954): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 5954): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 5954): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,I/OMACP   ( 5954): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 5954): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/OMACP   ( 5954): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/GassUtils( 3470): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 3470): Found info for package com.test.thalitest in db.
,D/PackageManager( 1016): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,E/Zygote  ( 5976): MountEmulatedStorage()
,E/Zygote  ( 5976): v2
I/libpersona( 5976): KNOX_SDCARD checking this for 10053
I/libpersona( 5976): KNOX_SDCARD not a persona
,I/SELinux ( 5976): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5976 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 5976): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,E/SELinux ( 5976): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_10042/pid_5407/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10142/pid_5371/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5976): TimaSignature is unavailable
,D/ActivityThread( 5976): Added TimaKeyStore provider
,D/SensorService( 1016): [SO] 0.019 0.096 10.113
,W/ResourcesManager( 5976): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/BaseAppContext( 3470): Using Auth Proxy for data requests.
W/BaseAppContext( 3470): Using Auth Proxy for data requests.
,D/Compatibility( 5976): onReceive() it will make start service
,D/ActivityManager( 1016): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,D/Compatibility( 5976): onHandleIntent()
,D/Compatibility( 5976): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/Compatibility( 5976): found: 2
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/Compatibility( 5976): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,D/Compatibility( 5976): skipping ResolveInfo{90b398a com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 5976): considering ResolveInfo{100bbbfb com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5976): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,D/Compatibility( 5976): enabling receiver ResolveInfo{767b418 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/UpdateIcingCorporaServi( 5526): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,D/Compatibility( 5976): enabling receiver ResolveInfo{22972e71 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Compatibility( 5976): enabling receiver ResolveInfo{26eb6456 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,D/Compatibility( 5976): enabling receiver ResolveInfo{3b501cd7 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5976): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
W/BaseAppContext( 3470): Using Auth Proxy for data requests.
,I/SL_DEBUG( 5892): isLoggable:: isProductShip = 1
,W/BaseAppContext( 3470): Using Auth Proxy for data requests.
,I/SL_DEBUG( 5892): isLoggable:: SL_DEBUG_EXIST = false
,W/BaseAppContext( 3470): Using Auth Proxy for data requests.
W/BaseAppContext( 3470): Using Auth Proxy for data requests.
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/BaseAppContext( 3470): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 3470): cleanUpNonGplusAccounts done.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,E/SMD     (  291): DCD OFF,
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5892): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5892): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6007): MountEmulatedStorage()
,E/Zygote  ( 6007): v2
I/libpersona( 6007): KNOX_SDCARD checking this for 10041
,I/libpersona( 6007): KNOX_SDCARD not a persona
,I/SELinux ( 6007): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6007): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1016): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6007 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6007): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6007): TimaSignature is unavailable
,D/ActivityThread( 6007): Added TimaKeyStore provider
,W/GAV2    ( 5816): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Icing   ( 3470): Internal init done: storage state 0
,I/ActivityManager( 1016): Killing 5207:com.google.android.gm/u0a101 (adj 15): empty #31
,I/Icing   ( 3470): Post-init done
,I/Icing   ( 3470): updateResources: need to parse f{com.google.android.gms}
,I/SA      ( 6007): [SSP] onCreated
,I/SA      ( 6007): [TPM] There is no property file
,I/SA      ( 6007): [SCU] isHaveSA() - false
,I/SA      ( 6007): [TPM] getModelProperty : null
I/SA      ( 6007): [TPM] getCSCProperty : null
,I/SA      ( 6007): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6007): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6007): [DM] TFT FEATURE: false
,I/SA      ( 6007): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 6007): [DM] init START
,I/SA      ( 6007): [DM] This device is not a Vodafone
,W/ResourceType( 6007): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 6007): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 6007): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 6007): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 6007): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 6007): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 6007): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 6007): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 6007): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 6007): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/libprocessgroup( 1016): failed to open /acct/uid_10101/pid_5207/cgroup.procs: No such file or directory
,W/ResourceType( 6007): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 6007): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6007): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 6007): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 6007): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6007): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 6007): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 6007): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 6007): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 6007): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 6007): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 6007): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6007): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 6007): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 6007): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 6007): [SCU] isHaveSA() - false
I/SA      ( 6007): support phone number id : false
I/SA      ( 6007): [DM] Supports Ref Jpn : true
,I/SA      ( 6007): [DM] init END
,I/SA      ( 6007): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 6007): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
,I/ActivityManager( 1016): Killing 5046:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6036): MountEmulatedStorage(),
,I/libpersona( 6036): KNOX_SDCARD checking this for 10100
,E/Zygote  ( 6036): v2
I/libpersona( 6036): KNOX_SDCARD not a persona
I/SELinux ( 6036): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6036 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 6036): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Killing 4565:com.google.android.music:main/u0a111 (adj 15): empty #31
E/SELinux ( 6036): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,W/GAV2    ( 5816): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     (  308): Explicit concurrent mark sweep GC freed 8708(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 627us total 22.671ms
,D/TimaKeyStoreProvider( 6036): TimaSignature is unavailable
,D/ActivityThread( 6036): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 16.947ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 17.382ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageIntentReceiver( 6036): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6036): Not GearManger package! 
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6059): MountEmulatedStorage()
I/libpersona( 6059): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6059): v2
I/libpersona( 6059): KNOX_SDCARD not a persona
I/SELinux ( 6059): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6059): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6059): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6059 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 6059): TimaSignature is unavailable
,D/ActivityThread( 6059): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_10040/pid_5046/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10111/pid_4565/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 5526): UpdateCorporaTask done [took 695 ms] updated apps [took 695 ms] 
,I/ActivityManager( 1016): Killing 4904:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
,W/AccountFeatureHelper( 5816): Write apps_features disabled false
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6075): MountEmulatedStorage(),
I/libpersona( 6075): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6075): v2
I/libpersona( 6075): KNOX_SDCARD not a persona
I/SELinux ( 6075): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6075 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 5386:com.android.calendar/u0a135 (adj 15): empty #31
I/SELinux ( 6075): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6075): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6075): TimaSignature is unavailable
,D/ActivityThread( 6075): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_10134/pid_4904/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10135/pid_5386/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/AcmsPackageEventListener( 6075): Received: android.intent.action.PACKAGE_ADDED
W/ContextImpl( 6075): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/AcmsService( 6075): Enter Oncreate
,D/AcmsServiceMonitor( 6075): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsService( 6075): creating AcmsCore
,D/AcmsCore( 6075): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6075): AcmsCore
,D/AcmsCore( 6075): init
D/AcmsCore( 6075): Looper handler is not null
D/AcmsCore( 6075): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6075): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6075): Incrementing - Counter value: 1
D/AcmsCore( 6075): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 6075): onStartCommand
D/AcmsService( 6075): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6075): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6075): Incrementing - Counter value: 2
D/AcmsService( 6075): Incremented Counter Value : onStartCommand
,D/AcmsCertificateMngr( 6075): AcmsCertificateMngr
,W/GAV2    ( 5816): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/AcmsRevocationMngr( 6075): AcmsRevocationMngr
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityThread( 6075): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsService( 6075): Inside handle Intent
,D/ChimeraCfgMgr( 3470): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 3470): Module APK com.google.android.play.games already loaded
D/AcmsService( 6075): App added - package name: com.test.thalitest
D/AcmsCore( 6075): Post to AcmsCoreHandler
,D/AcmsServiceMonitor( 6075): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6075): Incrementing - Counter value: 3
D/AcmsCore( 6075): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6075): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6075): Decrementing - Counter value: 2
,I/splitIntent( 1016): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1016): Killing 5330:com.google.android.talk/u0a104 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10104/pid_5330/cgroup.procs: No such file or directory
,I/Mms/MmsApp( 5724):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5724): [start]    fillCache consume time = 1951.60901
,D/Mms/ComposeMessageFragment( 5724): fillCache, easy = false
,D/AbsListView( 5724): Get MotionRecognitionManager
,D/MotionRecognitionService( 1016):  ssp status : false
,D/Mms/ComposeMessageFragment( 5724): [end]    fillCache consume time = 70.434635
,D/Mms/BubbleViewCache( 5724): fillCache bubble = 1
,I/Icing   ( 3470): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,D/Icing   ( 3470): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 3470): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,I/Icing   ( 3470): Indexing 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD from com.google.android.googlequicksearchbox
,I/Icing   ( 3470): Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Killing 5587:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10069/pid_5587/cgroup.procs: No such file or directory
,D/AcmsKeyStoreHelper( 6075):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 6075): Key Store exist
I/AcmsKeyStoreHelper( 6075): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 6075):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 6075): getKeyStoreForApplication success 
,D/AcmsCore( 6075): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6075): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsServiceMonitor( 6075): Decrementing - Counter value: 1
D/AcmsCore( 6075): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6075): This is NOT a valid MirrorLink app
,D/AcmsCore( 6075): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6075): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsServiceMonitor( 6075): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6075): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6075): getSvcCounter - Counter value: 0
,D/AcmsService( 6075): Enter onDestroy
I/AcmsService( 6075): cleanUp(): inside service clean up
D/AcmsCore( 6075): AcmsCore: inside DeInit
D/AcmsCore( 6075): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6075): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6075): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6075): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6075): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6075): getSvcCounter - Counter value: 0
,D/AcmsService( 6075): killing acms process
I/Process ( 6075): Sending signal. PID: 6075 SIG: 9
,I/ActivityManager( 1016): Process ACMS.Process (pid 6075)(adj 0) has died(48,1207)
,I/DBG_POLICYDM( 5805): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ContextImpl( 5700): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.sm.base.a.a:307 com.samsung.android.sm.contextagent.ContextAgentReceiver.onReceive:124 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6100): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6100 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/Zygote  ( 6100): v2
I/libpersona( 6100): KNOX_SDCARD checking this for 10104
I/SELinux ( 6100): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6100): KNOX_SDCARD not a persona,
,I/SELinux ( 6100): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6100): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6100): TimaSignature is unavailable
,D/ActivityThread( 6100): Added TimaKeyStore provider
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 26947(1516KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/40MB, paused 2.501ms total 149.968ms
,I/iu.UploadsManager( 3470): End new media; added: 0, uploading: 0, time: 248 ms
,W/ResourcesManager( 6100): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel   ( 6100): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6100): MmsConfig.loadMmsSettings
,I/Babel   ( 6100): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel   ( 6100): MmsConfig.loadFromDatabase
,E/Babel   ( 6100): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6100): MmsConfig.loadFromResources
,E/Babel   ( 6100): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6100): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6100): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_StickerModule( 6100): App launched.
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  283): getCameraInfo: X
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  283): getCameraInfo: X
,W/VideoCapabilities( 6100): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6100): Unsupported mime audio/evrc
,W/AudioCapabilities( 6100): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6100): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6100): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6100): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6100): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6100): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6100): Unsupported mime audio/evrc
,W/VideoCapabilities( 6100): Unsupported mime video/wvc1
,W/VideoCapabilities( 6100): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6100): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6100): Unsupported mime video/wvc1
,W/VideoCapabilities( 6100): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6100): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6100): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6100): Unsupported mime video/mp43
,W/VideoCapabilities( 6100): Unsupported mime video/sorenson
,W/VideoCapabilities( 6100): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6100): Unsupported profile 4 for video/mp4v-es
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 6100): Creating RTCS
,I/Babel   ( 6100): Destroying RTCS
,I/ActivityManager( 1016): Killing 5619:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,W/ProcessCpuTracker( 1016): Skipping unknown process pid 5619
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5619/cgroup.procs: No such file or directory
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 5656): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1869): Explicit concurrent mark sweep GC freed 34502(2MB) AllocSpace objects, 15(240KB) LOS objects, 39% free, 12MB/21MB, paused 1.174ms total 67.229ms
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5656): Thread-972(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5656): Thread-972(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5656): Thread-972(ApacheHTTPLog):isShipBuild true
I/System.out( 5656): Thread-972(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5656): Thread-972(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10028
,I/qtaguid ( 5656): Tagging socket 44 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5656, getuid(): 10028
,I/qtaguid ( 5656): Tagging socket 48 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5656, getuid(): 10028
,I/qtaguid ( 5656): Untagging socket 44
,I/System.out( 5656): Thread-972 calls detatch()
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5656): Thread-973(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5656): Thread-973(ApacheHTTPLog):isShipBuild true
I/System.out( 5656): Thread-973(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5656): Thread-973(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5656): Untagging socket 44
,I/qtaguid ( 5656): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5656): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5656): untagSocket(44) failed with errno -22
I/System.out( 5656): Thread-973 calls detatch()
,D/Finsky  ( 5656): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6138): MountEmulatedStorage(),
E/Zygote  ( 6138): v2
,I/SELinux ( 6138): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1016): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6138 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
I/libpersona( 6138): KNOX_SDCARD checking this for 10012
I/libpersona( 6138): KNOX_SDCARD not a persona,
,I/SELinux ( 6138): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6138): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5656): Thread-972(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5656): Thread-972(ApacheHTTPLog):isShipBuild true
I/System.out( 5656): Thread-972(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5656): Thread-972(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/TimaKeyStoreProvider( 6138): TimaSignature is unavailable
,D/ActivityThread( 6138): Added TimaKeyStore provider
,W/ResourcesManager( 6138): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6138): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6138): VM with version 2.1.0 has multidex support
I/MultiDex( 6138): install
I/MultiDex( 6138): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6138): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 5656): Untagging socket 44
,I/qtaguid ( 5656): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5656): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5656): untagSocket(44) failed with errno -22
I/System.out( 5656): Thread-972 calls detatch()
,W/ActivityThread( 6138): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6138): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@11e8f1c0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6138): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
,I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6138): Reading stored module config
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1869): callingUid 10012, callindPid: 1869
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/MDM     ( 1869): [211] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6138): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{8ece269 u0 com.samsung.android.MtpApplication/.MtpService}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/LocationInitializer( 3470): Restart initialization of location
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
D/AuthorizationBluetoothService( 1869): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NativeLibraryUtils( 6138): Install completed successfully. count=14 extracted=0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1869): No location to return for getLastLocation()
,W/FusedLocationProvider( 1869): location=null
,D/CAR.SERVICE( 6138): Connecting to CarCallService...
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 6138): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6138): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6138): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6138): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6138): Creating a new PhoneAdapter instance
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6138): setListener: com.google.android.gms.car.dn@359d638f
D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6138): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6138): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 6138): Package validated; name: com.android.vending
,V/Finsky  ( 5656): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5656): Thread-973(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5656): Thread-973(ApacheHTTPLog):isShipBuild true
I/System.out( 5656): Thread-973(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5656): Thread-973(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5656): Untagging socket 44
,I/qtaguid ( 5656): Failed write_ctrl(u 44) res=-1 errno=22
,I/qtaguid ( 5656): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5656): untagSocket(44) failed with errno -22
I/System.out( 5656): Thread-973 calls detatch()
,W/ResourcesManager( 5656): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5656): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5656): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/SMD     (  291): DCD OFF
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5656): [1] DailyHygiene.access$600: Logging device features
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/DeviceConnectionService( 1869): client connected with version: 8296000
,D/Finsky  ( 5656): [994] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5656): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5656): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 5656): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5656): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5656): (HTTPLog)-Static: isShipBuild true
I/System.out( 5656): (HTTPLog)-Thread-983-551039922: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 5656): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10028
,I/System.out( 5656): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/ActivityManager( 1016): Killing 5508:com.samsung.aasaservice/1000 (adj 15): empty #31
,D/SSRM:n  ( 1016): SIOP:: AP = 350,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5508/cgroup.procs: No such file or directory
,D/PackageManager( 1016): [MSG] MCS_UNBIND
,I/ActivityManager( 1016): Killing 5062:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10044/pid_5062/cgroup.procs: No such file or directory
,D/SensorService( 1016): [SO] 0.019 0.057 10.075,
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PowerManagerService( 1016): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1016): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 1 -> 1
,D/lights  ( 1016): lcd : 1 +
,D/DisplayPowerController( 1016): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1016): lcd : 1 -
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1016): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  291): DCD OFF
,D/CAR.SERVICE( 6138): mConnectedToCar = false, abort
,E/ActivityThread( 6138): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@a59f897 that was originally bound here
E/ActivityThread( 6138): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@a59f897 that was originally bound here
E/ActivityThread( 6138): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6138): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6138): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6138): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6138): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6138): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6138): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6138): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6138): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6138): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6138): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6138): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6138): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6138): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 6138): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 6138): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 6138): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6138): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6138): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6138): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6138): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6138): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6138): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 6138): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@24b32ee that was originally bound here
E/ActivityThread( 6138): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@24b32ee that was originally bound here
E/ActivityThread( 6138): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6138): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6138): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6138): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6138): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6138): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6138): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6138): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6138): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6138): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6138): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6138): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6138): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 6138): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 6138): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 6138): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6138): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6138): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6138): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6138): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6138): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6138): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1016): Unbind failed: could not find connection for android.os.BinderProxy@2273b18d
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{3a1b240a u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/IcingInternalCorpora( 3470): getNumBytesRead when not calculated.
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,E/Watchdog( 1016): !@Sync 2
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/PowerManagerService( 1016): [s] UserActivityState : 2 -> 4,
,I/PowerManagerService( 1016): Nap time (uid 1000)...
,D/PowerManagerService( 1016): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1016): !@[ps] Screen__Off - 0 :  dream(timeout) (2),
I/PowerManagerService( 1016): Going to sleep due to screen timeout (uid 1000)...
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1016): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1016): [PWL] sb acquire: PowerManagerService.Broadcasts,
D/PowerManagerService( 1016): SecHardwareInterface.setBatteryADC : false
D/PowerManagerService( 1016): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
,D/PowerManagerService( 1016): handleSandman : startDream(true)
E/PowerManagerService( 1016): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1016): Sleeping (uid 1000)...
,D/PowerManagerService( 1016): [s] UserActivityState : 4 -> 0
,V/WindowOrientationListener( 1016): WindowOrientationListener disabled
,I/SurfaceFlinger(  258): id=12 createSurf (720x1280),-1 flag=20004, DolorFade
D/SensorService( 1016): [SO] activate (ident=0xb82939b0, enabled=0)
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/PowerManagerService( 1016): Excessive delay in ColorFade : createSurface: 10ms,
,I/Adreno-EGL( 1016): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1016): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1016): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1016): Local Branch: 
I/Adreno-EGL( 1016): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1016): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1016):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/SensorManager( 1016): unregisterListener ::   
,D/KeyguardViewMediator( 1180): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1180): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1180): changeWallpaperByScreenOff(),
D/KeyguardViewMediator( 1180): notifyScreenOffLocked
I/DBG_DM  ( 3086): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,D/KeyguardViewMediator( 1180): timeout : 5000
,D/PowerManagerService( 1016): Excessive delay in ColorFade : createEglContext: 29ms
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (156 us)
,V/ActivityThread( 3086): updateVisibility : ActivityRecord{3066092b token=android.os.BinderProxy@fe0339e {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/KeyguardViewMediator( 1180): setting alarm to turn off keyguard, seq = 1
D/KeyguardViewMediator( 1180): handleNotifyScreenOff
,D/VolumePanel( 1180): onScreenTurnedOff()
,D/VolumePanel( 1180): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/PowerManagerService( 1016): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 18ms
,D/VolumePanel( 1180): mCoverBroadcastReceiver: Screen OFF end
,D/SecKeyguardClockSingleView( 1180): onScreenTurnedOff
,E/SmartFaceService( 1016): onReceive: android.intent.action.SCREEN_ON
,W/System.err( 1016): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
,W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1016): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
,W/System.err( 1016): 	at android.os.Handler.handleCallback(Handler.java:739)
,W/System.err( 1016): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1016): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1016): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1016): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/SmartFaceService( 1016): fail to set sysfs 1
W/System.err( 1016): 	... 10 more
,D/InputMethodManagerService( 1016): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_SCREEN_ON
,I/StatusBar( 1180): Icon Only
E/MotionRecognitionService( 1016):  handler : SCREEN_ON end
,D/PanelView( 1180): There is/are notification(s) 
,D/PowerManagerService( 1016): Excessive delay in ColorFade : initGLShaders: 34ms
D/NotificationService( 1016): ACTION_SCREEN_ON
D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
,D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/PowerManagerService( 1016): Excessive delay in ColorFade prepare: 105ms
,D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/DisplayPowerController( 1016): ColorFade: onAnimationStart
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
,D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
,E/WifiNative-wlan0( 1016): do suspend false
,I/wpa_supplicant( 2127): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2127): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2127): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2127): Scan requested (ret=0) - scan timeout 30 seconds
,D/IpRemoteDisplayController( 1016): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1016): Bridge Server is not available
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1016): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler( 1016): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1444): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NfcService( 1444): call the applyRouting
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false,
D/accuweather( 1727): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
D/accuweather( 1727): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1727): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1727): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
,D/ActivityManager( 1016): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1790): getNextShiftState() cursorCapsMode : 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/LightsService( 1016): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1016) 
D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1016): turn on LED for fully charged
,D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1016): write_int failed to open -1
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:n  ( 1016): SIOP:: AP = 330
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
W/System.err( 1016): 	at android.os.Looper.loop(Looper.java:145)
E/SmartFaceService( 1016): fail to set sysfs 0
W/System.err( 1016): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1016): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1016): 	... 10 more
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
,D/SamsungIME( 1790): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 1016):  handler : SCREEN_OFF end 
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/NotificationService( 1016): ACTION_SCREEN_OFF
,D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=off
,V/voice   (  283): voice_set_parameters: enter: screen_state=off
V/voice   (  283): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
,D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
,D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1305): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1305): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1305): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1305): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1454440560000
,D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1454419057775
,I/BackgroundCompactionService( 1016): Schedule Type1 BGCompaction
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR,
D/daemonapp( 1305): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1305): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/IpRemoteDisplayController( 1016): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1016): Bridge Server is not available
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1305): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
I/BatteryStatsDumper( 1016): In refreshStats isReason Screen ON/OFF: true
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/DisplayPowerState( 1016): !@ ColorFade entry
,D/DisplayPowerController( 1016): ColorFade: onAnimationEnd
,D/lights  ( 1016): lcd : 0 +,
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
,D/lights  ( 1016): lcd : 0 -
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 0 -> 0
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
,D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService( 1016): [PWL] sb release: PowerManagerService.Display
,D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,V/EmergencyMode( 1418): [EmergencyStateReceiver] binteractive [false] why[3]
D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/PersonaManagerService( 1016): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 1016): MSG_ACTION_SCREEN_OFF called
,D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
,D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1016): Got set_interactive hint
,D/DisplayManagerService( 1016): !@display_state: ON -> OFF
,I/DisplayManagerService( 1016): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 1016): Display changed displayId=0
,D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb8b6f690
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
,D/NfcService( 1444): call the applyRouting
,I/BatteryStatsDumper( 1016): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1016): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1016): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1016): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1016): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1016): Previous Battery Level: 0 Current Level: 100 Delta: -100
,D/StatusBar.NetworkController( 1180): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/accuweather( 1727): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1727): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1727): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1727): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1727): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1727): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1727): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1922): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/SSRM:n  ( 1016): SIOP:: AP = 330
,D/PowerManagerService( 1016): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1727): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1727): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1727): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1727): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1727): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1727): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1727): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl( 1016): Excessive delay in setPowerMode(): 250ms
D/PowerManagerService( 1016): Excessive delay in !@display_state: OFF: 251ms
I/libsuspend( 1016): !@autosuspend_wakeup_count_enable
I/libsuspend( 1016): !@autosuspend_wakeup_count_enable done
,D/PowerManagerService( 1016): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 265ms
E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
,I/PowerManagerService( 1016): [PWL] Off : 0s ago
I/PowerManagerService( 1016): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 1016): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=1016, ws=null) (elapsedTime=327)
,I/BatteryStatsDumper( 1016): Writing to database completed
,E/WifiNative-wlan0( 1016): do suspend true
,D/SSRM:a  ( 1016): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1016): SettingsAirViewInfo:: 000000000
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 2127): nl80211: Received scan results (3 BSSes),
D/WifiP2pService( 1016): InactiveState{ what=147461 }
D/WifiP2pService( 1016): P2pEnabledState{ what=147461 },
D/WifiP2pService( 1016): DefaultState{ what=147461 }
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5,
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardViewMediator( 1180): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1180): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1180): *** Keyguard wallpaper service already unbounded
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,I/PowerManagerService( 1016): [PWL] Off : 5s ago
,D/Finsky  ( 5656): [985] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5656): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,D/SSRM:n  ( 1016): SIOP:: AP = 300
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8,
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 15s ago,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 290,
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :8,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 3,
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK,
V/AlarmManager( 1016): ___SyncScheduler (v3) ACTIVATED___,
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
V/AlarmManagerEXT( 1016): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1016): (AppSync) ### 0 added ###
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,I/BackgroundCompactionService( 1016): onStart. jobID=801
,I/BackgroundCompactionService( 1016): onStart done. jobID=801
,I/BackgroundCompactionService( 1016): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1016): compact_memory command done
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,I/PowerManagerService( 1016): [PWL] Off : 30s ago
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :4,
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1869): Vacuum at: now=1454419091395 tag=VacuumService
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1869): Scheduling Phenotype for one-off execution 4705 seconds from now (1454419091818)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1869): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1869): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1869): Using platform SSLCertificateSocketFactory
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 68459(3MB) AllocSpace objects, 28(1000KB) LOS objects, 33% free, 28MB/42MB, paused 2.518ms total 168.379ms
,D/LocationManagerService( 1016): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1869): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1869): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1869): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1869): (HTTPLog)-Thread-265-807512236: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1869): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1869): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1869): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1869, getuid(): 10012
,I/qtaguid ( 1869): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1869, getuid(): 10012
,D/LocationManagerService( 1016): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1869): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1869): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1869, getuid(): 10012
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/LocationManagerService( 1016): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1869): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1869): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1869, getuid(): 10012
,D/LocationManagerService( 1016): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1869): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1869): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1869, getuid(): 10012
,D/FactoryTest( 5425): Not factory mode
,D/FactoryTest( 5425): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5425): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5425): still no open session command from host, so toast
,W/ContextImpl( 5425): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5425): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
I/Timeline( 5425): Timeline: Activity_launch_request id:com.android.settings time:114933
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
,I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1016): mDVFSHelper.acquire(),
,V/ActivityManager( 1016): Display changed displayId=0
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1016): Focused application set to: xxxx
,D/InputDispatcher( 1016): Focus left window: 3086
,E/MTPRx   ( 5425): started activity for popup
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5425): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5425): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5425): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5425): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5425): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5425): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SettingsReceiverActivity( 5425): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus entered window: 3086
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1016): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@148e58dd attribute=android.view.inputmethod.EditorInfo@379d5c52, token = android.os.BinderProxy@5e7897a
,D/SamsungIME( 1790): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/SettingsReceiverActivity( 5425): dev.kiessupport is : TRUE
,D/PhoneWindow( 5425): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5425): *FMB* installDecor flags : 8388610
,I/DBG_DM  ( 3086): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 3086): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 25
,I/DBG_DM  ( 3086): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 3086): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3086): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 25
,I/DBG_DM  ( 3086): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3086): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3086): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3086): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 3086): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 25
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
,I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3086): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 3086): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3086): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3086): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3086): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,I/DBG_DM  ( 3086): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/Timeline( 3086): Timeline: Activity_idle id: android.os.BinderProxy@fe0339e time:115217
,V/ActivityThread( 3086): updateVisibility : ActivityRecord{3066092b token=android.os.BinderProxy@fe0339e {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,W/ActivityManager( 1016): mDVFSHelper.release(),
,D/TaskPersister( 1016): removeObsoleteFile: deleting file=7_task.xml,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/PowerManagerService( 1016): [PWL] Off : 50s ago
,D/SSRM:n  ( 1016): SIOP:: AP = 270,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 4
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 75s ago
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1016): waitForAlarm result :8
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged,
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 5
,I/ClearcutLoggerApiImpl( 1869): disconnect managed GoogleApiClient,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 105s ago,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 6
,E/SMD     (  291): DCD OFF,
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK,
V/AlarmManager( 1016): waitForAlarm result :4
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :8,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/Watchdog( 1016): !@Sync 7
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1016): !@Sync 8
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 180s ago,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 9,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 225s ago,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1016): initializing...
I/TLC_TIMA_PKM_initialize( 1016): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1016): process = tima_pkm, process_strlen = 8,
I/TZ: qc_tlc_communication( 1016): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1016): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1016): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1016): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1016): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1016): Trustlet response is completed
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 10
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 11
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/PowerManagerService( 1016): [PWL] Off : 275s ago,
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 12
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,V/AlarmManager( 1016): waitForAlarm result :8,
V/AlarmManager( 1016): No more alarm at this time.nowELAPSED=402034 batch.start=744560
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 13
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 330s ago
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 14
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1016): waitForAlarm result :8,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 15,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 390s ago,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/bootchecker(  326): bootchecker wake up!!,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 16,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 17,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,I/MotionRecognitionService( 1016): Plugged
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/PowerManagerService( 1016): [PWL] Off : 455s ago,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 18,
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged,
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/Atfwd_Daemon(  329): Stop the daemon....,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 19
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 525s ago,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 20
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 21
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 22,
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 600s ago
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 23,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 24
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,I/DBG_POLICYDM( 5805): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5805): [com.policydm.XDMBroadcastReceiver(382/xdmExecResumeCase)] Start resumecase for POLLINGTIME
,I/DBG_POLICYDM( 5805): [com.policydm.XDMApplication(716/xdmStopAlarm)] Alarm ID: 0
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SettingsProvider( 1016): name = SPD_REGISTERD
,I/DBG_POLICYDM( 5805): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 5805): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,W/ContextImpl( 5805): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.policydm.XDMBroadcastReceiver.sendRegisterIntent:482 com.policydm.XDMBroadcastReceiver.processEULAAgreement:471 com.policydm.XDMBroadcastReceiver.xdmExecResumeCase:391 
,I/DBG_POLICYDM( 5805): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5805): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 5805): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 5805): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/02/02/14:24:23
,I/DBG_POLICYDM( 5805): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/02/02/14:28:42
,I/DBG_POLICYDM( 5805): [com.policydm.polling.XPollingAgent(323/xpollingDefaultPollingTime)] 
,I/DBG_POLICYDM( 5805): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 5805): [com.policydm.polling.XPollingAgent(347/xpollingDefaultPollingTime)] Next Polling Time:2016/02/03/19:03:31
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5805): [com.policydm.restclient.XRCProcess(921/xspdHandler)] XEVENT_RC_GET_VERSION
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.policydm, destAppInfo.processName = com.policydm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBSpdAdp(158/xdbSetSpdState)] nRestClientMode = 6
,E/DBG_POLICYDM( 5805): [com.policydm.restclient.XRCProcess(212/RestClientProcess)] SPD SERVICE Start!!
I/EventLogService( 3470): Aggregate from 1454417922461 (log), 1454417922461 (data)
,I/DBG_POLICYDM( 5805): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,W/ContextImpl( 5805): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.policydm.restclient.XRCProcess.RestClientProcess:213 com.policydm.restclient.XRCProcess.access$100:77 com.policydm.restclient.XRCProcess$RestClientThread.run:134 
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,D/ActivityManager( 1016): startService callerProcessName:com.policydm, calleePkgName: com.policydm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.policydm/com.policydm.XDMService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.policydm, destAppInfo.processName = com.policydm
,I/DBG_POLICYDM( 5805): [com.policydm.restclient.XRCProcess(622/execute)] 
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,W/ActivityThread( 5805): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5805): [com.policydm.XDMBroadcastReceiver(368/xdmExecResumeCase)] Start resumecase for REGISTER
,E/DBG_POLICYDM( 5805): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,I/System.out( 5805): Thread-1008(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5805): Thread-1008(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5805): Thread-1008(ApacheHTTPLog):isShipBuild true
I/System.out( 5805): Thread-1008(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5805): Thread-1008(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/DBG_POLICYDM( 5805): [com.policydm.XDMBroadcastReceiver(377/xdmExecResumeCase)] REGISTER is already started.
,I/DBG_POLICYDM( 5805): [com.policydm.XDMService(60/onCreate)] 
D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 1000
,I/DBG_POLICYDM( 5805): [com.policydm.XDMService(82/onStartCommand)] 
,I/System.out( 5805): Thread-1008 calls detatch()
,I/DBG_POLICYDM( 5805): [com.policydm.restclient.XRCProcess(328/RestClientProcess)] HTTP status is 200
,I/DBG_POLICYDM( 5805): [com.policydm.polling.XPollingAgent(204/xpollingNextPollingTime)] Next Polling Time:2016/02/09/09:35:09
,I/DBG_POLICYDM( 5805): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 5805): [com.policydm.polling.XPollingAgent(165/xpollingSaveXMLData)] Next StatusReport Time:2016/02/04/15:20:33
,E/DBG_POLICYDM( 5805): [com.policydm.restclient.XRCProcess(388/RestClientProcess)] bPolicyUpdate is false
,I/DBG_POLICYDM( 5805): [com.policydm.restclient.XRCProcess(948/callRestClientFinish)] 
,E/DBG_POLICYDM( 5805): [com.policydm.XDMBroadcastReceiver(540/xdmSetCheckedIntent)] b_AlreadyReceivedIntent : false
,I/DBG_POLICYDM( 5805): [com.policydm.db.XDBSpdAdp(158/xdbSetSpdState)] nRestClientMode = 0
,I/DBG_POLICYDM( 5805): [com.policydm.ui.XUIAdapter(33/xuiAdpGetUiMode)] nDmUiMode : 0
,E/DBG_POLICYDM( 5805): [com.policydm.restclient.XRCProcess(983/callRestClientFinish)] SPD SERVICE Stop!!
,W/ContextImpl( 5805): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.policydm.restclient.XRCProcess.callRestClientFinish:984 com.policydm.restclient.XRCProcess.RestClientProcess:504 com.policydm.restclient.XRCProcess.access$100:77 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.policydm/com.policydm.XDMService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.policydm, destAppInfo.processName = com.policydm
,I/DBG_POLICYDM( 5805): [com.policydm.XDMService(43/onDestroy)] 
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1016): stay LED for fully charged
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 680s ago,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 25
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :8
,E/Watchdog( 1016): !@Sync 26,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 27
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 765s ago,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 28
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 29
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1,
,E/SMD     (  291): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1016): !@Sync 30
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 855s ago,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 1016): waitForAlarm result :4
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
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 31
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 32
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1016): Plugged
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :8,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 33
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 950s ago,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 34
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 35
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 36
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 37
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 1050s ago,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 38
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 39
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1016): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1016): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1016): Updating Usage Statistics in DB @ 1454420193682
,I/ApplicationPolicy( 1016): updateDataUsageMap
,I/NetworkDataUsageDb( 1016): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1016): ::isTableExists: Table exists 
,I/ApplicationUsage( 1016): Done Updating Usage Statistics in DB @ 1454420194006
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 40,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 1155s ago,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2595): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2595): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 41,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,TIME-OUT KILL (timeout was 1200000ms),D/SSRM:n  ( 1016): SIOP:: AP = 260
D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/AndroidRuntime( 6697): 
D/AndroidRuntime( 6697): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6697): CheckJNI is OFF
D/AndroidRuntime( 6697): readGMSProperty: start
D/AndroidRuntime( 6697): readGMSProperty: already setted!!
D/AndroidRuntime( 6697): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6697): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6697): readGMSProperty: end
D/AndroidRuntime( 6697): addProductProperty: start
E/AffinityControl( 6697): AffinityControl: registerfunction enter
D/AndroidRuntime( 6697): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1016): START PACKAGE DELETE: observer{615340668}
D/PackageManager( 1016): pkg{<packageName>}
D/PackageManager( 1016): user{0}
D/PackageManager( 1016): caller{2000}
D/PackageManager( 1016): flags{3}
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1016): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled :  enabled true
E/SMD     (  291): DCD OFF
D/PackageManager( 1016): !@killApplicatoin: 10155, uninstall pkg
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
I/art     ( 5700): Explicit concurrent mark sweep GC freed 956(57KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 640us total 38.513ms
I/art     ( 3817): Explicit concurrent mark sweep GC freed 2652(162KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 6MB/11MB, paused 703us total 22.180ms
I/art     ( 5526): Explicit concurrent mark sweep GC freed 675(38KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 742us total 33.143ms
I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1790): mOCRHelper is null
W/GeofencerStateMachine( 1869): Ignoring removeGeofence because network location is disabled.
I/art     ( 3470): Explicit concurrent mark sweep GC freed 5558(357KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 13MB/17MB, paused 1.120ms total 73.597ms
D/RegisteredComponentCache( 1444): Collect Tech packages for Knox
D/PersonaManager( 1444): isKioskContainerExistOnDevice
I/KLMS-2.5.183: ( 3563): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 02 14:37:23 GMT+01:00 2016
D/ActivityManager( 1016): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
W/SQLiteConnectionPool( 3470): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/KLMS-2.5.183: ( 3563): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1016): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1016): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6710): MountEmulatedStorage()
I/libpersona( 6710): KNOX_SDCARD checking this for 10094
E/Zygote  ( 6710): v2
I/libpersona( 6710): KNOX_SDCARD not a persona
I/SELinux ( 6710): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/KLMS-2.5.183: ( 3563): KLMSIntentService(): onCreate()
I/KLMS-2.5.183: ( 3563): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/SELinux ( 6710): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6710): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6710 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
D/TimaKeyStoreProvider( 6710): TimaSignature is unavailable
D/ActivityThread( 6710): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3563): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
D/PersonaManager( 1444): isKioskContainerExistOnDevice
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3563): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/Zygote  ( 6725): MountEmulatedStorage()
E/Zygote  ( 6725): v2
I/libpersona( 6725): KNOX_SDCARD checking this for 10044
I/libpersona( 6725): KNOX_SDCARD not a persona
I/SELinux ( 6725): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6725): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6725): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6725 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3563): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.183: ( 3563): KLMSIntentService(): listeningToPackageRemoved().START
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
I/KLMS-2.5.183: ( 3563): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/RCPManagerService( 1016): PackageReceiver onReceive()
I/HarmonyEASService( 1016): onReceive : android.intent.action.PACKAGE_REMOVED for 0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1016): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1016): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1016): DBIntegrity::getInstance - New instance created
E/Zygote  ( 6741): MountEmulatedStorage()
E/Zygote  ( 6741): v2
I/libpersona( 6741): KNOX_SDCARD checking this for 10149
I/libpersona( 6741): KNOX_SDCARD not a persona
I/SELinux ( 6741): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6741 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/OTPFW   ( 1016): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
I/SELinux ( 6741): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/OTPFW   ( 1016): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1016): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 1016): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10155
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
E/SELinux ( 6741): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6725): TimaSignature is unavailable
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
D/ActivityThread( 6725): Added TimaKeyStore provider
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10155
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
D/SSRM:aZ ( 1016): MSG_TYPE_APP_REMOVED::
V/AlarmManagerEXT( 1016): com.test.thalitest(10155) is removed.
D/RegisteredServicesCache( 1444): empty dynamic service
D/elm:15183( 6710): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 6710): ELMEngine.ELMEngine( context ).
D/elm:15183( 6710): MDMBridge.setEnterpriseBridge()
D/ActivityManager( 1016): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
E/SQLiteLog( 5700): (284) automatic index on crash_info_summary(package_name_touched)
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/TimaKeyStoreProvider( 6741): TimaSignature is unavailable
D/elm:15183( 6710): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 6741): Added TimaKeyStore provider
I/art     ( 5700): Explicit concurrent mark sweep GC freed 502(28KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 750us total 59.903ms
E/Zygote  ( 6756): MountEmulatedStorage()
E/Zygote  ( 6756): v2
I/libpersona( 6756): KNOX_SDCARD checking this for 1000
I/libpersona( 6756): KNOX_SDCARD not a persona
W/ResourcesManager( 6725): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/SELinux ( 6756): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ResourcesManager( 6725): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6725): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6725): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6725): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6725): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6725): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6725): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SELinux ( 6756): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6756): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:15183( 6710): ElmAgentService : onCreate()
I/ActivityManager( 1016): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6756 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3563): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.183: ( 3563): KLMSIntentService(): onDestroy()
I/art     ( 1016): Explicit concurrent mark sweep GC freed 38553(3MB) AllocSpace objects, 85(1360KB) LOS objects, 33% free, 28MB/42MB, paused 4.123ms total 328.208ms
D/BadgeProvider( 5916): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5916): sendNotify, [notify] : null
D/BadgeProvider( 5916): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5916): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5916): update, [UpdateCount] : 1
W/ContextImpl( 5171): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
D/elm:15183( 6710): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6710): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6710): MDMBridge.getInstance()
D/elm:15183( 6710): MDMBridge.getAllLicenseInfoFromSDK()
D/TimaKeyStoreProvider( 6756): TimaSignature is unavailable
D/ActivityThread( 6756): Added TimaKeyStore provider
D/elm:15183( 6710): MDMBridge.getAllLicenseInfoFromSDK()
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/elm:15183( 6710): ElmAgentService : onDestroy().
D/RCPManager( 5603):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1016):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1016): queryAllProviders():  providerCallBack is not register for 0
D/ThemeInfoUtil( 6741): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 6741): isCurrentFestival = false
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
D/AASAservice-UpdateReceiver( 6756): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/System.err( 6756): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6756): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6756): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6756): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6756): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6756): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6756): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6756): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6756): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6756): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6756): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6756): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6756): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
I/TapandpayWidget:TapandpayAppWidgetProvider( 5767): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 5767): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils( 5767): Clear T&P info.
D/PackageManager( 1016): delete codoeFile: 
D/AASAuninstall( 1016): userId = 0, info.removedAppID = -1, info.uid = 10155, packageName = com.test.thalitest
I/AASA_removePackage( 1016): UID=10155 Target=com.test.thalitest
D/TapandpayWidget:TapandpayAppWidgetProvider( 5767): Widget is not attached.
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
D/PackageManager( 1016): result of delete: 1{615340668}
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/PCWCLIENTTRACE_PushUtil( 5751): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5751): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5751): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5751): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/AndroidRuntime( 6697): Shutting down VM
E/Zygote  ( 6777): MountEmulatedStorage()
E/Zygote  ( 6777): v2
I/libpersona( 6777): KNOX_SDCARD checking this for 1000
I/libpersona( 6777): KNOX_SDCARD not a persona
I/SELinux ( 6777): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6777 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6777): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6777): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6788): MountEmulatedStorage()
E/Zygote  ( 6788): v2
I/libpersona( 6788): KNOX_SDCARD checking this for 10160
I/libpersona( 6788): KNOX_SDCARD not a persona
I/SELinux ( 6788): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6788): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6788 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
E/SELinux ( 6788): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 5546:com.google.android.partnersetup/u0a15 (adj 15): empty #31
I/ActivityManager( 1016): Killing 5788:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
D/TimaKeyStoreProvider( 6777): TimaSignature is unavailable
D/ActivityThread( 6777): Added TimaKeyStore provider
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6788): TimaSignature is unavailable
D/ActivityThread( 6788): Added TimaKeyStore provider
W/ResourcesManager( 5569): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/Zygote  ( 6807): MountEmulatedStorage()
E/Zygote  ( 6807): v2
I/libpersona( 6807): KNOX_SDCARD checking this for 10035
I/libpersona( 6807): KNOX_SDCARD not a persona
I/SELinux ( 6807): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6807 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 5835:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
W/ResourcesManager( 5569): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/SELinux ( 6807): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6807): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 5569): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/art     (  308): Explicit concurrent mark sweep GC freed 8752(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 26.294ms
D/TimaKeyStoreProvider( 6807): TimaSignature is unavailable
D/ActivityThread( 6807): Added TimaKeyStore provider
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 17.269ms
W/ResourcesManager( 6788): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 21.629ms
W/ResourcesManager( 5569): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ContextImpl( 6777): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1016): startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
D/NearbySource( 6725): Nearby Source Create!
W/ResourcesManager( 5569): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/NearbyContext( 6725): Nearby Context Create!
W/ResourcesManager( 5569): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/[0]UMC:UMCContentProvider( 6788): @onCreate
E/Zygote  ( 6823): MountEmulatedStorage()
E/Zygote  ( 6823): v2
I/libpersona( 6823): KNOX_SDCARD checking this for 1000
I/SELinux ( 6823): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6823): KNOX_SDCARD not a persona
W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/ActivityManager( 1016): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6823 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/[0]UMC:Core( 6788): onCreate(): 
D/[0]UMC:Core( 6788): @isManagedProfileUser
D/[0]UMC:Core( 6788): userId: 0
I/SELinux ( 6823): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6823): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/art     ( 6697): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/[0]UMC:Core( 6788): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 6788): userInfo.isManagedProfile() : false
W/ResourcesManager( 5569): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/ActivityManager( 1016): Killing 5724:com.android.mms/u0a46 (adj 15): empty #31
D/TimaKeyStoreProvider( 6823): TimaSignature is unavailable
D/ActivityThread( 6823): Added TimaKeyStore provider
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6725): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 6725): Samsung link source created
W/ResourcesManager( 5569): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/SPPClientService( 6807): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6807): [PushClientApplication] Push log off : This is Ship build version
D/[0]UMC:DeviceInfo( 6788): USA==US==
I/SA      ( 6007): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 6007): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10155 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager( 1016): Killing 5932:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
D/SPPClientService( 6807): PushLog.txt file is not deleted.
D/SPPClientService( 6807): PushLog.txt file is not deleted.
D/SPPClientService( 6807): ============PushLog. stop!
D/ActivityManager( 1016): startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ResourcesManager( 5569): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
D/AcmsPackageEventListener( 6823): Received: android.intent.action.PACKAGE_REMOVED
D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ResourcesManager( 5569): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ResourcesManager( 5569): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
E/SQLiteLog( 6725): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
W/ContextImpl( 6823): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
E/SQLiteDatabase( 6725): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase( 6725): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6725): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6725): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6725): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase( 6725): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase( 6725): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase( 6725): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
E/SQLiteDatabase( 6725): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
E/SQLiteDatabase( 6725): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 6725): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteDatabase( 6725): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6725): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6725): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6725): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6725): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6725): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6725): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6725): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6725): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 6725): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper( 6725): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6725): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6725): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6725): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper( 6725): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper( 6725): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper( 6725): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
E/SQLiteOpenHelper( 6725): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
E/SQLiteOpenHelper( 6725): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 6725): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteOpenHelper( 6725): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 6725): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 6725): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6725): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6725): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6725): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6725): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6725): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6725): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0

```
