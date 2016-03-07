#### Test 61362366345141a_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
I/DocumentService( 4399): [BEGIN SYNC] DocumentService beginIndexing :16
D/TimaKeyStoreProvider( 4436): TimaSignature is unavailable
D/ActivityThread( 4436): Added TimaKeyStore provider
W/ContextImpl( 4399): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
--------- beginning of system
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ResourcesManager( 4436): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
E/File    ( 4399): fail readDirectory() errno=13
E/File    ( 4399): fail readDirectory() errno=13
I/SystemInfo( 4399): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 4399): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 4399): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :41
E/DocumentService( 4399): [THUMBNAIL] Total Time taken for each file :0
E/        ( 4399): [INDEX] Total time taken for each file :0
I/DocumentService( 4399): DocumentService onDestroy start
I/DocumentService( 4399): DocumentService onDestroy end
I/DocumentService( 4399): DocumentService cleanupEverything start
I/ActivityManager( 1013): Killing 3603:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
I/IndexParserThreadsManager( 4399): InterruptedException: null
I/SystemInfo( 4399): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 4399): DocumentService cleanupEverything end
I/Process ( 4399): Sending signal. PID: 4399 SIG: 9
E/SmartCardContentProvider( 4436): onCreate
I/ActivityManager( 1013): Process com.samsung.indexservice (pid 4399)(adj 9) has died(90,1164)
I/SmartCardBroadcastReceiver( 4436): SmartCardBroadcastReceiver - onReceive() 
I/SmartCardBroadcastReceiver( 4436): Broadcast received for locktype changed 
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/AssistantMenuSettingSearch( 3722): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
D/AssistantMenuSettingSearch( 3722): Make Setting DB
D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.sec.providers.settingsearch
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4461): MountEmulatedStorage()
E/Zygote  ( 4461): v2
I/libpersona( 4461): KNOX_SDCARD checking this for 10150
I/libpersona( 4461): KNOX_SDCARD not a persona
I/SELinux ( 4461): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4461): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=4461 uid=10150 gids={50150, 9997} abi=armeabi-v7a
E/SELinux ( 4461): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/art     (  308): Explicit concurrent mark sweep GC freed 8705(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 22.345ms
D/TimaKeyStoreProvider( 4461): TimaSignature is unavailable
D/ActivityThread( 4461): Added TimaKeyStore provider
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3603/cgroup.procs: No such file or directory
I/MediaStoreImporter( 4269): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 17.233ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 18.536ms
I/ActivityManager( 1013): Waited long enough for: ServiceRecord{f215530 u0 com.android.settings/.wifi.WifiCredService}
W/ContextImpl( 3722): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:158 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:38 
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.phone
I/ActivityManager( 1013): Killing 3639:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
I/ActivityManager( 1013): Killing 3618:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #32
I/SettingSearchManagerReceiver( 1445): onReceive : com.samsung.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
I/SettingSearchManagerReceiver( 1445): addSearchInfoDB
W/libprocessgroup( 1013): failed to open /acct/uid_10069/pid_3639/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10100/pid_3618/cgroup.procs: No such file or directory
I/SettingSearchManagerReceiver( 1445): endInsert
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.wluc, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4477): MountEmulatedStorage()
E/Zygote  ( 4477): v2
I/ActivityManager( 1013): Start proc com.sec.android.app.wluc for broadcast com.sec.android.app.wluc/.PolicyManagerBroadcastReceiver: pid=4477 uid=10165 gids={50165, 9997} abi=armeabi-v7a
I/libpersona( 4477): KNOX_SDCARD checking this for 10165
I/libpersona( 4477): KNOX_SDCARD not a persona
I/SELinux ( 4477): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/art     ( 1013): Background sticky concurrent mark sweep GC freed 169391(6MB) AllocSpace objects, 2(32KB) LOS objects, 11% free, 49MB/55MB, paused 3.059ms total 141.260ms
I/SELinux ( 4477): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4477): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 4477): TimaSignature is unavailable
D/ActivityThread( 4477): Added TimaKeyStore provider
I/PolicyManagerBroadcastReceiver( 4477): onReceive: action = com.sec.intent.ACTION.SSRM_HGL_UPDATE
I/PolicyManagerBroadcastReceiver( 4477): onReceive: width = 720, height = 1280
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.app.popupuireceiver
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1013): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=4492 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 4492): MountEmulatedStorage()
E/Zygote  ( 4492): v2
I/libpersona( 4492): KNOX_SDCARD checking this for 1000
I/libpersona( 4492): KNOX_SDCARD not a persona
I/SELinux ( 4492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Killing 3681:com.sec.android.soagent/u0a34 (adj 15): empty #31
E/SELinux ( 4492): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 4492): TimaSignature is unavailable
D/ActivityThread( 4492): Added TimaKeyStore provider
D/PopupuiReceiver( 4492): onReceive() getAction : com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED
D/SecContentProvider2( 1013): uri = -1 selection = getSealedState
D/SecContentProvider2( 1013): mCursor = null
I/PopupuiReceiver_KNOX( 4492): getSealedState : true
D/SecContentProvider2( 1013): uri = 15 selection = getSealedHideNotificationMessages
D/SecContentProvider2( 1013): mCursor = null
I/PopupuiReceiver_KNOX( 4492): getSealedHideNotificationMessages : 1
D/SecContentProvider2( 1013): uri = 15 selection = getCheckCoverPopupState
D/SecContentProvider2( 1013): mCursor = null
I/PopupuiReceiver_KNOX( 4492): getCheckCoverPopupState : true
D/PopupuiReceiver( 4492): Action cable connected ! on - 
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.samsung.android.app.powersharing
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.powersharing, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4507): MountEmulatedStorage()
I/ActivityManager( 1013): Start proc com.samsung.android.app.powersharing for broadcast com.samsung.android.app.powersharing/.service.BatteryReceiver: pid=4507 uid=10122 gids={50122, 9997} abi=armeabi-v7a
E/Zygote  ( 4507): v2
I/libpersona( 4507): KNOX_SDCARD checking this for 10122
I/SELinux ( 4507): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4507): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Killing 2975:com.policydm/1000 (adj 15): empty #31
I/SELinux ( 4507): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4507): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 4507): TimaSignature is unavailable
D/ActivityThread( 4507): Added TimaKeyStore provider
I/PowerSharing.BatteryReceiver( 4507): onReceive : com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1013): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=4522 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 3706:com.sec.spp.push/u0a35 (adj 15): empty #31
E/Zygote  ( 4522): MountEmulatedStorage()
E/Zygote  ( 4522): v2
I/libpersona( 4522): KNOX_SDCARD checking this for 10033
I/libpersona( 4522): KNOX_SDCARD not a persona
I/SELinux ( 4522): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4522): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4522): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1013): failed to open /acct/uid_10034/pid_3681/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 4522): TimaSignature is unavailable
D/ActivityThread( 4522): Added TimaKeyStore provider
W/ResourcesManager( 4522): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2975/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10035/pid_3706/cgroup.procs: No such file or directory
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4553): MountEmulatedStorage()
E/Zygote  ( 4553): v2
I/libpersona( 4553): KNOX_SDCARD checking this for 10035
I/SELinux ( 4553): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4553): KNOX_SDCARD not a persona
I/SELinux ( 4553): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.ForceUpdateAlarmReceiver: pid=4553 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4553): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Killing 3513:com.android.vending/u0a28 (adj 15): empty #31
D/TimaKeyStoreProvider( 4553): TimaSignature is unavailable
D/ActivityThread( 4553): Added TimaKeyStore provider
D/AndroidRuntime( 4537): 
D/AndroidRuntime( 4537): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4537): CheckJNI is OFF
D/AndroidRuntime( 4537): readGMSProperty: start
D/AndroidRuntime( 4537): readGMSProperty: already setted!!
D/AndroidRuntime( 4537): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4537): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4537): readGMSProperty: end
D/AndroidRuntime( 4537): addProductProperty: start
E/SPPClientService( 4553): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 4553): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 4553): PushLog.txt file is not deleted.
D/SPPClientService( 4553): PushLog.txt file is not deleted.
D/SPPClientService( 4553): ============PushLog. stop!
E/SPPClientService( 4553): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4570): MountEmulatedStorage()
E/Zygote  ( 4570): v2
I/libpersona( 4570): KNOX_SDCARD checking this for 10035
I/libpersona( 4570): KNOX_SDCARD not a persona
I/SELinux ( 4570): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4570): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4570): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=4570 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 3658:com.google.android.gm/u0a101 (adj 15): empty #31
D/TimaKeyStoreProvider( 4570): TimaSignature is unavailable
D/ActivityThread( 4570): Added TimaKeyStore provider
E/SPPClientService( 4570): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 4570): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 4570): PushLog.txt file is not deleted.
D/SPPClientService( 4570): PushLog.txt file is not deleted.
D/SPPClientService( 4570): ============PushLog. stop!
W/libprocessgroup( 1013): failed to open /acct/uid_10028/pid_3513/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10101/pid_3658/cgroup.procs: No such file or directory
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/AffinityControl( 4537): AffinityControl: registerfunction enter
E/Zygote  ( 4597): MountEmulatedStorage()
I/libpersona( 4597): KNOX_SDCARD checking this for 10035
E/Zygote  ( 4597): v2
I/libpersona( 4597): KNOX_SDCARD not a persona
I/SELinux ( 4597): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=4597 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 3762:com.osp.app.signin/u0a41 (adj 15): empty #31
I/SELinux ( 4597): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4597): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 4537): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1013): inState():  stateMachine is null !!
I/PersonaManagerService( 1013): PersonaId don't exist
I/ActivityManager( 1013): do not start freezing screen for locked container getKeyguardshowstate = false
D/AndroidRuntime( 4537): Shutting down VM
D/TimaKeyStoreProvider( 4597): TimaSignature is unavailable
D/ActivityThread( 4597): Added TimaKeyStore provider
E/SPPClientService( 4597): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 4597): [PushClientApplication] Push log off : This is Ship build version
E/LNoti   ( 4597): [PhoneStatusChangeReceiver] This device doesn't register yet.
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1013): Killing 3745:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/SPPClientService( 4597): PushLog.txt file is not deleted.
E/Zygote  ( 4617): MountEmulatedStorage()
E/Zygote  ( 4617): v2
I/libpersona( 4617): KNOX_SDCARD checking this for 10101
I/libpersona( 4617): KNOX_SDCARD not a persona
D/SPPClientService( 4597): PushLog.txt file is not deleted.
D/SPPClientService( 4597): ============PushLog. stop!
I/SELinux ( 4617): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4617): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4617): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=4617 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup( 1013): failed to open /acct/uid_10041/pid_3762/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 4617): TimaSignature is unavailable
D/ActivityThread( 4617): Added TimaKeyStore provider
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3745/cgroup.procs: No such file or directory
W/art     ( 4537): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4617): getAccountsCursor
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 4617): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4617): Observing account changes for notifications
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
E/Gmail   ( 4617): Error finding the version of the Email provider.....
E/Gmail   ( 4617): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4617): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 4617): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 4617): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 4617): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4617): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4617): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 4617): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4617): We do not support migrating this version of the Email provider.
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/Gmail   ( 4617): getAccountsCursor
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
E/Watchdog( 1013): !@Sync 1
D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1013): Killing 3920:com.samsung.helphub/1000 (adj 15): empty #31
,D/SettingsProvider( 1013): name = audio_safe_volume_state,
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1837): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.download.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3920/cgroup.procs: No such file or directory
,E/SQLiteLog( 4617): (283) recovered 111 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SafeBrowsingUpdateIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/GCoreFlp( 1837): No location to return for getLastLocation()
W/FusedLocationProvider( 1837): location=null
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4659): MountEmulatedStorage(),
,E/Zygote  ( 4659): v2
,I/libpersona( 4659): KNOX_SDCARD checking this for 1000
,I/libpersona( 4659): KNOX_SDCARD not a persona
,I/SELinux ( 4659): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1013): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=4659 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4659): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4659): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/Mms/MmsApp( 4367):  start initViewCache mms
D/Mms/ComposeMessageFragment( 4367): [start]    fillCache consume time = 1953.930364
D/Mms/ComposeMessageFragment( 4367): fillCache, easy = false
,D/TimaKeyStoreProvider( 4659): TimaSignature is unavailable
,D/ActivityThread( 4659): Added TimaKeyStore provider
,E/File    ( 4617): fail readDirectory() errno=2
,I/Gmail   ( 4617): notifyAccountChanged
,W/ResourcesManager( 4659): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/Gmail   ( 4617): getAccountsCursor
,I/Gmail   ( 4617): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4617): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4617): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4617): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AbsListView( 4367): Get MotionRecognitionManager
,D/MotionRecognitionService( 1013):  ssp status : false
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,I/ActivityManager( 1013): Killing 3936:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,D/Mms/ComposeMessageFragment( 4367): [end]    fillCache consume time = 133.532135
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3936/cgroup.procs: No such file or directory
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 4617): getAccountsCursor
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/Mms/BubbleViewCache( 4367): fillCache bubble = 1
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4677): MountEmulatedStorage()
,I/libpersona( 4677): KNOX_SDCARD checking this for 10134
E/Zygote  ( 4677): v2
I/libpersona( 4677): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=4677 uid=10134 gids={50134, 9997} abi=armeabi-v7a
,I/SELinux ( 4677): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4677): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4677): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4677): TimaSignature is unavailable
,D/ActivityThread( 4677): Added TimaKeyStore provider
,W/ResourcesManager( 4677): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4677): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1013): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1013): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4695): MountEmulatedStorage(),
E/Zygote  ( 4695): v2
I/libpersona( 4695): KNOX_SDCARD checking this for 1000,
I/SELinux ( 4695): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4695): KNOX_SDCARD not a persona,
,I/SELinux ( 4695): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=4695 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 4695): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1013): Killing 3959:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4695): TimaSignature is unavailable
,D/ActivityThread( 4695): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 8707(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 675us total 29.736ms,
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 17.056ms
,I/DIAGMON_AGENT( 4695): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 16.893ms
,I/art     ( 1013): Background sticky concurrent mark sweep GC freed 155381(5MB) AllocSpace objects, 0(0B) LOS objects, 9% free, 50MB/55MB, paused 3.301ms total 117.512ms
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3959/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 4695): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 4695): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
I/DIAGMON_AGENT( 4695): [com.diagmondm.XDMBroadcastReceiver(33/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
I/ActivityManager( 1013): Killing 3979:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,I/DBG_DM  ( 2924): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,W/ContextImpl( 4659): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.sm.base.a.a:307 com.samsung.android.sm.contextagent.ContextAgentReceiver.onReceive:124 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,I/Babel   ( 3817): Creating RTCS
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4713): MountEmulatedStorage(),
E/Zygote  ( 4713): v2
I/libpersona( 4713): KNOX_SDCARD checking this for 1000
I/libpersona( 4713): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4713 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 4713): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4713): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4713): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4713): TimaSignature is unavailable
,D/ActivityThread( 4713): Added TimaKeyStore provider
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/MTPRx   ( 4713): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1013): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1013): mCursor = null
,V/MTPRx   ( 4713): sealedState: false
V/MTPRx   ( 4713): sealedUsbMassStorageState: false
E/MTPRx   ( 4713): check value of boot_completed is1
E/MTPRx   ( 4713): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4713): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4713): Status for mount/Unmount :removed
E/MTPRx   ( 4713): SDcard is not available
I/Babel   ( 3817): Destroying RTCS
,W/MTPRx   ( 4713): value of connected istrue
W/MTPRx   ( 4713): value of configured istrue
W/MTPRx   ( 4713): value of mtpEnabled istrue
W/MTPRx   ( 4713): value of ptpEnabled isfalse
,E/MTPRx   ( 4713): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 4713): mFirstTime: false
,D/        ( 4713): MTP: reading debug level property
,E/MTPJNIInterface( 4713): Getting CryptionKey from JAVA
,E/MTPRx   ( 4713): currentUserId is 0,
,E/MTPRx   ( 4713): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 4713): cannot open file : /sys/class/android_usb/android0/bcdUSB,
,E/MTPRx   ( 4713): is_Privatemode is NOT 1
,D/SettingsProvider( 1013): name = mtp_usb_conditions_met
,D/SecContentProvider( 1013): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 4713): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1013): name = mtp_running_status
,W/libprocessgroup( 1013): failed to open /acct/uid_10107/pid_3979/cgroup.procs: No such file or directory
,D/SettingsProvider( 1013): name = mtp_usb_conditions_met
,E/MTPRx   ( 4713): else part ... so first time!!!
,E/MTPPlaObsrvr( 4713): inside setContext()
,E/MTPPlaObsrvr( 4713):  inside createplafiles
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 4713): playlist count is0
,E/MTPPlaObsrvr( 4713):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4713):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4713): Inside registerContentObserver
,E/MtpAdbObserver( 4713): inside setContext()
,E/MtpAdbObserver( 4713): Inside registerContentObserver
,W/Settings( 4713): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1013): name = mtp_running_status
,D/SettingsProvider( 1013): name = mtp_usb_conditions_met
,V/MtpMediaDBManager( 4713): inside deleteAllDB
,D/ActivityManager( 1013): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
E/MtpService( 4713): onCreate.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MtpService( 4713): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 4713): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 4713): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,D/MtpService( 1230): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpService( 4713): onStartCommand.
,W/MTPRx   ( 4713): calling native method
,E/MTPJNIInterface( 4713): < MTP > Registering BroadCast receiver :::::
,E/MTPJNIInterface( 4713): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 4713): noti = 10
,E/MtpService( 4713): onStartCommand.
,W/MTPRx   ( 4713): calling native method
E/MTPRx   ( 4713): Checking the driver time out
E/MTPJNIInterface( 4713): noti = 2
D/        ( 4713): deleting sockets before message queue initialization
,D/MediaScannerReceiver( 1230): action: com.samsung.intent.action.MTP_FILE_SCAN
,D/ActivityManager( 1013): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,D/        ( 4713): event handler thread is created, so set the flag
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media,
,D/ActivityManager( 1013): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/MtpService( 4713): handleMessage. msg= { when=-7ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
V/MtpMediaDBManager( 4713): inside Thread updateDB
,E/MTPRx   ( 4713): called native method
,E/MTPJNIInterface( 4713): setting Media scanner status0
E/MTPJNIInterface( 4713): After setting Media scanner status0
W/MTPRx   ( 4713): notification from stack 1
E/MtpService( 4713): handleMessage. msg= { when=-26ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
E/        ( 4713): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4713): Getting media scanner status0
E/MTPJNIInterface( 4713): DeviceName is A5-1
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.android.settings
,E/MtpMediaDBManager( 4713): count : 27
,I/SettingSearch/SearchIntentReceiver( 1293): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1293): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
,E/SQLiteLog( 3841): (284) automatic index on view_events(_id)
,I/SettingSearch/SearchIntentReceiver( 1293): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 1293): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1293): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm,
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/MtpMediaDBManager( 4713): sending db update complete noti to stack
E/MTPJNIInterface( 4713): noti = 29
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/SQLiteLog( 4713): (5) database is locked
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/MTPJNIInterface( 4713): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4713): SDcard is not available
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 4713): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,E/        ( 4713): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,D/CalendarAlarmManager( 3841): sys current time:1457361448046
,E/MTPJNIInterface( 4713): Status for mount/Unmount :removed
E/MTPJNIInterface( 4713): SDcard is not available
E/SQLiteLog( 4713): (21) API call with NULL database connection pointer
E/SQLiteLog( 4713): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4713): (21) API call with NULL database connection pointer
E/SQLiteLog( 4713): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4713): (21) API call with NULL database connection pointer
E/SQLiteLog( 4713): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4713): (21) API call with NULL database connection pointer
E/SQLiteLog( 4713): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 4713): notification from stack 2
,D/        ( 4713): [mtp_init_device] Library open with 32 bits.
D/        ( 4713): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 4713): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
,D/        ( 4713): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 4713):  [sua_support_present:1287] returning false 
D/        ( 4713): *****Starting mtp_io()
D/CalendarAlarmManager( 3841): reminder amount:0
,D/MediaScannerService( 1230): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,W/MTPRx   ( 4713): notification from stack 3
D/        ( 4713): [mtp_start_io] source_thread Creation 
D/        ( 4713): [mtp_start_io] sink_thread Creation 
D/        ( 4713): [mtp_start_io:376] sink thread created so set th_sink
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/MediaProvider( 1230): savePlaylistTableInBulkDeleter finished
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SettingSearch/SettingsSearchManager( 1293): Infomation -> numtitleinfo : 0 numSearchinfo : 306
,D/MediaScanner( 1230): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,V/MediaScanner( 1230): processDirectory :  /storage/emulated/0
,D/MediaScanner( 1230): Skipping:
,D/MediaScanner( 1230): 7klwibgf7fvntblfd7(75ebcf7
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/MediaScanner( 1230): Skipping:
D/MediaScanner( 1230): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,V/MediaScanner( 1230): processDirectory :  /storage/extSdCard
W/MediaScanner( 1230): Error opening directory, reason : Permission denied.
W/MediaScanner( 1230): 7klwibgf7fxlKdCbid7
,V/MediaScanner( 1230):  prescan time: 24ms (DB items: 27)
V/MediaScanner( 1230):     scan time: 27ms (Caching mode: true), (makeEntry time: 19ms ~70%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1230): postscan time: 3ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1230):    total time: 54ms
V/MediaScanner( 1230): checked files: 10  directories : 17  (I: 0, U: 0)
,E/MTPJNIInterface( 4713): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,D/MediaScannerService( 1230): !@done scanning volume external
,I/SettingSearch/SettingsSearchManager( 1293):  Infomation -> getItem size : 306
,I/iu.UploadsManager( 2001): End new media; added: 0, uploading: 0, time: 61 ms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 1293): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 1293): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1293): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1293): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
,E/CscFactoryReceiver( 1445): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1445): Media DB Scanner finished.
D/CscFactoryReceiver( 1445): start service to Set Ringtone
,D/ActivityManager( 1013): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/CscFactoryReceiver( 1445): start service to Set Notification
,D/ActivityManager( 1013): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1445): start service to Set Alarmtone
,D/ActivityManager( 1013): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscUpdateService( 1445): onStart
E/CscUpdateService( 1445): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1445): only ringtone update
D/CscUpdateService( 1445): onStart
,E/CscUpdateService( 1445): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1445): only notification update
D/CscUpdateService( 1445): onStart
E/CscUpdateService( 1445): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1445): only alarmtone update
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.indexservice, hostingType: broadcast
,E/CscParser( 1445): update(): xml file exist
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/CscParser( 1445): update(): xml file exist
,E/Zygote  ( 4752): MountEmulatedStorage()
,E/Zygote  ( 4752): v2
,I/libpersona( 4752): KNOX_SDCARD checking this for 10006
I/libpersona( 4752): KNOX_SDCARD not a persona
W/CSCSettings( 1445): Setting Ringtones (type) : 1
D/CscParser( 1445): RingTone: null
,W/CSCSettings( 1445): 1. Tag_Str: null
,E/CscParser( 1445): update(): xml file exist
,I/SELinux ( 4752): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/CSCSettings( 1445): Setting Ringtones (type) : 4,
,D/CscParser( 1445): AlarmTone: null
I/ActivityManager( 1013): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=4752 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
W/CSCSettings( 1445): 1. Tag_Str: null
,I/SELinux ( 4752): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4752): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/CSCSettings( 1445): Setting Ringtones (type) : 2
,D/CscParser( 1445): MessageTone: null
W/CSCSettings( 1445): 1. Tag_Str: null
,D/TimaKeyStoreProvider( 4752): TimaSignature is unavailable
,D/ActivityThread( 4752): Added TimaKeyStore provider
,E/SMD     (  288): DCD OFF
,I/ThumbnailProvider( 4752): ThumbnailProvider onCreate()
,I/DocumentBroadcastReceiver( 4752): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 4752): [START] processBroadcastIntent ...
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 4342): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
D/GalleryCacheReady( 4342): handleMeidaScanFinish()
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/FaceInterface( 4342): requestFaceScan() is called.
,W/LocalSuggestAlbumData( 4342): query fail: 
,W/LocalSuggestAlbumData( 4342): query fail: 
,I/BroadcastProcessorService( 4752): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,I/FaceInterface( 4342): startFaceScan() : waiting 5 sec
,I/SystemInfo( 4752): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 4752): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
,I/BroadcastProcessorService( 4752): [START] DocumentService startDocumentService
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,I/DocumentService( 4752): DocumentService onCreate ... service
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4752): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4752): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/MediaStoreImporter( 4269): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,E/SystemInfo( 4752): [SIOP LEVEL] : 0
,I/DocumentService( 4752): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4752): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/File    ( 4752): fail readDirectory() errno=13
E/File    ( 4752): fail readDirectory() errno=13
,I/SystemInfo( 4752): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 4752): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 4752): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :41
E/DocumentService( 4752): [THUMBNAIL] Total Time taken for each file :0
E/        ( 4752): [INDEX] Total time taken for each file :0
,I/DocumentService( 4752): DocumentService onDestroy start
,I/DocumentService( 4752): DocumentService onDestroy end
,I/DocumentService( 4752): DocumentService cleanupEverything start
,I/IndexParserThreadsManager( 4752): InterruptedException: null
,I/SystemInfo( 4752): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 4752): DocumentService cleanupEverything end
,I/Process ( 4752): Sending signal. PID: 4752 SIG: 9
,I/SettingSearch/SearchIntentReceiver( 1293): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1293): LOCALE_CHANGED call search setting db finish!!
,I/ActivityManager( 1013): Killing 4006:com.sec.android.app.mt/1000 (adj 15): empty #31
,I/SettingSearch/SearchIntentReceiver( 1293): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/ActivityManager( 1013): Waited long enough for: ServiceRecord{3e08f9ac u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SettingSearch/SearchIntentReceiver( 1293): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 1293): LOCALE_CHANGED call search setting db finish!!
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1013): Process com.samsung.indexservice (pid 4752)(adj 9) has died(83,1167)
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_4006/cgroup.procs: No such file or directory
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1837): callingUid 10012, callindPid: 1837
,I/MusicLeanback( 4269): Conditions not met for autocaching.
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
I/MusicLeanback( 4269): Stop autocaching.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/GmsUtils( 4269): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 4269): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,I/PolicyManagerBroadcastReceiver( 4477): This process will be killed soon.
,I/Process ( 4477): Sending signal. PID: 4477 SIG: 9
,I/ActivityManager( 1013): Process com.sec.android.app.wluc (pid 4477)(adj 15) has died(83,1167)
,I/FaceInterface( 4342): startFaceScan() : going on
,D/FaceInterface( 4342): startFaceScan() is called.
,D/ContentApp( 1230): startScan() is called.
,D/FaceValue( 1230): mSleepTime: 800
D/FaceValue( 1230): mMaxThreadNum: 2
,W/FaceValue( 1230): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,D/ContentApp( 1230): startScan() is end.
,D/ContentApp( 1230): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1230): isNeedToRestore : start
,I/art     ( 1013): Background sticky concurrent mark sweep GC freed 131555(4MB) AllocSpace objects, 0(0B) LOS objects, 7% free, 50MB/55MB, paused 3.140ms total 107.310ms
,D/SSRM:n  ( 1013): SIOP:: AP = 380
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/FaceInterface( 4342): startFaceScan() : going on
,D/FaceInterface( 4342): startFaceScan() is called.
,D/ContentApp( 1230): startScan() is called.
,D/ContentApp( 1230): startScan() is end.
,D/ContentApp( 1230): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1230): isNeedToRestore : start
,D/PowerManagerService( 1013): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1013): Nap time (uid 1000)...
,D/PowerManagerService( 1013): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1013): !@[ps] Screen__Off - 0 :  dream(timeout) (2)
,I/PowerManagerService( 1013): Going to sleep due to screen timeout (uid 1000)...
,D/DisplayPowerController( 1013): getFinalBrightness : Summary is 19 -> 19
D/DisplayPowerController( 1013): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1013): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService( 1013): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 1013): SecHardwareInterface.setBatteryADC : false
V/WindowOrientationListener( 1013): WindowOrientationListener disabled
D/PowerManagerService( 1013): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1013): handleSandman : startDream(true)
E/PowerManagerService( 1013): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService( 1013): Sleeping (uid 1000)...
D/PowerManagerService( 1013): [s] UserActivityState : 4 -> 0
,D/SensorService( 1013): [SO] activate (ident=0xb8f7bc50, enabled=0)
,I/Sensors ( 1013): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/SurfaceFlinger(  256): id=10 createSurf (720x1280),-1 flag=20004, DolorFade
,D/SensorManager( 1013): unregisterListener ::   
,D/KeyguardViewMediator( 1177): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1177): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1177): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1177): notifyScreenOffLocked
,D/PowerManagerService( 1013): Excessive delay in ColorFade : createSurface: 21ms
,I/Adreno-EGL( 1013): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1013): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1013): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1013): Local Branch: 
I/Adreno-EGL( 1013): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1013): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1013):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/Launcher.HomeView( 1467): onPause
,D/Launcher( 1467): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/KeyguardViewMediator( 1177): timeout : 5000
,D/PowerManagerService( 1013): Excessive delay in ColorFade : createEglContext: 22ms
,D/PermissionCache(  256): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (207 us)
,D/PowerManagerService( 1013): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 24ms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4787): MountEmulatedStorage(),
,E/Zygote  ( 4787): v2
,I/ActivityManager( 1013): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=4787 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
I/libpersona( 4787): KNOX_SDCARD checking this for 10142
I/libpersona( 4787): KNOX_SDCARD not a persona
,I/SELinux ( 4787): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/KeyguardViewMediator( 1177): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 1177): handleNotifyScreenOff
D/VolumePanel( 1177): onScreenTurnedOff()
D/VolumePanel( 1177): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1177): mCoverBroadcastReceiver: Screen OFF end
I/SELinux ( 4787): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,D/SecKeyguardClockSingleView( 1177): onScreenTurnedOff
,E/SELinux ( 4787): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/ActivityThread( 1467): updateVisibility : ActivityRecord{3e166ebd token=android.os.BinderProxy@140ab565 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,D/Launcher.HomeView( 1467): onStop
,E/SmartFaceService( 1013): onReceive: android.intent.action.SCREEN_ON
,W/System.err( 1013): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1013): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err( 1013): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1013): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1013): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
,W/System.err( 1013): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1013): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1013): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
,W/System.err( 1013): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1013): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1013): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1013): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1013): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1013): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1013): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/SmartFaceService( 1013): fail to set sysfs 1
W/System.err( 1013): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1013): 	... 10 more
,D/PowerManagerService( 1013): Excessive delay in ColorFade : initGLShaders: 73ms
,E/SMD     (  288): DCD OFF
,D/InputMethodManagerService( 1013): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/PowerManagerService( 1013): Excessive delay in ColorFade prepare: 160ms
,D/DisplayPowerController( 1013): ColorFade: onAnimationStart
D/DisplayPowerController( 1013): getFinalBrightness : Summary is 60 -> 60
D/DisplayPowerController( 1013): performScreenOffTransition : no brightness animation
,D/MotionRecognitionService( 1013):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService( 1013):  handler : SCREEN_ON end
,I/WifiNative-HAL( 1013): startHal
,E/wifi    ( 1013): getStaticLongField sWifiHalHandle 0x9cae27fc
I/WifiNative-HAL( 1013): Could not start hal
,D/NotificationService( 1013): ACTION_SCREEN_ON
D/LightsService( 1013): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1013) 
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,D/LightsService( 1013): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1013): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1013): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=on
V/voice   (  281): voice_set_parameters: enter: screen_state=on
V/voice   (  281): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  281): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  281): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  281): adev_set_parameters: exit
,D/TimaKeyStoreProvider( 4787): TimaSignature is unavailable
,D/ActivityThread( 4787): Added TimaKeyStore provider
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/IpRemoteDisplayController( 1013): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 1013): Bridge Server is not available
,I/art     ( 1013): Background partial concurrent mark sweep GC freed 367919(21MB) AllocSpace objects, 10(7MB) LOS objects, 31% free, 35MB/51MB, paused 7.626ms total 271.706ms
,D/GpsLocationProvider( 1013): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1013): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1013): MSG_ACTION_SCREEN_ON called
,V/TaskCloserActivity( 4787): TaskCloserActivity enter()
,V/TaskCloserActivity( 4787): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/CoverManagerWhiteLists( 1013): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1430): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1430): call the applyRouting
,D/accuweather( 1688): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1688): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1688): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1688): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
,D/ActivityManager( 1013): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1778): getNextShiftState() cursorCapsMode : 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LightsService( 1013): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1013) 
,D/LightsService( 1013): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/BatteryService( 1013): turn on LED for fully charged
,D/LightsService( 1013): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1013): write_int failed to open -1
D/LightsService( 1013): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:n  ( 1013): SIOP:: AP = 380
,E/SmartFaceService( 1013): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1013): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1013): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1013): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1013): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1013): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1013): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1013): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1013): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1013): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1013): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SmartFaceService( 1013): fail to set sysfs 0
W/System.err( 1013): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1013): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1013): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1013): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1013): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1013): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1013): 	... 10 more
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,D/MotionRecognitionService( 1013):   mReceiver.onReceive : ACTION_SCREEN_OFF
,D/daemonapp( 1336): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1336): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SamsungIME( 1778): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/WifiNative-HAL( 1013): startHal
,E/wifi    ( 1013): getStaticLongField sWifiHalHandle 0x9cae27fc
I/WifiNative-HAL( 1013): Could not start hal
,D/NotificationService( 1013): ACTION_SCREEN_OFF
D/LightsService( 1013): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1013) 
E/MotionRecognitionService( 1013):  handler : SCREEN_OFF end 
D/LightsService( 1013): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1013): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1013): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=off
,D/daemonapp( 1336): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
V/voice   (  281): voice_set_parameters: enter: screen_state=off
V/voice   (  281): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  281): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  281): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  281): adev_set_parameters: exit
,D/comsamsunglog( 1336): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1336): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1336): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1336): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1336): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1336): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1336): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1336): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1457383020000
D/daemonapp( 1336): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1457361451516
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/BackgroundCompactionService( 1013): Schedule Type1 BGCompaction
,D/daemonapp( 1336): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1336): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1336): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1336): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1336): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/IpRemoteDisplayController( 1013): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 1013): Bridge Server is not available
,D/GpsLocationProvider( 1013): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/PersonaManagerService( 1013): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1013): MSG_ACTION_SCREEN_OFF called
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1404): [EmergencyStateReceiver] binteractive [false] why[3]
,D/DisplayPowerState( 1013): !@ ColorFade entry
,D/DisplayPowerController( 1013): ColorFade: onAnimationEnd
,D/DisplayPowerController( 1013): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1013): performScreenOffTransition : no brightness animation
,D/lights  ( 1013): lcd : 0 +
,I/BatteryStatsDumper( 1013): In refreshStats isReason Screen ON/OFF: true
,D/lights  ( 1013): lcd : 0 -,
,D/DisplayPowerController( 1013): getFinalBrightness : Summary is 0 -> 0
,D/DisplayPowerController( 1013): performScreenOffTransition : no brightness animation
,D/PowerManagerService( 1013): [s] DisplayPowerCallbacks : onStateChanged()
,D/NfcService( 1430): call the applyRouting
,D/PowerManagerService( 1013): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 1013): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1013): sysfs_write -: /sys/class/input/event1/device/enabled: 0,
,D/accuweather( 1688): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
D/MISC PowerHAL( 1013): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/accuweather( 1688): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/MISC PowerHAL( 1013): sysfs_write -: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1013): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1013): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1013): Got set_interactive hint
,D/DisplayManagerService( 1013): !@display_state: ON -> OFF
,I/DisplayManagerService( 1013): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  256): Set power mode=0, type=0 flinger=0xb80d2690
D/qdhwcomposer(  256): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager( 1013): Display changed displayId=0
E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
,D/accuweather( 1688): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,I/BatteryStatsDumper( 1013): Screen bin #0: time=11 power=6.416666666666666E-5
I/BatteryStatsDumper( 1013): Screen bin #1: time=12075 power=0.2113125
I/BatteryStatsDumper( 1013): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1013): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1013): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1013): Previous Battery Level: 0 Current Level: 100 Delta: -100
,D/StatusBar.NetworkController( 1177): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/accuweather( 1688): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1688): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1688): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1688): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1935): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/SSRM:n  ( 1013): SIOP:: AP = 380
,D/PowerManagerService( 1013): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1688): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1688): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1688): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1688): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1688): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1688): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1688): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  256): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl( 1013): Excessive delay in setPowerMode(): 254ms
E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
D/PowerManagerService( 1013): Excessive delay in !@display_state: OFF: 256ms
,I/BatteryStatsDumper( 1013): Writing to database completed
I/libsuspend( 1013): !@autosuspend_wakeup_count_enable
I/libsuspend( 1013): !@autosuspend_wakeup_count_enable done
,I/PowerManagerService( 1013): [PWL] Off : 0s ago
D/PowerManagerService( 1013): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 275ms
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 4617): Thread[GAThread,5,main]: No campaign data found.
,I/art     ( 1013): Background sticky concurrent mark sweep GC freed 133776(5MB) AllocSpace objects, 11(2MB) LOS objects, 10% free, 45MB/51MB, paused 3.288ms total 121.296ms
,W/PackageManager( 1013): verifying app can be installed or not
D/ApplicationPolicy( 1013): isApplicationInstallationEnabled
,D/ApplicationPolicy( 1013): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1013): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1013): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1013): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy( 1013): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1013): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1013): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1013): isApplicationInstallationEnabled :  Checking SIG BL - true
,D/ApplicationPolicy( 1013): isApplicationInstallationEnabled :  enabled true
,I/AASAInstall( 1013): ship mode
,D/SSRM:a  ( 1013): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1013): SettingsAirViewInfo:: 000000000
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/art     ( 1013): Background partial concurrent mark sweep GC freed 284366(18MB) AllocSpace objects, 11(7MB) LOS objects, 29% free, 38MB/54MB, paused 2.542ms total 191.769ms
,D/PackageManager( 1013): Existing package
,D/PackageManager( 1013): Renaming /data/app/vmdl870288594.tmp to /data/app/com.test.thalitest-1
,D/PackageManager( 1013): installNewPackageLI: Package{2090fa2f com.test.thalitest}
,I/PackageManager( 1013): scanFileNewer : com.test.thalitest
,I/ActivityManager( 1013): Waited long enough for: ServiceRecord{ce99389 u0 com.sec.bcservice/.BroadcastService}
,I/ActivityManager( 1013): Killing 4042:com.samsung.android.sconnect/u0a125 (adj 15): empty #31,
,I/art     ( 1013): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
I/art     ( 1013): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.test.thalitest-1/arm/base.odex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
D/PackageManager( 1013): Running dexopt on: /data/app/com.test.thalitest-1/base.apk pkg=com.test.thalitest isa=arm vmSafeMode=false interpret_only=false
,I/dex2oat ( 4813): ----------------------------------------------------
,I/dex2oat ( 4813): <SS>: S T A R T I N G . . .
I/dex2oat ( 4813): <SS>: going to process manifest for 32-bit...
,I/        ( 4813): SS_ART_lib [I]: Memory allocation: ctx
,I/        ( 4813): SS_ART_lib [I]: Memory allocation: manifest_buf
I/        ( 4813): SS_ART_lib [I]: Parsing Manifest for SS stuff
,I/        ( 4813): SS_ART_lib [I]: Memory allocation: ctx->libs
I/        ( 4813): SS_ART_lib [I]: Memory allocation: ctx->package_name
I/        ( 4813): SS_ART_lib [I]: Parsing completed
I/        ( 4813): SS_ART_lib [I]: permission is absent: /data/app/com.test.thalitest-1/base.apk
I/        ( 4813): SS_ART_lib [I]: Closing zip file: /data/app/com.test.thalitest-1/base.apk
I/        ( 4813): SS_ART_lib [I]: access to SS denied
I/        ( 4813): SS_ART_lib [I]: ctx will be cleaned
I/        ( 4813): SS_ART_lib [I]: ctx component will be cleaned: ctx->libs
I/        ( 4813): SS_ART_lib [I]: ctx component is cleaned: ctx->libs
I/        ( 4813): SS_ART_lib [I]: ctx component will be cleaned: ctx->package_name
I/        ( 4813): SS_ART_lib [I]: ctx component is cleaned: ctx->package_name
I/        ( 4813): SS_ART_lib [I]: ctx is cleaned
I/dex2oat ( 4813): /system/bin/dex2oat --zip-fd=11 --zip-location=/data/app/com.test.thalitest-1/base.apk --oat-fd=12 --art-fd=-1 --oat-location=/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup( 1013): failed to open /acct/uid_10125/pid_4042/cgroup.procs: No such file or directory
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/FaceInterface( 4342): startFaceScan() : going on
D/FaceInterface( 4342): startFaceScan() is called.
,D/ContentApp( 1230): startScan() is called.
,D/ContentApp( 1230): startScan() is end.
,D/ContentApp( 1230): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1230): isNeedToRestore : start
,I/dex2oat ( 4813): dex2oat took 465.419ms (threads: 4)
,I/PackageManager( 1013): do mInstaller.dexopt : 0
,D/PackageManager( 1013): Time to dexopt: 0.536 seconds
,W/System.err( 1013): java.io.FileNotFoundException: /data/app/com.test.thalitest-1: open failed: EISDIR (Is a directory)
,W/System.err( 1013): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err( 1013): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 1013): 	at android.content.pm.PackageParser.getHashValueOfPackage(PackageParser.java:5140)
,W/System.err( 1013): 	at com.android.server.pm.PackageManagerService.saveHash(PackageManagerService.java:19520)
W/System.err( 1013): 	at com.android.server.pm.PackageManagerService.access$5400(PackageManagerService.java:342)
,W/System.err( 1013): 	at com.android.server.pm.PackageManagerService$19.run(PackageManagerService.java:19505)
,W/System.err( 1013): Caused by: android.system.ErrnoException: open failed: EISDIR (Is a directory)
,W/System.err( 1013): 	at libcore.io.IoBridge.open(IoBridge.java:446)
W/System.err( 1013): 	... 5 more
,W/PackageSettings( 1013): Skipping PackageSetting{83cd73d com.example.hello/10174} due to missing metadata
,I/HarmonyEASService( 1013): Updating for all 1
D/PackageManager( 1013): New package installed
,W/PackageSettings( 1013): Skipping PackageSetting{83cd73d com.example.hello/10174} due to missing metadata
,D/PackageManager( 1013): doPostInstall for uid{10155}
,D/PackageManager( 1013): token 1 to BM for possible restore
,V/BackupManagerService( 1013): restoreAtInstall pkg=com.test.thalitest token=1 restoreSet=0
,V/BackupManagerService( 1013): Finishing install immediately
D/PackageManager( 1013): BM finishing package install for 1
,D/PackageManager( 1013): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 1013): [MSG] MCS_UNBIND
,I/InputReader( 1013): Reconfiguring input devices.  changes=0x00000010
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,I/PageBuddyNotiSvc( 4026): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 1445): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 4821): MountEmulatedStorage()
E/Zygote  ( 4821): v2
I/libpersona( 4821): KNOX_SDCARD checking this for 1000
I/libpersona( 4821): KNOX_SDCARD not a persona
,I/SELinux ( 4821): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=4821 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4821): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4821): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RegisteredComponentCache( 1430): Collect Tech packages for Knox
,D/PackageManager( 1013): [MSG] POST_INSTALL: observer{992099602}
D/PackageManager( 1013):           Handling post-install for 1
,I/ActivityManager( 1013): Killing 4058:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,D/PersonaManager( 1430): isKioskContainerExistOnDevice
,D/TimaKeyStoreProvider( 4821): TimaSignature is unavailable
,D/ActivityThread( 4821): Added TimaKeyStore provider
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Settings( 1013): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,D/PersonaManager( 1430): isKioskContainerExistOnDevice
,D/AASAservice-UpdateReceiver( 4821): AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.google.android.gms, uid = -1
,I/InputReader( 1013): Reconfiguring input devices.  changes=0x00000010
,D/SecContentProvider2( 1013): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1013): mCursor = null
,E/SamsungIME( 1778): mOCRHelper is null
,D/RegisteredServicesCache( 1430): empty dynamic service
,I/splitIntent( 1013): intent=android.intent.action.PACKAGE_CHANGED will be not split. because same process=com.google.android.googlequicksearchbox:search is in other queue. index=1
I/splitIntent( 1013): base  index=1, name=com.google.android.googlequicksearchbox com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher
I/splitIntent( 1013): other index=7, name=com.google.android.googlequicksearchbox com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
I/splitIntent( 1013): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_CHANGED !! do not split it!!
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 4839): MountEmulatedStorage()
,E/Zygote  ( 4839): v2
I/libpersona( 4839): KNOX_SDCARD checking this for 10057
I/libpersona( 4839): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher: pid=4839 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/SELinux ( 4839): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Killing 4098:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,I/SELinux ( 4839): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4839): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/RegisteredComponentCache( 1430): Collect Tech packages for Knox
,D/PersonaManager( 1430): isKioskContainerExistOnDevice
,D/TimaKeyStoreProvider( 4839): TimaSignature is unavailable
,D/ActivityThread( 4839): Added TimaKeyStore provider
,W/IntentResolver( 1013): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,D/BackupManagerService( 1013): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1013): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService( 1013): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.backup.TRANSPORT_HOST
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,D/PersonaManager( 1430): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1430): empty dynamic service
,D/SecContentProvider2( 1013): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1013): mCursor = null
,W/ResourceType( 1013): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 107023(5MB) AllocSpace objects, 20(6MB) LOS objects, 27% free, 42MB/58MB, paused 4.495ms total 293.684ms
,D/PackageManager( 1013): result of install: 1{992099602}
,I/PackageManager( 1013): Observer no longer exists.
,W/ResourcesManager( 1013): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1013): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1013): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService( 1013): PackageReceiver onReceive()
D/RCPManagerService( 1013): App Installed with packageNAme = com.test.thalitest
,E/RCPManagerService( 1013):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: Attempt to invoke virtual method 'java.lang.String android.os.Bundle.getString(java.lang.String)' on a null object reference
D/RCPManagerService( 1013):  PackageReceiver onReceive() bundle null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/KnoxMUMContainerPolicy( 1013): mPackageReceiver : action - android.intent.action.PACKAGE_ADDED
,D/BackupManagerService( 1013): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,W/BackupManagerService( 1013): Removing schedule queue dupe of com.test.thalitest
,V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_ADDED
V/EnterpriseBillingPolicy( 1013): uID is 10155
V/EnterpriseBillingPolicy( 1013): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - exit null : containerId = 0
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - end - null
,I/GCoreNlp( 1837): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/PersonaPolicyManagerService( 1013): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,V/BackupManagerService( 1013): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 1013): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2be385f
,V/AlarmManagerEXT( 1013): com.test.thalitest(10155) is added to mUserAppList
D/KnoxMUMContainerPolicy( 1013): packageInstalledForExternalStorage com.test.thalitest
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
D/EnterpriseDeviceManagerService( 1013): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1013): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1013): no available spell checker services found
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourceType( 1013): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/CrashAnrDetector( 1013): onPackageAdded : com.test.thalitest
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,W/libprocessgroup( 1013): failed to open /acct/uid_10131/pid_4058/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10139/pid_4098/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1013): applying state to connected service
,D/LocationProviderProxy( 1013): applying state to connected service
,D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/LocationManagerService( 1013): getProviders()=[passive]
,E/Zygote  ( 4861): MountEmulatedStorage()
,E/Zygote  ( 4861): v2
,I/libpersona( 4861): KNOX_SDCARD checking this for 10015
I/libpersona( 4861): KNOX_SDCARD not a persona
,I/SELinux ( 4861): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4861): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4861 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,E/SELinux ( 4861): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/LocationProviderProxy( 1013): applying state to connected service
,I/GCoreNlp( 1837): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/TimaKeyStoreProvider( 4861): TimaSignature is unavailable
,D/ActivityThread( 4861): Added TimaKeyStore provider
,I/ActivityManager( 1013): Killing 4167:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 3817): Creating RTCS
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Zygote  ( 4880): MountEmulatedStorage()
E/Zygote  ( 4880): v2
I/libpersona( 4880): KNOX_SDCARD checking this for 10032
I/libpersona( 4880): KNOX_SDCARD not a persona
,I/SELinux ( 4880): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4880): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=4880 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 4880): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Babel   ( 3817): Destroying RTCS
,I/ActivityManager( 1013): Killing 4207:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4880): TimaSignature is unavailable
D/ActivityThread( 4880): Added TimaKeyStore provider
,I/FeatureConfig( 4880): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/ActivityManager( 1013): Killing 4226:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for fully charged
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
,I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,I/PackagesMonitor( 4342): PackagesMonitor onReceive :com.google.android.gms
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ResourcesManager( 4880): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4880): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4880): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4880): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 4880): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 4880): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/UpdateIcingCorporaServi( 4839): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/ResourcesManager( 4880): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
W/ResourcesManager( 4880): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4880): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 4901): MountEmulatedStorage()
I/libpersona( 4901): KNOX_SDCARD checking this for 10069
E/Zygote  ( 4901): v2
I/libpersona( 4901): KNOX_SDCARD not a persona
I/SELinux ( 4901): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=4901 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4901): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4901): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
W/ResourcesManager( 4880): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 4880): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 4880): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 4901): TimaSignature is unavailable
,D/ActivityThread( 4901): Added TimaKeyStore provider
,W/ResourcesManager( 4880): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 4880): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/libprocessgroup( 1013): failed to open /acct/uid_10072/pid_4167/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_4207/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_4226/cgroup.procs: No such file or directory
,D/FileShare-Server( 4901): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4880): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4880): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4880): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 4916): MountEmulatedStorage()
I/libpersona( 4916): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4916): v2
I/libpersona( 4916): KNOX_SDCARD not a persona
I/SELinux ( 4916): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=4916 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4916): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4916): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 4880): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 4880): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4839): UpdateCorporaTask done [took 114 ms] updated apps [took 113 ms] 
,D/TimaKeyStoreProvider( 4916): TimaSignature is unavailable
,D/ActivityThread( 4916): Added TimaKeyStore provider
I/ActivityManager( 1013): Killing 4414:com.wsomacp/u0a25 (adj 15): empty #31
,W/ResourcesManager( 4916): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4880): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4880): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4880): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 4880): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 4880): system/finder_cp/cpdata.xml file not found
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4932): MountEmulatedStorage(),
E/Zygote  ( 4932): v2
I/libpersona( 4932): KNOX_SDCARD checking this for 1000
I/libpersona( 4932): KNOX_SDCARD not a persona
,I/SELinux ( 4932): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4932 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 4436:com.sec.smartcard.manager/u0a153 (adj 15): empty #31
,I/SELinux ( 4932): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4932): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4932): TimaSignature is unavailable
,D/ActivityThread( 4932): Added TimaKeyStore provider
,D/KnoxSetupWizardDbHelper( 4932): dbMigrationFlag : false
,D/ShortcutReceiver( 4932):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4948): MountEmulatedStorage(),
E/Zygote  ( 4948): v2
,I/libpersona( 4948): KNOX_SDCARD checking this for 10120
I/libpersona( 4948): KNOX_SDCARD not a persona
,I/SELinux ( 4948): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4948): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1013): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4948 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 4367:com.android.mms/u0a46 (adj 15): empty #31
,E/SELinux ( 4948): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1013): failed to open /acct/uid_10025/pid_4414/cgroup.procs: No such file or directory
,I/art     (  308): Explicit concurrent mark sweep GC freed 8755(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 792us total 24.753ms
,D/TimaKeyStoreProvider( 4948): TimaSignature is unavailable
D/ActivityThread( 4948): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 737us total 20.284ms
,W/ResourcesManager( 4948): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 726us total 19.961ms,
,D/CountryDetector( 1013): No listener is left
,W/libprocessgroup( 1013): failed to open /acct/uid_10153/pid_4436/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10046/pid_4367/cgroup.procs: No such file or directory
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4970): MountEmulatedStorage()
I/ActivityManager( 1013): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4970 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 4970): v2
I/libpersona( 4970): KNOX_SDCARD checking this for 10028
I/SELinux ( 4970): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4970): KNOX_SDCARD not a persona
,I/SELinux ( 4970): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4970): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Killing 4492:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4970): TimaSignature is unavailable
,D/ActivityThread( 4970): Added TimaKeyStore provider
,I/ActivityManager( 1013): Waited long enough for: ServiceRecord{3dfe4829 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_4492/cgroup.procs: No such file or directory
,D/Finsky  ( 4970): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 4970): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Settings( 4970): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
W/Settings( 4970): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4970): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4970): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4970): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/System.out( 4970): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 4970): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4970): (HTTPLog)-Static: isShipBuild true
I/System.out( 4970): (HTTPLog)-Thread-853-1020322209: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4970): (HTTPLog)-Static: isSBSettingEnabled false
,D/Ads     ( 4970): Skipping gmscore version check
,D/EnterpriseController(  276): uids 10028
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 10028
,D/ActivityManager( 1013): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4970): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageBroadcastService( 2001): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/HomeSyncInstallReceiver( 1430): This pkg do not need BT addr. Do nothing
,I/splitIntent( 1013): Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=14, mSplitNum[1]=23, mSplitNum[2]=36, mBgSplitQueueNum=3 divideNum= 11 r.nextReceiver= 2 receivers.size=47
,I/splitIntent( 1013): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,I/PackageBroadcastService( 2001): Null package name or gms related package.  Ignoreing.
,D/AASAservice-UpdateReceiver( 4821): AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
,I/AASAservice-TokenRule( 4821): parseToken()
,W/System.err( 4821): java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
W/System.err( 4821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 4821): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 4821): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/System.err( 4821): 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:80)
W/System.err( 4821): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:52)
W/System.err( 4821): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 4821): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 4821): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 4821): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4821): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4821): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 4821): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4821): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4821): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4821): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 4821): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 4821): 	at libcore.io.Posix.open(Native Method)
W/System.err( 4821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 4821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 4821): 	... 14 more
E/AASAservice-TokenRule( 4821): parseToken() : TokenFile is null
,E/AASAservice-UpdateReceiver( 4821): AASARuleUpdateResult() : Rule file is not exist.
,I/PackagesMonitor( 4342): PackagesMonitor onReceive :com.test.thalitest
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1013): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5016 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
E/Zygote  ( 5016): MountEmulatedStorage()
I/libpersona( 5016): KNOX_SDCARD checking this for 10152
E/Zygote  ( 5016): v2
I/libpersona( 5016): KNOX_SDCARD not a persona
I/SELinux ( 5016): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5016): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5016): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5016): TimaSignature is unavailable
,D/ActivityThread( 5016): Added TimaKeyStore provider
,E/Zygote  ( 5032): MountEmulatedStorage()
,E/Zygote  ( 5032): v2
I/libpersona( 5032): KNOX_SDCARD checking this for 10046
I/libpersona( 5032): KNOX_SDCARD not a persona
,I/SELinux ( 5032): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5032): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1013): Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=5032 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/SELinux ( 5032): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
W/ContextImpl( 3722): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5032): TimaSignature is unavailable
,D/ActivityThread( 5032): Added TimaKeyStore provider
,E/Zygote  ( 5052): MountEmulatedStorage()
E/Zygote  ( 5052): v2
I/libpersona( 5052): KNOX_SDCARD checking this for 1000
I/libpersona( 5052): KNOX_SDCARD not a persona
,I/SELinux ( 5052): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5052): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5052): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/SQLiteLog( 5016): (284) automatic index on shooting_modes(title_id)
I/ActivityManager( 1013): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5052 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,D/TimaKeyStoreProvider( 5052): TimaSignature is unavailable
,D/ActivityThread( 5052): Added TimaKeyStore provider
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5032): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5032): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5032): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5032): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5032): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5032): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 5071): MountEmulatedStorage()
E/Zygote  ( 5071): v2
I/libpersona( 5071): KNOX_SDCARD checking this for 1000
I/libpersona( 5071): KNOX_SDCARD not a persona
I/SELinux ( 5071): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1013): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5071 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 5071): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5071): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5083): MountEmulatedStorage(),
,I/libpersona( 5083): KNOX_SDCARD checking this for 10156
E/Zygote  ( 5083): v2
I/libpersona( 5083): KNOX_SDCARD not a persona
I/SELinux ( 5083): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/TimaKeyStoreProvider( 5071): TimaSignature is unavailable
D/ActivityThread( 5071): Added TimaKeyStore provider
I/SELinux ( 5083): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5083 uid=10156 gids={50156, 9997} abi=armeabi-v7a
E/SELinux ( 5083): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/MmsApp( 5032): [start]    onCreate() consume time = 0.0
,D/TimaKeyStoreProvider( 5083): TimaSignature is unavailable
,D/ActivityThread( 5083): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_LOG( 5052): DEFAULT_LOGON : true
W/ResourcesManager( 5071): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
I/PCWCLIENTTRACE_LOG( 5052): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5052): new DMDBOpenHelper instance
,I/ActivityManager( 1013): Killing 4507:com.samsung.android.app.powersharing/u0a122 (adj 15): empty #31
,I/PCWCLIENTTRACE_PushUtil( 5052): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5052): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5052): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5052): [onReceive] - android.intent.action.PACKAGE_ADDED
,I/Icing   ( 2001): Storage manager: low false usage 1.72MB avail 10.16GB capacity 11.68GB
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,I/TapandpayWidget:TapandpayAppWidgetProvider( 5083): onReceive()
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5083): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/TapandpayWidget:Utils( 5083): Clear T&P info.
,E/Zygote  ( 5104): MountEmulatedStorage()
E/Zygote  ( 5104): v2
I/libpersona( 5104): KNOX_SDCARD checking this for 1000
I/libpersona( 5104): KNOX_SDCARD not a persona
,I/SELinux ( 5104): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5104): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5104): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=5104 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 4522:com.sec.android.app.sns3/u0a33 (adj 15): empty #31
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,V/AlarmManager( 1013): waitForAlarm result :4
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5104): TimaSignature is unavailable
,D/ActivityThread( 5104): Added TimaKeyStore provider
,E/Zygote  ( 5121): MountEmulatedStorage()
E/Zygote  ( 5121): v2
I/libpersona( 5121): KNOX_SDCARD checking this for 10091
I/libpersona( 5121): KNOX_SDCARD not a persona
,I/SELinux ( 5121): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5121): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1013): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5121 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 5121): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Killing 4553:com.sec.spp.push/u0a35 (adj 15): empty #31
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5083): Widget is not attached.
,D/TimaKeyStoreProvider( 5121): TimaSignature is unavailable
,D/ActivityThread( 5121): Added TimaKeyStore provider
,D/ActivityManager( 1013): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 4970): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,W/art     ( 5032): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 124.426ms
,I/libpersona( 5138): KNOX_SDCARD checking this for 10010
E/Zygote  ( 5138): MountEmulatedStorage()
I/libpersona( 5138): KNOX_SDCARD not a persona
E/Zygote  ( 5138): v2
I/SELinux ( 5138): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5138): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5138): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1013): failed to open /acct/uid_10122/pid_4507/cgroup.procs: No such file or directory,
W/libprocessgroup( 1013): failed to open /acct/uid_10033/pid_4522/cgroup.procs: No such file or directory
,I/ActivityManager( 1013): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5138 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/libprocessgroup( 1013): failed to open /acct/uid_10035/pid_4553/cgroup.procs: No such file or directory
,I/ActivityManager( 1013): Killing 4570:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/TimaKeyStoreProvider( 5138): TimaSignature is unavailable
,D/ActivityThread( 5138): Added TimaKeyStore provider
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/DBG_POLICYDM( 5104): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 5104): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,D/Mms/TelephonyPermission( 5032): start operation mode monitor
,D/Mms/ArtClassLoader( 5032): init before art
,W/libprocessgroup( 1013): failed to open /acct/uid_10035/pid_4570/cgroup.procs: No such file or directory
,W/ResourcesManager( 5032): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5104): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 5104): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 5104): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 5104): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/Mms/TelephonyPermission( 5032): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 5032): isDefault true
,D/Mms/MmsApp( 5032): onCreate() com.android.mms
,I/DBG_POLICYDM( 5104): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,I/DBG_POLICYDM( 5104): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 5104): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 5104): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 5104): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 5104): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 5104): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5160): MountEmulatedStorage()
,E/Zygote  ( 5160): v2
I/libpersona( 5160): KNOX_SDCARD checking this for 10035
I/libpersona( 5160): KNOX_SDCARD not a persona
,I/SELinux ( 5160): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5160): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5160): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5160 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5160): TimaSignature is unavailable,
D/ActivityThread( 5160): Added TimaKeyStore provider
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5104): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,E/SPPClientService( 5160): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5160): [PushClientApplication] Push log off : This is Ship build version
,E/Zygote  ( 5182): MountEmulatedStorage(),
,E/Zygote  ( 5182): v2
I/libpersona( 5182): KNOX_SDCARD checking this for 10038
I/libpersona( 5182): KNOX_SDCARD not a persona
,I/SELinux ( 5182): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5182): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5182 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/DBG_POLICYDM( 5104): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
I/ActivityManager( 1013): Killing 4597:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
E/SELinux ( 5182): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/SPPClientService( 5160): PushLog.txt file is not deleted.,
D/SPPClientService( 5160): PushLog.txt file is not deleted.
D/SPPClientService( 5160): ============PushLog. stop!
I/DBG_POLICYDM( 5104): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5104): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,I/art     (  308): Explicit concurrent mark sweep GC freed 8740(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 25.528ms
,D/TimaKeyStoreProvider( 5182): TimaSignature is unavailable
,D/ActivityThread( 5182): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 16.785ms
,W/ResourcesManager( 5182): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5182): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 16.884ms,
,E/PhotosPlugin( 5121): Loading PhotosPlugin
,D/Mms/MmsApp( 5032): [start]    initCountryIso consume time = 602.798281
,W/libprocessgroup( 1013): failed to open /acct/uid_10035/pid_4597/cgroup.procs: No such file or directory
,V/AlarmManager( 1013): waitForAlarm result :4
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 4970): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/PowerManagerService( 1013): [PWL] Off : 5s ago
,I/PowerManagerService( 1013): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1013): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 1013): [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10012, pid=2001, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=834)
,I/PowerManagerService( 1013): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1013, ws=WorkSource{10054}) (elapsedTime=582)
,D/Mms/ArtClassLoader( 5032): init [DONE] art
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 212792(14MB) AllocSpace objects, 4(3MB) LOS objects, 33% free, 27MB/40MB, paused 2.808ms total 184.120ms
,D/CountryDetector( 1013): The first listener is added
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/Mms/MmsApp( 5032): [end]    initCountryIso consume time = 160.742083
,D/Mms/MmsConfig( 5032): [start]    MmsConfig.init() consume time = 0.436042
,D/Mms/MmsConfig( 5032): before partial update
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageBroadcastService( 2001): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/Mms/MmsConfig( 5032): Load Resize quality : 80
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2001): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/EasySignUpManager_1.0.1( 5032): serviceId : 1, features : -1
D/ChimeraModuleLdr( 2001): Loading module APK com.google.android.play.games
,D/EasySignUpManager_1.0.1( 5032): isAuth is false
,D/Mms/MmsConfig( 5032): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1445): query,matched:2117, calling pid = 5032
,D/TP/MmsSmsProvider( 1445): match 2117:Elapsed time : 0.753 ms
,D/EasySignUpManager_1.0.1( 5032): isAuth is false
D/EasySignUpManager_1.0.1( 5032): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 5032): mps_code.dat does not exist
E/CscParser( 5032): customer_path =/system/csc/customer.xml
E/CscParser( 5032): fileName + /system/csc/customer.xml
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/CscParser( 5032): mps_code.dat does not exist
E/CscParser( 5032): customer_path =/system/csc/customer.xml
E/CscParser( 5032): fileName + /system/csc/customer.xml
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/CscParser( 5032): getInstance fileName =/system/csc/customer.xml
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/MmsConfig( 5032):  enable multiwindow = true
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Mms/MessageUtils( 5032): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5032): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 5032): [end]    init() consume time = 101.95026,
D/Mms/Contact( 5032): [start]    init() consume time = 0.685312
,D/Mms/Contact( 5032): [end]    init consume time = 8.416563
,D/TP/MmsSmsProvider( 1445): query,matched:13, calling pid = 5032
,D/TP/MmsSmsProvider( 1445): match 13:Elapsed time : 1.229 ms
,D/Mms/DraftCache( 5032): [start]    rebuildCache consume time = 5.437344
,D/TP/MmsSmsProvider( 1445): query,matched:12, calling pid = 5032
,D/TP/MmsSmsProvider( 1445): match 12:Elapsed time : 1.600 ms
,D/Mms/DraftCache( 5032): [end]    rebuildCache consume time = 6.796198
,D/Mms/MethodReflector( 5032): getSubId is called
D/Mms/TelephonyUtils( 5032): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 5032): getTelephonyProperty is called
D/Mms/DownloadManager( 5032): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5032): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5032): auto download without roaming -> true
D/Mms/DownloadManager( 5032): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/Mms/MethodReflector( 5032): getSubId is called
D/Mms/MethodReflector( 5032): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5032): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5032): getLongSubId from simSlot 1, return Value = -1000
,D/Mms/MethodReflector( 5032): getTelephonyProperty is called
D/Mms/DownloadManager( 5032): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5032): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5032): auto download without roaming -> true
D/Mms/DownloadManager( 5032): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5032): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5032): mAutoDownload ------> true
,D/ComposerPerformance( 5032): 1457361457064 ms / [DONE] Composer constructor
,E/CII     ( 5032): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 5032): ReservationManager()
,I/Mms/ReservationManager( 5032): resetAfterConnected()
,D/TP/MmsSmsProvider( 1445): query,matched:7, calling pid = 5032
,D/TP/MmsSmsProvider( 1445): match 7:Elapsed time : 1.713 ms
,D/Mms/Conversation( 5032): [start]    init() consume time = 53.058697
,I/Mms/ReservationManager( 5032): getReservedSendMessageCount(): retMessageCount=0
,D/TP/MmsSmsProvider( 1445): deleteConversation threadId: 9223372036854775807
,D/Mms/MmsApp( 5032): [end]    onCreate() consume time = 4.085209
,D/TP/MmsSmsProvider( 1445): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1445): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1445): sUpgradeVersion = 0, db.getVersion() = 81
,D/TP/MmsSmsProvider( 1445): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1445): need read changed broadcast:false
,W/art     ( 2001): Suspending all threads took: 27.819ms
,D/Mms/DownloadManager( 5032): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/Conversation( 5032): [end]    init consume time = 10.850364
D/Mms/DownloadManager( 5032): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 5032): getSubId is called
D/Mms/MessagingNotification( 5032): [start]    init() consume time = 3.098698
,D/Mms/TelephonyUtils( 5032): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MessagingNotification( 5032): [end]    init consume time = 1.746823
,D/Mms/MethodReflector( 5032): getTelephonyProperty is called
D/Mms/DownloadManager( 5032): roaming -> false (slotId = 0)
,D/Mms/DownloadManager( 5032): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5032): auto download without roaming -> true
D/Mms/DownloadManager( 5032): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5032): mAutoDownload ------> true
,D/TP/MmsSmsProvider( 1445): query,matched:0, calling pid = 5032
V/TP/MmsSmsProvider( 1445): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1445): match 0:Elapsed time : 0.901 ms
,D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/Mms/Synchronizer( 5032): [start]    doSync consume time = 11.405469
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/Mms/SpamFilter( 5032): [start]    SpamFilter fill() begin consume time = 2.475937
,E/Zygote  ( 5211): MountEmulatedStorage(),
,I/libpersona( 5211): KNOX_SDCARD checking this for 10072
E/Zygote  ( 5211): v2
I/libpersona( 5211): KNOX_SDCARD not a persona
D/Mms/FreeMessageStatusReceiver( 5032): onReceive, action : android.intent.action.PACKAGE_ADDED
I/SELinux ( 5211): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5211 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,I/SELinux ( 5211): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1013): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
E/SELinux ( 5211): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/TP/MmsSmsProvider( 1445): update, matched:300, calling pid = 5032
V/TP/MmsSmsProvider( 1445): syncDBData start
V/TP/MmsSmsProvider( 1445): syncDBData sms end
V/TP/MmsSmsProvider( 1445): syncDBData mms end
V/TP/MmsSmsProvider( 1445): syncDBData end
,D/TP/MmsSmsProvider( 1445): query,matched:400, calling pid = 5032
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5211): TimaSignature is unavailable
,D/ActivityThread( 5211): Added TimaKeyStore provider
,D/Mms/FreeMessageReceiverService( 5032): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
,D/Mms/FreeMessageReceiverService( 5032): onHandleIntent: ACTION_PACKAGE_ADDED
,E/Zygote  ( 5227): MountEmulatedStorage(),
E/Zygote  ( 5227): v2
I/libpersona( 5227): KNOX_SDCARD checking this for 10047,
I/libpersona( 5227): KNOX_SDCARD not a persona
,I/SELinux ( 5227): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1013): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5227 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/SELinux ( 5227): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5227): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,D/Mms/Synchronizer( 5032): [end]    doSync consume time = 70.534167,
I/ActivityManager( 1013): Killing 4677:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
,D/Mms/SpamFilter( 5032): [end]    SpamFilter fill() finished consume time = 8.416719
,D/TimaKeyStoreProvider( 5227): TimaSignature is unavailable
D/ActivityThread( 5227): Added TimaKeyStore provider
,D/BadgeProvider( 5211): onCreate
,D/BadgeProvider( 5211): DatabaseHelper
,W/ResourcesManager( 5227): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5227): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5227): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/CheckinService( 2001): Done disabling old GoogleServicesFramework version
,D/Mms/MessagingNotification( 5032): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1445): query,matched:26, calling pid = 5032
,D/TP/SmsProvider( 1445): match 26:Elapsed time : 2.001 ms
,I/SL_DEBUG( 5182): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 5182): isLoggable:: SL_DEBUG_EXIST = false
,W/libprocessgroup( 1013): failed to open /acct/uid_10134/pid_4677/cgroup.procs: No such file or directory
,D/TP/MmsSmsProvider( 1445): query,matched:6, calling pid = 5032
,D/TP/MmsSmsProvider( 1445): match 6:Elapsed time : 1.296 ms
,D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5249): MountEmulatedStorage()
E/Zygote  ( 5249): v2
I/libpersona( 5249): KNOX_SDCARD checking this for 10025
I/libpersona( 5249): KNOX_SDCARD not a persona
,I/SELinux ( 5249): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5249): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5249 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,E/SELinux ( 5249): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 5249): TimaSignature is unavailable
,D/ActivityThread( 5249): Added TimaKeyStore provider
,I/ActivityManager( 1013): Killing 4077:com.android.calendar/u0a135 (adj 15): empty #31
,W/ResourcesManager( 5249): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/SMD     (  288): DCD OFF
,I/Icing   ( 2001): updateResources: need to parse f{com.google.android.gms}
,D/MyFiles ( 5227): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,I/ActivityManager( 1013): Killing 4695:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,E/installd(  282): system dir 0 : /system/app/
E/installd(  282): system dir 1 : /system/priv-app/
E/installd(  282): system dir 2 : /vendor/app/
E/installd(  282): system dir 3 : /oem/app/
I/TactileAssist( 1013): enable value -1
I/TactileAssist( 1013): internal enable value -1
I/TactileAssist( 1013): intensity value -1
I/TactileAssist( 1013): saveAppList value true
,I/TactileAssist( 1013): List of disabled apps :
,I/OMACP   ( 5249): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/,
D/Mms/Omacp( 5032): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5182): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,I/ActivityManager( 1013): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5267 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a,
,E/Zygote  ( 5267): MountEmulatedStorage(),
,E/Zygote  ( 5267): v2
I/libpersona( 5267): KNOX_SDCARD checking this for 10053,
I/libpersona( 5267): KNOX_SDCARD not a persona
,W/libprocessgroup( 1013): failed to open /acct/uid_10135/pid_4077/cgroup.procs: No such file or directory,
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_4695/cgroup.procs: No such file or directory
I/SELinux ( 5267): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5267): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5267): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/PackageManager( 1013): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,I/OMACP   ( 5249): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 5249): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 5249): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 5249): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 5249): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 5249): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 5249): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 5249): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 5249): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,D/TimaKeyStoreProvider( 5267): TimaSignature is unavailable
,D/ActivityThread( 5267): Added TimaKeyStore provider
I/OMACP   ( 5249): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 5249): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/OMACP   ( 5249): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 5249): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 5267): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink,
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,D/ChimeraCfgMgr( 2001): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2001): Module APK com.google.android.play.games already loaded
,D/Compatibility( 5267): onReceive() it will make start service
,D/ChimeraCfgMgr( 2001): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,I/System.out( 4970): Thread-842(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 4970): Thread-842(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 4970): Thread-842(ApacheHTTPLog):isShipBuild true
I/System.out( 4970): Thread-842(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4970): Thread-842(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5182): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/ActivityManager( 1013): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
D/Compatibility( 5267): onHandleIntent()
,D/Compatibility( 5267): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/Compatibility( 5267): found: 2
,D/EnterpriseController(  276): uids 10028
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 10028
,I/System.out( 4970): Thread-842 calls detatch()
,W/Finsky  ( 4970): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/UpdateIcingCorporaServi( 4839): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/AsyncTaskServiceImpl( 2001): Submit a task: k
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Compatibility( 5267): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/Compatibility( 5267): skipping ResolveInfo{2d61c3e com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5267): considering ResolveInfo{7b91a9f com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5267): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5267): enabling receiver ResolveInfo{25e6f7ec com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Compatibility( 5267): enabling receiver ResolveInfo{2f69a7b5 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5267): enabling receiver ResolveInfo{c13be4a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/ChimeraCfgMgr( 2001): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/Compatibility( 5267): enabling receiver ResolveInfo{1f9ec1bb com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5267): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/ChimeraCfgMgr( 2001): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/System.out( 4970): Thread-843(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 4970): Thread-843(ApacheHTTPLog):isShipBuild true
I/System.out( 4970): Thread-843(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4970): Thread-843(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4970): Thread-843 calls detatch()
,D/k       ( 2001): Processing package: com.test.thalitest
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,W/BaseAppContext( 2001): Using Auth Proxy for data requests.
,W/BaseAppContext( 2001): Using Auth Proxy for data requests.
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5300): MountEmulatedStorage()
,E/Zygote  ( 5300): v2
I/libpersona( 5300): KNOX_SDCARD checking this for 10041
I/libpersona( 5300): KNOX_SDCARD not a persona
,I/SELinux ( 5300): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5300 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5300): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5300): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5315): MountEmulatedStorage()
I/libpersona( 5315): KNOX_SDCARD checking this for 10012
E/Zygote  ( 5315): v2
I/libpersona( 5315): KNOX_SDCARD not a persona
D/TimaKeyStoreProvider( 5300): TimaSignature is unavailable
,D/ActivityThread( 5300): Added TimaKeyStore provider
,I/ActivityManager( 1013): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5315 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 5315): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5315): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5315): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GassUtils( 2001): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 2001): Found info for package com.test.thalitest in db.
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5315): TimaSignature is unavailable
,D/ActivityThread( 5315): Added TimaKeyStore provider
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/BaseAppContext( 2001): Using Auth Proxy for data requests.
,I/SA      ( 5300): [SSP] onCreated
W/ResourcesManager( 5315): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5315): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/System.out( 4970): Thread-842(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 4970): Thread-842(ApacheHTTPLog):isShipBuild true
,I/System.out( 4970): Thread-842(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4970): Thread-842(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 4970): Thread-842 calls detatch()
,W/Finsky  ( 4970): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,W/BaseAppContext( 2001): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 2001): cleanUpNonGplusAccounts done.
,W/BaseAppContext( 2001): Using Auth Proxy for data requests.
W/BaseAppContext( 2001): Using Auth Proxy for data requests.
,I/SA      ( 5300): [TPM] There is no property file
,I/SA      ( 5300): [SCU] isHaveSA() - false
,I/SA      ( 5300): [TPM] getModelProperty : null
I/SA      ( 5300): [TPM] getCSCProperty : null
I/MultiDex( 5315): VM with version 2.1.0 has multidex support
I/MultiDex( 5315): install
I/MultiDex( 5315): VM has multidex support, MultiDex support library is disabled.
,I/SA      ( 5300): [DM] FLOATING AMOLED FEATURE: true
,I/SA      ( 5300): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5300): [DM] TFT FEATURE: false
,I/SA      ( 5300): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 5300): [DM] init START
,W/BaseAppContext( 2001): Using Auth Proxy for data requests.
,I/SA      ( 5300): [DM] This device is not a Vodafone
,V/JNIHelp ( 5315): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourceType( 5300): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 5300): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 5300): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 5300): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 5300): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 5300): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 5300): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 5300): No package identifier when getting value for resource number 0x00000000,
,W/ResourceType( 5300): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75),
,W/ResourceType( 5300): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 5300): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 5300): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 5300): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 5300): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 5300): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 5300): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 5300): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 5300): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 5300): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 5300): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 5300): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5300): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5300): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 5300): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5300): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 5300): [SCU] isHaveSA() - false
I/SA      ( 5300): support phone number id : false
I/SA      ( 5300): [DM] Supports Ref Jpn : true
,I/SA      ( 5300): [DM] init END
I/SA      ( 5300): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 5300): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
,I/ActivityManager( 1013): Killing 3841:com.android.providers.calendar/u0a42 (adj 15): empty #31
,W/GAV2    ( 5121): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityThread( 5315): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5315): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@51d314: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5315): Installed default security provider GmsCore_OpenSSL
,I/Icing   ( 2001): Internal init done: storage state 0
,D/ChimeraCfgMgr( 5315): Reading stored module config
,I/Icing   ( 2001): Post-init done
,I/Icing   ( 2001): updateResources: need to parse f{com.google.android.gms},
,D/ChimeraCfgMgr( 5315): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/libprocessgroup( 1013): failed to open /acct/uid_10042/pid_3841/cgroup.procs: No such file or directory
,V/AlarmManager( 1013): waitForAlarm result :4
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,I/iu.UploadsManager( 2001): End new media; added: 0, uploading: 0, time: 38 ms
,D/NativeLibraryUtils( 5315): Install completed successfully. count=14 extracted=0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/CAR.SERVICE( 5315): Connecting to CarCallService...
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5354): MountEmulatedStorage(),
E/Zygote  ( 5354): v2
I/libpersona( 5354): KNOX_SDCARD checking this for 10100
I/libpersona( 5354): KNOX_SDCARD not a persona
,I/SELinux ( 5354): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5354 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 5354): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5354): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Killing 4461:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,W/GAV2    ( 5121): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/UpdateIcingCorporaServi( 4839): UpdateCorporaTask done [took 741 ms] updated apps [took 741 ms] 
,D/TimaKeyStoreProvider( 5354): TimaSignature is unavailable
,D/ActivityThread( 5354): Added TimaKeyStore provider
,I/art     ( 5315): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5315): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/CAR.SERVICE( 5315): com.google.android.projection.gearhead isn't installed.
,I/ActivityManager( 1013): Killing 4617:com.google.android.gm/u0a101 (adj 15): empty #31
,D/PackageIntentReceiver( 5354): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5354): Not GearManger package! 
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/CAR.TEL.Service( 5315): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5315): Creating a new PhoneAdapter instance
,E/Zygote  ( 5375): MountEmulatedStorage()
I/libpersona( 5375): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5375): v2
I/libpersona( 5375): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5375 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/ActivityManager( 1013): Killing 4325:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,I/SELinux ( 5375): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
W/AccountFeatureHelper( 5121): Write apps_features disabled false
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
I/SELinux ( 5375): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ActivityManager( 1013): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5315): setListener: com.google.android.gms.car.dn@e0544f3
,E/SELinux ( 5375): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5315): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5315): Starting CarCallService with initial phone null
,W/art     ( 2001): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 112.730ms
,D/TimaKeyStoreProvider( 5375): TimaSignature is unavailable
,D/ActivityThread( 5375): Added TimaKeyStore provider
,W/libprocessgroup( 1013): failed to open /acct/uid_10150/pid_4461/cgroup.procs: No such file or directory
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/libprocessgroup( 1013): failed to open /acct/uid_10101/pid_4617/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10040/pid_4325/cgroup.procs: No such file or directory
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/CAR.SERVICE( 5315): Package validated; name: com.android.vending
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5394): MountEmulatedStorage(),
I/libpersona( 5394): KNOX_SDCARD checking this for 1000
,E/Zygote  ( 5394): v2
,I/libpersona( 5394): KNOX_SDCARD not a persona
I/SELinux ( 5394): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5394 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 4269:com.google.android.music:main/u0a111 (adj 15): empty #31
,I/SELinux ( 5394): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5394): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/Finsky  ( 4970): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/TimaKeyStoreProvider( 5394): TimaSignature is unavailable
,D/ActivityThread( 5394): Added TimaKeyStore provider
,W/GAV2    ( 5121): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager( 1013): Killing 4787:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,D/AcmsPackageEventListener( 5394): Received: android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ContextImpl( 5394): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/AcmsService( 5394): Enter Oncreate
,D/AcmsServiceMonitor( 5394): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,D/AcmsService( 5394): creating AcmsCore
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/AcmsCore( 5394): AcmsCore.getAcmsCore() - Enter
,D/AcmsCore( 5394): AcmsCore
,W/libprocessgroup( 1013): failed to open /acct/uid_10111/pid_4269/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10142/pid_4787/cgroup.procs: No such file or directory
,D/AcmsCore( 5394): init
,D/AcmsCore( 5394): Looper handler is not null
D/AcmsCore( 5394): Post to AcmsCoreHandler
,D/AcmsServiceMonitor( 5394): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5394): Incrementing - Counter value: 1
,D/AcmsCore( 5394): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsCertificateMngr( 5394): AcmsCertificateMngr
,D/AcmsService( 5394): onStartCommand
,D/AcmsService( 5394): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 5394): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 5394): Incrementing - Counter value: 2
D/AcmsService( 5394): Incremented Counter Value : onStartCommand
,D/AcmsRevocationMngr( 5394): AcmsRevocationMngr
,D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityThread( 5394): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsService( 5394): Inside handle Intent
D/AcmsService( 5394): App added - package name: com.test.thalitest
D/AcmsCore( 5394): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5394): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5394): Incrementing - Counter value: 3
D/AcmsCore( 5394): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 5394): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 5394): Decrementing - Counter value: 2
,I/splitIntent( 1013): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/KeyguardViewMediator( 1177): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1177): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1177): *** Keyguard wallpaper service already unbounded
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2001): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2001): Module APK com.google.android.play.games already loaded
,I/splitIntent( 1013): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1013): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1013): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1013): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1837): callingUid 10012, callindPid: 1837
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/MDM     ( 1837): [250] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2001): Restart initialization of location,
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1837): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 28189(1529KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/40MB, paused 2.474ms total 150.495ms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1837): No location to return for getLastLocation()
,W/FusedLocationProvider( 1837): location=null
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 4970): Thread-843(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 4970): Thread-843(ApacheHTTPLog):isShipBuild true
I/System.out( 4970): Thread-843(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4970): Thread-843(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 4970): Thread-843 calls detatch()
,W/Finsky  ( 4970): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/ActivityManager( 1013): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/Mms/MmsApp( 5032):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5032): [start]    fillCache consume time = 1895.529114
,D/Mms/ComposeMessageFragment( 5032): fillCache, easy = false
,D/Finsky  ( 4970): [1] DailyHygiene.access$600: Logging device features
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1013): waitForAlarm result :4
,D/Finsky  ( 4970): [1] DailyHygiene.reschedule: Scheduling new run in 92 minutes (failures=3)
,D/ActivityManager( 1013): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/DeviceConnectionService( 1837): client connected with version: 8296000
,D/Finsky  ( 4970): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 4970): [865] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AbsListView( 5032): Get MotionRecognitionManager
,D/MotionRecognitionService( 1013):  ssp status : false
,D/Finsky  ( 4970): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/System.out( 4970): (HTTPLog)-Static: isSBSettingEnabled false
D/Mms/ComposeMessageFragment( 5032): [end]    fillCache consume time = 115.863125
D/Finsky  ( 4970): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/EnterpriseController(  276): uids 10028
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 10028
,I/ActivityManager( 1013): Killing 4901:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,I/ActivityManager( 1013): Killing 3817:com.google.android.talk/u0a104 (adj 15): empty #32,
,D/Mms/BubbleViewCache( 5032): fillCache bubble = 1
,I/Icing   ( 2001): Indexing 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD from com.google.android.googlequicksearchbox
,D/Icing   ( 2001): Loaded CLD2 Version V2.0 - 20141016
,D/AcmsKeyStoreHelper( 5394):  getKeyStoreForApplication Enter
,I/Icing   ( 2001): Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
,I/Icing   ( 2001): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,I/AcmsKeyStoreHelper( 5394): Key Store exist
I/AcmsKeyStoreHelper( 5394): Hence loading the keystore file
,W/libprocessgroup( 1013): failed to open /acct/uid_10069/pid_4901/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10104/pid_3817/cgroup.procs: No such file or directory
,D/AcmsKeyStoreHelper( 5394):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5394): getKeyStoreForApplication success 
D/AcmsCore( 5394): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5394): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5394): Decrementing - Counter value: 1
D/AcmsCore( 5394): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5394): This is NOT a valid MirrorLink app
D/AcmsCore( 5394): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5394): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5394): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5394): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5394): getSvcCounter - Counter value: 0
,D/AcmsService( 5394): Enter onDestroy
I/AcmsService( 5394): cleanUp(): inside service clean up
D/AcmsCore( 5394): AcmsCore: inside DeInit
D/AcmsCore( 5394): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5394): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5394): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5394): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5394): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 5394): getSvcCounter - Counter value: 0
,D/AcmsService( 5394): killing acms process
I/Process ( 5394): Sending signal. PID: 5394 SIG: 9
,I/ActivityManager( 1013): Process ACMS.Process (pid 5394)(adj 0) has died(92,1168)
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Icing   ( 2001): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1013): waitForAlarm result :8
,D/SSRM:n  ( 1013): SIOP:: AP = 350
,I/ActivityManager( 1013): Waited long enough for: ServiceRecord{3d964795 u0 com.samsung.android.MtpApplication/.MtpService}
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms,
,E/SMD     (  288): DCD OFF
,D/CAR.SERVICE( 5315): mConnectedToCar = false, abort
,E/ActivityThread( 5315): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@84a217b that was originally bound here
E/ActivityThread( 5315): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@84a217b that was originally bound here
E/ActivityThread( 5315): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5315): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5315): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5315): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5315): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5315): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5315): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5315): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5315): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5315): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5315): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5315): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5315): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5315): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 5315): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 5315): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 5315): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5315): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5315): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5315): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5315): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5315): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5315): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 5315): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1871eb62 that was originally bound here
E/ActivityThread( 5315): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1871eb62 that was originally bound here
E/ActivityThread( 5315): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5315): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5315): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5315): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5315): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5315): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5315): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5315): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5315): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5315): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5315): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5315): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5315): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 5315): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 5315): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 5315): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5315): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5315): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5315): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5315): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5315): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5315): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1013): Unbind failed: could not find connection for android.os.BinderProxy@2e08728f
,I/ActivityManager( 1013): Killing 4932:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_4932/cgroup.procs: No such file or directory
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1013): waitForAlarm result :8
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
,D/BatteryService( 1013): stay LED for fully charged,
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1013): Plugged,
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1013): [PWL] Off : 15s ago,
,D/PackageManager( 1013): [MSG] MCS_UNBIND
,I/ActivityManager( 1013): Killing 4821:com.samsung.aasaservice/1000 (adj 15): empty #31
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_4821/cgroup.procs: No such file or directory
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1013): Waited long enough for: ServiceRecord{a603a79 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/SSRM:n  ( 1013): SIOP:: AP = 320
,E/SMD     (  288): DCD OFF
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/IcingInternalCorpora( 2001): getNumBytesRead when not calculated.
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 2
,V/AlarmManager( 1013): waitForAlarm result :4
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,D/NtpTrustedTime( 1013): forceRefresh() from cache miss
,D/EnterpriseController(  276): uids 1000
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 1000
,I/BackgroundCompactionService( 1013): onStart. jobID=801
D/EnterpriseController(  276): uids 1000
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
,D/Netd    (  276): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1013): forceRefresh Fail.
,I/BackgroundCompactionService( 1013): onStart done. jobID=801
,I/BackgroundCompactionService( 1013): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1013): compact_memory command done
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/Finsky  ( 4970): [855] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4970): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1013): waitForAlarm result :8
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1013): waitForAlarm result :4
,V/AlarmManager( 1013): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1013): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1013): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1013): SIOP:: AP = 300
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PowerManagerService( 1013): [PWL] Off : 30s ago
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1013): stay LED for fully charged
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
,I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 290,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 290
,I/PowerManagerService( 1013): [PWL] Off : 50s ago
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 3,
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/FactoryTest( 4713): Not factory mode
,D/FactoryTest( 4713): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4713): DRIVER_TIME_OUT 60s lapsed,
D/MTPRx   ( 4713): still no open session command from host, so toast
W/ContextImpl( 4713): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4713): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 ,
,I/Timeline( 4713): Timeline: Activity_launch_request id:com.android.settings time:109314
E/PersonaManagerService( 1013): inState():  stateMachine is null !!,
I/PersonaManagerService( 1013): PersonaId don't exist,
I/ActivityManager( 1013): do not start freezing screen for locked container getKeyguardshowstate = false,
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1013): mDVFSHelper.acquire(),
,D/FocusedStackFrame( 1013): Set to : 0
,V/ActivityManager( 1013): Display changed displayId=0,
,D/PersonaManager( 1013): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1013): Focused application set to: xxxx
,D/InputDispatcher( 1013): Focus left window: 1467
,E/MTPRx   ( 4713): started activity for popup
,D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
,D/WindowOrientationListener( 1013):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,W/ResourcesManager( 4713): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 4713): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 4713): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4713): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4713): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4713): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 4713): PREF_DONT_ASK_AGAIN : true
,D/FocusedStackFrame( 1013): Set to : 0
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1013): Focused application set to: xxxx
,D/InputDispatcher( 1013): Focus entered window: 1467
,D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1013): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1013): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1d1d9595 attribute=android.view.inputmethod.EditorInfo@2f6a46aa, token = android.os.BinderProxy@1f3ea764
,D/SamsungIME( 1778): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/SettingsReceiverActivity( 4713): dev.kiessupport is : TRUE
,D/PhoneWindow( 4713): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 4713): *FMB* installDecor flags : 8388610
,E/SMD     (  288): DCD OFF
,W/ActivityManager( 1013): mDVFSHelper.release(),
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 290,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/WindowOrientationListener( 1013):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 290,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
D/BatteryService( 1013): stay LED for fully charged
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged,
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1013): [PWL] Off : 75s ago
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 4,
,V/AlarmManager( 1013): waitForAlarm result :4,
,D/NtpTrustedTime( 1013): forceRefresh() from cache miss
,D/EnterpriseController(  276): uids 1000
,D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  276): uids 1000
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1013): forceRefresh Fail.
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,V/AlarmManager( 1013): waitForAlarm result :8
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1013): [PWL] Off : 105s ago
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  288): DCD OFF,
,I/ClearcutLoggerApiImpl( 1837): disconnect managed GoogleApiClient
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for fully charged
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1013): !@Sync 5,
,V/AlarmManager( 1013): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,I/PowerManagerService( 1013): [PWL] Off : 140s ago,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1013): !@Sync 6,
,V/AlarmManager( 1013): waitForAlarm result :4
D/NtpTrustedTime( 1013): forceRefresh() from cache miss
,D/EnterpriseController(  276): uids 1000
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  276): uids 1000,
,D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 1000
D/NtpTrustedTime( 1013): forceRefresh Fail.
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1837): Vacuum at: now=1457361597459 tag=VacuumService
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1013): waitForAlarm result :8
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/Watchdog( 1013): !@Sync 7,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1013): [PWL] Off : 180s ago,
D/SSRM:n  ( 1013): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1013): !@Sync 8,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for fully charged
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
,I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1013): [PWL] Off : 225s ago
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1013): !@Sync 9,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,I/TLC_TIMA_PKM_initialize( 1013): initializing...
,D/TimaService( 1013): TIMA: TimaService scheduler is intialized. 
I/TLC_TIMA_PKM_initialize( 1013): root = /firmware/image, root_strlen = 15
D/TimaService( 1013): TIMA: checkEvent, operation: 50000 subject: 10000
I/TLC_TIMA_PKM_initialize( 1013): process = tima_pkm, process_strlen = 8
D/TimaService( 1013): TimaServiceHandler.handleMessage what =1
I/TZ: qc_tlc_communication( 1013): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1013): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1013): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1013): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1013): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1013): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1013): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1013): Loaded image: APP id = 9
,I/TZ: qc_tlc_communication( 1013): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded,
,I/TLC_TIMA_PKM_initialize( 1013): Trustlet response is completed
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,I/TLC_TIMA_PKM_measure_kernel( 1013): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1013): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1013): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1013): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1013): !@Sync 10,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 ,	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1013): [PWL] Off : 275s ago
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1013): waitForAlarm result :8,
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter; callingUser = 0; userId(target) = 0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 5561): MountEmulatedStorage(),
I/libpersona( 5561): KNOX_SDCARD checking this for 10104
E/Zygote  ( 5561): v2
I/libpersona( 5561): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.google.android.talk for service com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter: pid=5561 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
I/SELinux ( 5561): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5561): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5561): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5561): TimaSignature is unavailable
,D/ActivityThread( 5561): Added TimaKeyStore provider
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ResourcesManager( 5561): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/Babel   ( 5561): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5561): MmsConfig.loadMmsSettings
,I/Babel   ( 5561): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 5561): MmsConfig.loadFromDatabase
,E/Babel   ( 5561): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5561): MmsConfig.loadFromResources
,E/Babel   ( 5561): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5561): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 5561): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_StickerModule( 5561): App launched.
,I/Babel_StickerModule( 5561): Sticker update initiated. last:1456825783062 empty:false
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/art     ( 5561): Suspending all threads took: 16.860ms
,W/ResourcesManager( 5561): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5561): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5561): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5561): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5561): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b75307: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5561): Installed default security provider GmsCore_OpenSSL
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  281): getCameraInfo: X
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  281): getCameraInfo: X
,W/VideoCapabilities( 5561): Unrecognized profile 2130706433 for video/avc
,I/art     ( 5561): Note: end time exceeds epoch: 
,W/AudioCapabilities( 5561): Unsupported mime audio/evrc
,W/AudioCapabilities( 5561): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5561): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5561): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5561): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5561): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5561): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5561): Unsupported mime audio/evrc
,W/VideoCapabilities( 5561): Unsupported mime video/wvc1
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/VideoCapabilities( 5561): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5561): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5561): Unsupported mime video/wvc1
,W/VideoCapabilities( 5561): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5561): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5561): Unsupported mime video/x-ms-wmv8,
,W/VideoCapabilities( 5561): Unsupported mime video/mp43
,W/VideoCapabilities( 5561): Unsupported mime video/sorenson
,W/VideoCapabilities( 5561): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5561): Unsupported profile 4 for video/mp4v-es
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5561): Creating RTCS,
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5561): Destroying RTCS
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/ActivityManager( 1013): Killing 4342:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,W/libprocessgroup( 1013): failed to open /acct/uid_10044/pid_4342/cgroup.procs: No such file or directory,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1013): !@Sync 11,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null,
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1837): Explicit concurrent mark sweep GC freed 46761(2MB) AllocSpace objects, 21(336KB) LOS objects, 39% free, 12MB/21MB, paused 1.430ms total 82.255ms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 4970): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  276): uids 10028
,D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 10028
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
E/Watchdog( 1013): !@Sync 12
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1013): waitForAlarm result :8,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1013): [PWL] Off : 330s ago,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 13,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 14,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1013): [PWL] Off : 390s ago,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 15,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/bootchecker(  313): bootchecker wake up!!,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 16,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for fully charged
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1013): [PWL] Off : 455s ago
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 17,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 18,
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1013): [PWL] Off : 525s ago,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/Atfwd_Daemon(  316): Stop the daemon....,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 19,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,D/TimaService( 1013): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1013): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1013): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/TLC_TIMA_PKM_measure_kernel( 1013): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1013): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1013): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1013): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1013): !@Sync 20,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 21,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1013): [PWL] Off : 600s ago,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 4970): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  276): uids 10028
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 10028
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 22,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 23,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1013): [PWL] Off : 681s ago,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 24,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for fully charged
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,E/SMD     (  288): DCD OFF
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 25,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for fully charged
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for fully charged
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for fully charged,
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 26,
,V/AlarmManager( 1013): waitForAlarm result :8,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for fully charged
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1013): [PWL] Off : 766s ago,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 27,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 28,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 29,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1013): [PWL] Off : 856s ago
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/TimaService( 1013): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1013): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1013): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1013): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1013): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1013): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1013): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1013): !@Sync 30
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 31,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator,
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null,
W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 4970): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  276): uids 10028
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 10028
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 32,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1013): [PWL] Off : 951s ago,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 33,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1013): !@Sync 34,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 35,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 36,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1013): [PWL] Off : 1051s ago
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 37,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 38,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for fully charged
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for fully charged
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for fully charged
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 39
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1013): [PWL] Off : 1156s ago,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 1013): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1013): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1013): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1013): User[0] Flushing usage stats to disk,
,I/ApplicationUsage( 1013): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1013): Updating Usage Statistics in DB @ 1457362614819
,I/ApplicationUsage( 1013): Done Updating Usage Statistics in DB @ 1457362614823
,I/TLC_TIMA_PKM_measure_kernel( 1013): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1013): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1013): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1013): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1013): !@Sync 40
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for fully charged
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
,I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for fully charged
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
,I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 41,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for fully charged
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 4970): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  276): uids 10028
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 10028
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for fully charged
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1013): !@Sync 42,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1013): !@Sync 43,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,I/PowerManagerService( 1013): [PWL] Off : 1266s ago,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1013): !@Sync 44,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1013): !@Sync 45,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1013): !@Sync 46,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/Watchdog( 1013): !@Sync 47,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1013): [PWL] Off : 1381s ago,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,TIME-OUT KILL (timeout was 1400000ms),E/Watchdog( 1013): !@Sync 48
D/AndroidRuntime( 6058): 
D/AndroidRuntime( 6058): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6058): CheckJNI is OFF
D/AndroidRuntime( 6058): readGMSProperty: start
D/AndroidRuntime( 6058): readGMSProperty: already setted!!
D/AndroidRuntime( 6058): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6058): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6058): readGMSProperty: end
D/AndroidRuntime( 6058): addProductProperty: start
E/AffinityControl( 6058): AffinityControl: registerfunction enter
D/AndroidRuntime( 6058): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1013): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1013): START PACKAGE DELETE: observer{142186543}
D/PackageManager( 1013): pkg{<packageName>}
D/PackageManager( 1013): user{0}
D/PackageManager( 1013): caller{2000}
D/PackageManager( 1013): flags{3}
D/PersonaManagerService( 1013): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1013): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1013): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 1013): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1013): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1013): !@killApplicatoin: 10155, uninstall pkg
D/PackageManagerService( 1013): deletePackage- pkg:com.test.thalitest, edmuserId:0
I/ActivityManager( 1013): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
D/PackageManagerService( 1013): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1013): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1013): getApplicationUninstallationEnabled :  enabled true
W/PackageSettings( 1013): Skipping PackageSetting{83cd73d com.example.hello/10174} due to missing metadata
I/ActivityManager( 1013): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
W/ActivityManager( 1013): CustomStartingWindow se packge removed so remove capture also
I/art     ( 3529): Explicit concurrent mark sweep GC freed 2583(158KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 6MB/11MB, paused 704us total 29.828ms
I/InputReader( 1013): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1778): mOCRHelper is null
W/GeofencerStateMachine( 1837): Ignoring removeGeofence because network location is disabled.
I/art     ( 4839): Explicit concurrent mark sweep GC freed 292(23KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 729us total 57.386ms
I/art     ( 4659): Explicit concurrent mark sweep GC freed 23593(1198KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 6.340ms total 60.826ms
I/art     ( 2001): Explicit concurrent mark sweep GC freed 2435(118KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 13MB/17MB, paused 1.100ms total 85.313ms
I/KLMS-2.5.183: ( 3350): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 07 16:00:59 GMT+01:00 2016
D/ActivityManager( 1013): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/RegisteredComponentCache( 1430): Collect Tech packages for Knox
D/PersonaManager( 1430): isKioskContainerExistOnDevice
I/KLMS-2.5.183: ( 3350): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1013): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1013): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6071): MountEmulatedStorage()
E/Zygote  ( 6071): v2
I/libpersona( 6071): KNOX_SDCARD checking this for 10094
I/libpersona( 6071): KNOX_SDCARD not a persona
I/SELinux ( 6071): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6071): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6071): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6071 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3350): KLMSIntentService(): onCreate()
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3350): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/art     (  308): Explicit concurrent mark sweep GC freed 8699(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 24.090ms
E/SMD     (  288): DCD OFF
I/KLMS-2.5.183: ( 3350): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/TimaKeyStoreProvider( 6071): TimaSignature is unavailable
D/ActivityThread( 6071): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3350): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.183: ( 3350): KLMSIntentService(): PACKAGE_REMOVED
D/SecContentProvider2( 1013): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1013): mCursor = null
I/KLMS-2.5.183: ( 3350): KLMSIntentService(): listeningToPackageRemoved().START
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 28.072ms
I/KLMS-2.5.183: ( 3350): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 603us total 17.312ms
E/Zygote  ( 6086): MountEmulatedStorage()
I/libpersona( 6086): KNOX_SDCARD checking this for 10044
E/Zygote  ( 6086): v2
I/libpersona( 6086): KNOX_SDCARD not a persona
I/SELinux ( 6086): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6086 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux ( 6086): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6086): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PersonaManager( 1430): isKioskContainerExistOnDevice
D/TimaKeyStoreProvider( 6086): TimaSignature is unavailable
D/ActivityThread( 6086): Added TimaKeyStore provider
D/RCPManagerService( 1013): PackageReceiver onReceive()
I/HarmonyEASService( 1013): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/KnoxMUMContainerPolicy( 1013): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1013): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1013): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1013): DBIntegrity::getInstance - New instance created
I/KLMS-2.5.183: ( 3350): KLMSIntentService(): listeningToPackageRemoved().END
D/OTPFW   ( 1013): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
I/OTPFW   ( 1013): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1013): ProvisionData::getAllEntries Table is empty
E/Zygote  ( 6101): MountEmulatedStorage()
E/Zygote  ( 6101): v2
I/libpersona( 6101): KNOX_SDCARD checking this for 10149
I/libpersona( 6101): KNOX_SDCARD not a persona
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 1013): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 1013): uID is 10155
D/JobSchedulerService( 1013): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1013): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - end - null
I/SELinux ( 6101): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/elm:15183( 6071): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 6071): ELMEngine.ELMEngine( context ).
I/SELinux ( 6101): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6101 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6101): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/AlarmManagerEXT( 1013): com.test.thalitest(10155) is removed.
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/SSRM:aZ ( 1013): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1013): uID is 10155
V/EnterpriseBillingPolicy( 1013): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - end - null
D/RegisteredServicesCache( 1430): empty dynamic service
D/elm:15183( 6071): MDMBridge.setEnterpriseBridge()
D/EnterpriseDeviceManagerService( 1013): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1013): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1013): no available spell checker services found
D/TimaKeyStoreProvider( 6101): TimaSignature is unavailable
D/ActivityThread( 6101): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3350): KLMSIntentService(): onDestroy()
E/SQLiteLog( 4659): (10) POSIX Error : 11 SQLite Error : 3850
E/SQLiteLog( 4659): (10) POSIX Error : 11 SQLite Error : 3850
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SQLiteLog( 4659): (10) POSIX Error : 11 SQLite Error : 3850
D/ActivityManager( 1013): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ResourcesManager( 6086): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ResourcesManager( 6086): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ResourcesManager( 6086): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
W/ResourcesManager( 6086): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6086): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6086): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6086): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6086): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/elm:15183( 6071): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/SQLiteLog( 4659): (284) automatic index on crash_info_summary(package_name_touched)
D/elm:15183( 6071): ElmAgentService : onCreate()
E/Zygote  ( 6119): MountEmulatedStorage()
I/libpersona( 6119): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6119): v2
I/libpersona( 6119): KNOX_SDCARD not a persona
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 6119): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/elm:15183( 6071): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
I/ActivityManager( 1013): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6119 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/elm:15183( 6071): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6071): MDMBridge.getInstance()
D/elm:15183( 6071): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 6071): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux ( 6119): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/art     ( 4659): Explicit concurrent mark sweep GC freed 1134(55KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 1.023ms total 55.128ms
E/SELinux ( 6119): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BadgeProvider( 5211): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5211): sendNotify, [notify] : null
D/BadgeProvider( 5211): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5211): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5211): update, [UpdateCount] : 1
D/ThemeInfoUtil( 6101): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 6101): isCurrentFestival = false
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ContextImpl( 3722): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
D/elm:15183( 6071): ElmAgentService : onDestroy().
D/TimaKeyStoreProvider( 6119): TimaSignature is unavailable
D/ActivityThread( 6119): Added TimaKeyStore provider
D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/RCPManager( 4916):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1013):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1013): queryAllProviders():  providerCallBack is not register for 0
I/TapandpayWidget:TapandpayAppWidgetProvider( 5083): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 5083): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils( 5083): Clear T&P info.
D/TapandpayWidget:TapandpayAppWidgetProvider( 5083): Widget is not attached.
I/art     ( 1013): Explicit concurrent mark sweep GC freed 40952(4MB) AllocSpace objects, 188(2MB) LOS objects, 33% free, 27MB/41MB, paused 7.633ms total 423.145ms
D/AASAservice-UpdateReceiver( 6119): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/System.err( 6119): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6119): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6119): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6119): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6119): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6119): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6119): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6119): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6119): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6119): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6119): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6119): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6119): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6139): MountEmulatedStorage()
E/Zygote  ( 6139): v2
I/libpersona( 6139): KNOX_SDCARD checking this for 10160
I/libpersona( 6139): KNOX_SDCARD not a persona
I/SELinux ( 6139): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6139): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6139): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6139 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 4861:com.google.android.partnersetup/u0a15 (adj 15): empty #31
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/PCWCLIENTTRACE_PushUtil( 5052): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5052): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5052): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5052): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/libpersona( 6148): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6148): MountEmulatedStorage()
I/libpersona( 6148): KNOX_SDCARD not a persona
E/Zygote  ( 6148): v2
I/SELinux ( 6148): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6148): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6148): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6139): TimaSignature is unavailable
D/ActivityThread( 6139): Added TimaKeyStore provider
I/ActivityManager( 1013): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6148 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 5071:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
W/ResourceType( 1013): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/ResourcesManager( 6139): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
D/TimaKeyStoreProvider( 6148): TimaSignature is unavailable
D/ActivityThread( 6148): Added TimaKeyStore provider
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 6169): MountEmulatedStorage()
I/libpersona( 6169): KNOX_SDCARD checking this for 10035
E/Zygote  ( 6169): v2
I/libpersona( 6169): KNOX_SDCARD not a persona
I/SELinux ( 6169): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6169): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6169 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6169): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/NearbySource( 6086): Nearby Source Create!
I/ActivityManager( 1013): Killing 5104:com.policydm/1000 (adj 15): empty #31
D/NearbyContext( 6086): Nearby Context Create!
D/[0]UMC:UMCContentProvider( 6139): @onCreate
D/Launcher.Model( 1467): reloadBadges entered.
D/[0]UMC:Core( 6139): onCreate(): 
D/[0]UMC:Core( 6139): @isManagedProfileUser
D/[0]UMC:Core( 6139): userId: 0
D/[0]UMC:Core( 6139): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 6139): userInfo.isManagedProfile() : false
D/TimaKeyStoreProvider( 6169): TimaSignature is unavailable
D/ActivityThread( 6169): Added TimaKeyStore provider
W/ContextImpl( 6148): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1013): startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
D/PackageManager( 1013): delete codoeFile: 
W/ResourcesManager( 1013): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1013): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1013): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/AASAuninstall( 1013): userId = 0, info.removedAppID = -1, info.uid = 10155, packageName = com.test.thalitest
I/AASA_removePackage( 1013): UID=10155 Target=com.test.thalitest
E/Zygote  ( 6184): MountEmulatedStorage()
E/Zygote  ( 6184): v2
I/libpersona( 6184): KNOX_SDCARD checking this for 1000
I/libpersona( 6184): KNOX_SDCARD not a persona
I/SELinux ( 6184): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 6184): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux ( 6184): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6184 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/PackageManager( 1013): result of delete: 1{142186543}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ContextImpl( 6086): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/[0]UMC:DeviceInfo( 6139): USA==US==
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1013): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1013): onPackageRemoved : com.test.thalitest
D/SLinkSource( 6086): Samsung link source created
W/libprocessgroup( 1013): failed to open /acct/uid_10015/pid_4861/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_5071/cgroup.procs: No such file or directory
D/AndroidRuntime( 6058): Shutting down VM
D/TimaKeyStoreProvider( 6184): TimaSignature is unavailable
D/ActivityThread( 6184): Added TimaKeyStore provider
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_5104/cgroup.procs: No such file or directory
I/ActivityManager( 1013): Killing 5138:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
E/SPPClientService( 6169): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6169): [PushClientApplication] Push log off : This is Ship build version
I/SA      ( 5300): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 5300): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10155 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager( 1013): Killing 5032:com.android.mms/u0a46 (adj 15): empty #31
D/ActivityManager( 1013): startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
D/AcmsPackageEventListener( 6184): Received: android.intent.action.PACKAGE_REMOVED
D/ActivityManager( 1013): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/SPPClientService( 6169): PushLog.txt file is not deleted.
D/SPPClientService( 6169): PushLog.txt file is not deleted.
D/SPPClientService( 6169): ============PushLog. stop!
D/ActivityManager( 1013): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 6184): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1013): failed to open /acct/uid_10010/pid_5138/cgroup.procs: No such file or directory
E/Zygote  ( 6207): MountEmulatedStorage()
E/Zygote  ( 6207): v2
I/libpersona( 6207): KNOX_SDCARD checking this for 1000
I/libpersona( 6207): KNOX_SDCARD not a persona
I/SELinux ( 6207): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6207 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6207): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6207): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/USER_AGENT( 6139): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
D/[0]UMC:AdminManager( 6139): init - start
D/AcmsService( 6184): Enter Oncreate
D/AcmsServiceMonitor( 6184): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6184): creating AcmsCore
D/AcmsCore( 6184): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6184): AcmsCore
D/AcmsCore( 6184): init
D/AcmsCore( 6184): Looper handler is not null
D/AcmsCore( 6184): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6184): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6184): Incrementing - Counter value: 1
D/AcmsCore( 6184): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 6184): onStartCommand
D/AcmsService( 6184): Action: android.intent.action.PACKAGE_REMOVED
D/AcmsServiceMonitor( 6184): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6184): Incrementing - Counter value: 2
D/AcmsService( 6184): Incremented Counter Value : onStartCommand

```
