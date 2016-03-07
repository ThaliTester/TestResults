#### Test 61362366a48397d_thali08_samsung-SM-A300FU Logs


```
--------- beginning of system
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
--------- beginning of main
E/Zygote  ( 4008): MountEmulatedStorage()
E/Zygote  ( 4008): v2
I/SELinux ( 4008): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/AMMetaDataParserService( 3854): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
I/SELinux ( 4008): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4008): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/libpersona( 4008): KNOX_SDCARD checking this for 1000
I/libpersona( 4008): KNOX_SDCARD not a persona
I/ActivityManager( 1022): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4008 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1022): Killing 3195:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
W/libprocessgroup( 1022): failed to open /acct/uid_10082/pid_3075/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3092/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3121/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_10088/pid_3139/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_10068/pid_1615/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_10146/pid_3161/cgroup.procs: No such file or directory
W/System.err( 3976): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 3976): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3976): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3976): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 3976): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 3976): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3976): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
D/TimaKeyStoreProvider( 4008): TimaSignature is unavailable
E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ActivityThread( 4008): Added TimaKeyStore provider
I/GFX raster( 3854): took 0.670417ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d14428 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8add288 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3854): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3854): took 0.845730ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d38a00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d37f28 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3854): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
W/ResourcesManager( 3829): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3829): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/BaseAppContext( 2121): Using Auth Proxy for data requests.
W/ResourcesManager( 3829): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1022): failed to open /acct/uid_10088/pid_3195/cgroup.procs: No such file or directory
I/Icing   ( 2121): updateResources: need to parse f{com.google.android.gms}
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SystemUpdateService( 2121): onDestroy
E/BaseAppContext( 2121): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
D/StatusChecker( 4008): onReceive : android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3854): took 0.714792ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8add288 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d37f28 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3854): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
I/GFX raster( 3854): took 0.679635ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d37f28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d0b940 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3854): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
I/art     ( 1672): Explicit concurrent mark sweep GC freed 4051(158KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 781us total 25.388ms
I/GAV2    ( 3261): Thread[GAThread,5,main]: No campaign data found.
I/StatusChecker( 4008): onReceive : net.mt.init : DONE
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4043): MountEmulatedStorage()
E/Zygote  ( 4043): v2
I/libpersona( 4043): KNOX_SDCARD checking this for 10113
I/libpersona( 4043): KNOX_SDCARD not a persona
I/SELinux ( 4043): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4043): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1022): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4043 uid=10113 gids={50113, 9997} abi=armeabi-v7a
D/GCM     ( 1834): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/ActivityManager( 1022): Killing 3241:com.policydm/1000 (adj 15): empty #31
E/SELinux ( 4043): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/Process ( 3894): Sending signal. PID: 3894 SIG: 9
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
I/AuthZen ( 2121): Fetching signing key...
E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3854): took 0.631510ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d0b940 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d1ccd0 counterpartCT=4 counterpartW=96 counterparth=96
D/TimaKeyStoreProvider( 4043): TimaSignature is unavailable
W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3241/cgroup.procs: No such file or directory
I/AuthZen ( 2121): Signing key fetched successfully!
D/ActivityThread( 4043): Added TimaKeyStore provider
I/AMMetaDataParserService( 3854): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
W/BaseAppContext( 2121): Using Auth Proxy for data requests.
I/ActivityManager( 1022): Process com.sec.android.app.sns3 (pid 3894)(adj 0) has died(46,647)
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:assistant
I/AMMetaDataParserService( 3854): Resource data:2131034113
I/AMMetaDataParserService( 3854): getResourceName:com.android.contacts:xml/assistant_main
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3854): getResourceTypeNamexml
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
I/GFX raster( 3854): took 0.888749ms for 96*96 texture 0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d51868 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d0c4c8 counterpartCT=4 counterpartW=96 counterparth=96
I/ActivityManager( 1022): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4063 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 4063): MountEmulatedStorage()
E/Zygote  ( 4063): v2
I/libpersona( 4063): KNOX_SDCARD checking this for 10031
I/libpersona( 4063): KNOX_SDCARD not a persona
I/SELinux ( 4063): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/AMMetaDataParserService( 3854): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
I/SELinux ( 4063): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4063): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PCWCLIENTTRACE_AccountAppFacade2_0( 3405): unregister AuthInfo UpdateReceiver v2.0
D/a       ( 2121): Opening database auth.proximity.permit_store...
D/TimaKeyStoreProvider( 4063): TimaSignature is unavailable
D/ActivityThread( 4063): Added TimaKeyStore provider
I/GCoreUlr( 1834): DispatchingService.onCreate()
D/AuthZenTransactionCache( 2121): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2121): Clearing transaction cache
I/PageBuddyNotiSvc( 4043): Intent received : action=android.intent.action.BOOT_COMPLETED
E/SQLiteLog( 2121): (10) POSIX Error : 11 SQLite Error : 3850
W/ContextImpl( 4043): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
I/PageBuddyNotiSvc( 4043): onCreate mCpBitFlag=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4080): MountEmulatedStorage()
E/Zygote  ( 4080): v2
I/libpersona( 4080): KNOX_SDCARD checking this for 10121
I/libpersona( 4080): KNOX_SDCARD not a persona
I/SELinux ( 4080): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4080 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 4080): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4080): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3854): took 0.862500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d51868 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d0c4c8 counterpartCT=4 counterpartW=96 counterparth=96
D/TimaKeyStoreProvider( 4080): TimaSignature is unavailable
D/ActivityThread( 4080): Added TimaKeyStore provider
I/AMMetaDataParserService( 3854): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
W/ResourcesManager( 4080): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4080): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4080): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/GCM     ( 1834): GCM config loaded
W/art     ( 2121): Suspending all threads took: 73.155ms
D/QuickConnect( 4080): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1022): name = scon_is_running
D/SettingsProvider( 1022): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1022): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1022): selectionArgs: false
D/SettingsProvider( 1022): selectionArgs: 10121
D/SecContentProvider( 1022): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1022): ret = -1
W/BackupManagerService( 1022): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
D/QuickConnect( 4080): Utils.setQCRunningSetting - set : 0
I/QuickConnect( 4080): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
I/QuickConnect( 4080): PeriphStartReceiver.onReceive - no need to start
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4100): MountEmulatedStorage()
E/Zygote  ( 4100): v2
I/libpersona( 4100): KNOX_SDCARD checking this for 10127
I/libpersona( 4100): KNOX_SDCARD not a persona
I/SELinux ( 4100): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4100 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 4100): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4100): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Killing 3333:com.sec.esdk.elm/u0a90 (adj 15): empty #31
E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3854): took 0.755104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d16518 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d0c4c8 counterpartCT=4 counterpartW=96 counterparth=96
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 4100): TimaSignature is unavailable
V/GLSActivity( 1834): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityThread( 4100): Added TimaKeyStore provider
V/GLSActivity( 1834): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Zygote  ( 4116): MountEmulatedStorage()
E/Zygote  ( 4116): v2
I/libpersona( 4116): KNOX_SDCARD checking this for 1000
I/libpersona( 4116): KNOX_SDCARD not a persona
I/ActivityManager( 1022): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4116 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 4116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Killing 3363:com.fmm.dm/1000 (adj 15): empty #31
I/SELinux ( 4116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/AMMetaDataParserService( 3854): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
E/SELinux ( 4116): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/GLSActivity( 1834): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 4040): 
D/AndroidRuntime( 4040): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4040): CheckJNI is OFF
D/AndroidRuntime( 4040): readGMSProperty: start
D/AndroidRuntime( 4040): readGMSProperty: already setted!!
D/AndroidRuntime( 4040): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4040): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4040): readGMSProperty: end
D/AndroidRuntime( 4040): addProductProperty: start
I/art     (  307): Explicit concurrent mark sweep GC freed 8742(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 629us total 33.071ms
I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 17.225ms
I/ActivityManager( 1022): Killing 3385:com.sec.factory.camera/1000 (adj 15): empty #31
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 21.459ms
D/TimaKeyStoreProvider( 4116): TimaSignature is unavailable
W/ResourcesManager( 4100): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4100): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4100): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4100): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ActivityThread( 4116): Added TimaKeyStore provider
I/GCoreUlr( 1834): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/art     ( 1834): Explicit concurrent mark sweep GC freed 25766(1918KB) AllocSpace objects, 36(576KB) LOS objects, 40% free, 9MB/15MB, paused 2.456ms total 104.310ms
W/libprocessgroup( 1022): failed to open /acct/uid_10090/pid_3333/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3363/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3385/cgroup.procs: No such file or directory
E/SMD     (  290): DCD OFF
I/DBG_POLICYDM( 4116): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
I/DBG_POLICYDM( 4116): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
I/DBG_POLICYDM( 4116): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 4116): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
I/DBG_POLICYDM( 4116): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3854): took 0.926094ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d14428 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d0c4c8 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_POLICYDM( 4116): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
I/AMMetaDataParserService( 3854): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
I/DBG_POLICYDM( 4116): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
I/DBG_POLICYDM( 4116): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
I/DBG_POLICYDM( 4116): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/DBG_POLICYDM( 4116): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
I/DBG_POLICYDM( 4116): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3854): took 1.121666ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d38a00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d0c4c8 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_POLICYDM( 4116): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/AMMetaDataParserService( 3854): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
W/Auth    ( 1834): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
I/DBG_POLICYDM( 4116): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 4116): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 4116): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 4116): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
I/DBG_POLICYDM( 4116): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
V/GLSActivity( 1834): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DBG_POLICYDM( 4116): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4149): MountEmulatedStorage()
E/Zygote  ( 4149): v2
I/libpersona( 4149): KNOX_SDCARD checking this for 10032
I/libpersona( 4149): KNOX_SDCARD not a persona
I/SELinux ( 4149): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4149): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1022): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4149 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4149): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Killing 3417:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
W/GCoreFlp( 1834): No location to return for getLastLocation()
W/FusedLocationProvider( 1834): location=null
I/DBG_POLICYDM( 4116): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
D/TimaKeyStoreProvider( 4149): TimaSignature is unavailable
I/DBG_POLICYDM( 4116): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/ActivityThread( 4149): Added TimaKeyStore provider
W/GCoreFlp( 1834): No location to return for getLastLocation()
I/DBG_POLICYDM( 4116): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
W/FusedLocationProvider( 1834): location=null
I/DBG_POLICYDM( 4116): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
I/DBG_POLICYDM( 4116): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
D/PersistentNotificationBroadcastReceiver( 1834): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
I/DBG_POLICYDM( 4116): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
I/DBG_POLICYDM( 4116): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
I/DBG_POLICYDM( 4116): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 4116): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 4116): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/DBG_POLICYDM( 4116): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/DBG_POLICYDM( 4116): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/DBG_POLICYDM( 4116): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/13/12:50:23
I/DBG_POLICYDM( 4116): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/07/13:35:43
I/DBG_POLICYDM( 4116): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
I/DBG_POLICYDM( 4116): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
I/DBG_POLICYDM( 4116): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 4116): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 4116): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
I/DBG_POLICYDM( 4116): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
W/libprocessgroup( 1022): failed to open /acct/uid_10095/pid_3417/cgroup.procs: No such file or directory
I/DBG_POLICYDM( 4116): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 4116): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4169): MountEmulatedStorage()
E/Zygote  ( 4169): v2
I/libpersona( 4169): KNOX_SDCARD checking this for 10026
I/libpersona( 4169): KNOX_SDCARD not a persona
I/SELinux ( 4169): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4169): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1022): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4169 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4169): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 4169): TimaSignature is unavailable
D/ActivityThread( 4169): Added TimaKeyStore provider
D/SBrowserFeatureFlag( 4100): initialized in static block : loadCscFeatureValue() succeed! 
I/DBG_POLICYDM( 4116): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
I/DBG_POLICYDM( 4116): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
I/DBG_POLICYDM( 4116): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
I/GCoreUlr( 1834): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3854): took 0.629480ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8add288 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d0c4c8 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_POLICYDM( 4116): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
I/GCoreUlr( 1834): Unbound from all location providers
I/GCoreUlr( 1834): Place inference reporting - stopped
I/AMMetaDataParserService( 3854): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
D/ManifestProvider( 4100): onCreate()
E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3854): took 0.693958ms for 96*96 texture 0
D/SSRM:n  ( 1022): SIOP:: AP = 420
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d37f28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d293e0 counterpartCT=4 counterpartW=96 counterparth=96
E/AffinityControl( 4040): AffinityControl: registerfunction enter
I/AMMetaDataParserService( 3854): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
E/NetworkSettingsReceiver( 4100): onReceive: android.intent.action.BOOT_COMPLETED
D/AndroidRuntime( 4040): Calling main entry com.android.commands.am.Am
I/DBG_POLICYDM( 4116): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
E/SPPClientService( 4149): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 4149): [PushClientApplication] Push log off : This is Ship build version
I/DBG_POLICYDM( 4116): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
E/SPPClientService( 4149): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
I/DBG_POLICYDM( 4116): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
D/SPPClientService( 4149): PushLog.txt file is not deleted.
D/SPPClientService( 4149): PushLog.txt file is not deleted.
D/SPPClientService( 4149): ============PushLog. stop!
E/PersonaManagerService( 1022): inState():  stateMachine is null !!
I/PersonaManagerService( 1022): PersonaId don't exist
I/ActivityManager( 1022): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/System.err( 4100): java.lang.NoSuchMethodException: isEnabled []
W/System.err( 4100): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 4100): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
W/System.err( 4100): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
W/System.err( 4100): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
W/System.err( 4100): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
W/System.err( 4100): 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
W/System.err( 4100): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
W/System.err( 4100): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 4100): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 4100): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 4100): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4100): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4100): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 4100): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4100): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4100): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4100): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SBrowserFeatureFlag( 4100): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@194c24d0
D/SBrowserFeatureFlag( 4100): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 4100): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
D/CustomFrequencyManagerService( 1022): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1022): mDVFSHelper.acquire()
D/FocusedStackFrame( 1022): Set to : 0
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1022): Focused application set to: xxxx
D/InputDispatcher( 1022): Focus left window: 1511
D/AndroidRuntime( 4040): Shutting down VM
D/Launcher.HomeView( 1511): onPause
I/DBG_POLICYDM( 4116): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
D/Launcher( 1511): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4194): MountEmulatedStorage()
E/Zygote  ( 4194): v2
I/ActivityManager( 1022): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4194 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/PhoneWindow( 1022): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1022): *FMB* installDecor flags : -2122120936
I/libpersona( 4194): KNOX_SDCARD checking this for 10036
I/libpersona( 4194): KNOX_SDCARD not a persona
I/ActivityManager( 1022): Killing 3445:com.fmm.ds/1000 (adj 15): empty #31
I/SELinux ( 4194): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
I/SELinux ( 4194): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4194): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=10 createSurf (1x1),1 flag=404, uhalitest
I/DBG_POLICYDM( 4116): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
E/Zygote  ( 4203): MountEmulatedStorage()
E/Zygote  ( 4203): v2
I/libpersona( 4203): KNOX_SDCARD checking this for 10131
I/libpersona( 4203): KNOX_SDCARD not a persona
I/SELinux ( 4203): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4203 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux ( 4203): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4203): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Killing 3466:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
I/GCoreUlr( 1834): DispatchingService.onDestroy()
I/GCoreUlr( 1834): Stopping handler for UlrDispSvcFast
E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3854): took 0.567708ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d0b940 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d293e0 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_POLICYDM( 4116): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3854): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3854): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3854): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3854): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3854): getResourcePackageName:assistant
I/AMMetaDataParserService( 3854): Resource data:2131034112
I/AMMetaDataParserService( 3854): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3854): getResourceTypeNamexml
E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3854): took 0.618698ms for 96*96 texture 0
I/libpersona( 4225): KNOX_SDCARD checking this for 10167
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d14428 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d0c120 counterpartCT=4 counterpartW=96 counterparth=96
I/libpersona( 4225): KNOX_SDCARD not a persona
E/Zygote  ( 4225): MountEmulatedStorage()
E/Zygote  ( 4225): v2
I/SELinux ( 4225): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4225 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/GAV2    ( 3482): Thread[GAThread,5,main]: No campaign data found.
I/SELinux ( 4225): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/TimaKeyStoreProvider( 4194): TimaSignature is unavailable
E/SELinux ( 4225): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/ActivityThread( 4194): Added TimaKeyStore provider
I/AMMetaDataParserService( 3854): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
D/TimaKeyStoreProvider( 4203): TimaSignature is unavailable
D/ActivityThread( 4203): Added TimaKeyStore provider
I/GCoreUlr( 1834): Unbound from all location providers
I/GCoreUlr( 1834): Place inference reporting - stopped
D/TimaKeyStoreProvider( 4225): TimaSignature is unavailable
D/ActivityThread( 4225): Added TimaKeyStore provider
V/WindowOrientationListener( 1022): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1022): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1022): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
W/ResourcesManager( 4203): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4203): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4203): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
V/ActivityThread( 1511): updateVisibility : ActivityRecord{225f14ea token=android.os.BinderProxy@3f657c28 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
W/art     ( 4040): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/Launcher.HomeView( 1511): onStop
D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/ActivityThread( 1511): updateVisibility : ActivityRecord{225f14ea token=android.os.BinderProxy@3f657c28 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1511): onTrimMemory. Level: 20
,D/PersonaManager( 1022): isKioskContainerExistOnDevice
,I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,D/WindowOrientationListener( 1022):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1022): [SO] activate (ident=0xb9196588, enabled=0)
,I/Sensors ( 1022): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3854): took 0.601042ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d14428 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d0c120 counterpartCT=4 counterpartW=96 counterparth=96
,D/SensorManager( 1022): unregisterListener ::   
,I/Sensors ( 1022): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1022): [SO] changed settle time [1]
D/SensorService( 1022): [SO] setDelay [66000000]
D/SensorService( 1022): [SO] activate (ident=0xb9196588, enabled=1)
D/SensorService( 1022): [SO] AR_init
I/Sensors ( 1022): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/AMMetaDataParserService( 3854): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,D/SensorManager( 1022): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3445/cgroup.procs: No such file or directory
,W/libprocessgroup( 1022): failed to open /acct/uid_10098/pid_3466/cgroup.procs: No such file or directory
,D/SensorService( 1022): [SO] Reset Rotation Old [100], Init [1]
,I/SA      ( 4194): [SSP] onCreated
,D/SensorService( 1022): [SO] -0.402 0.172 9.883
,D/SensorService( 1022): [SO] [100 -> 255]
,D/daemonapp( 1812): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/WebViewFactory( 4225): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/LibraryLoader( 4225): Loading: webviewchromium
,I/LibraryLoader( 4225): Time to load native libraries: 5 ms (timestamps 4279-4284)
I/LibraryLoader( 4225): Expected native library version number "",actual native library version number ""
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1022): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4256 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/Zygote  ( 4256): MountEmulatedStorage(),
E/Zygote  ( 4256): v2
I/libpersona( 4256): KNOX_SDCARD checking this for 10037
I/SA      ( 4194): [TPM] There is no property file
I/libpersona( 4256): KNOX_SDCARD not a persona
,I/SELinux ( 4256): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4256): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
E/SELinux ( 4256): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/SA      ( 4194): [SCU] isHaveSA() - false
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/SA      ( 4194): [TPM] getModelProperty : null
I/SA      ( 4194): [TPM] getCSCProperty : null
,I/SA      ( 4194): [DM] FLOATING AMOLED FEATURE: true
,I/SA      ( 4194): [DM] PRODUCT AMOLED FEATURE: false
,E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3854): took 0.674583ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d056a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d0c120 counterpartCT=4 counterpartW=96 counterparth=96
V/WebViewChromiumFactoryProvider( 4225): Binding Chromium to main looper Looper (main, tid 1) {22baf7f7}
I/LibraryLoader( 4225): Expected native library version number "",actual native library version number ""
I/chromium( 4225): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/SA      ( 4194): [DM] TFT FEATURE: false
,I/SA      ( 4194): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
,I/AMMetaDataParserService( 3854): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529,
,E/Zygote  ( 4268): MountEmulatedStorage(),
I/libpersona( 4268): KNOX_SDCARD checking this for 10135
E/Zygote  ( 4268): v2
I/libpersona( 4268): KNOX_SDCARD not a persona,
I/SELinux ( 4268): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4268): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4268): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SA      ( 4194): [DM] init START
,I/ActivityManager( 1022): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4268 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
,I/SA      ( 4194): [DM] This device is not a Vodafone
,E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/TimaKeyStoreProvider( 4256): TimaSignature is unavailable
,D/ActivityThread( 4256): Added TimaKeyStore provider
I/GFX raster( 3854): took 1.296561ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8add288 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8984ae8 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3854): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
W/ResourceType( 4194): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 4194): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
I/BrowserStartupController( 4225): Initializing chromium process, renderers=0
W/ResourceType( 4194): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 4194): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4194): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 4194): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4194): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 4194): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 4194): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
W/art     ( 4225): Attempt to remove local handle scope entry from IRT, ignoring
W/ResourceType( 4194): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 4194): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 4194): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4194): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 4194): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4194): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 4194): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4194): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 4194): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
W/ResourceType( 4194): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
D/TimaKeyStoreProvider( 4268): TimaSignature is unavailable
W/ResourceType( 4194): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
D/ActivityThread( 4268): Added TimaKeyStore provider
W/ResourceType( 4194): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4194): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 4194): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 4194): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 4194): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 4194): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 4194): [SCU] isHaveSA() - false
I/SA      ( 4194): support phone number id : false
I/SA      ( 4194): [DM] Supports Ref Jpn : true
I/SA      ( 4194): [DM] init END
,I/SA      ( 4194): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 4194): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,W/ResourcesManager( 4268): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4268): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4268): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 4268): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,W/ResourcesManager( 4268): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ActivityManager( 1022): userId = 0, bbcId = -10000,
W/ActivityManager( 1022): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,W/ResourcesManager( 4256): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/SA      ( 4194): [OR] onReceive END
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity,
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity,
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity,
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:assistant
I/AMMetaDataParserService( 3854): Resource data:2131034113
I/AMMetaDataParserService( 3854): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3854): getResourceTypeNamexml
,W/chromium( 4225): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 4225): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3854): took 0.833906ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8f049c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8984ae8 counterpartCT=4 counterpartW=96 counterparth=96
,I/chromium( 4225): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/8)
,I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/8)
,I/SA      ( 4194): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/AMMetaDataParserService( 3854): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,I/SA      ( 4194): [ODM] queryOpenData(key= GEO_IP )
,I/Adreno-EGL( 4225): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4225): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4225): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4225): Local Branch: 
I/Adreno-EGL( 4225): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4225): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4225):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3854): took 0.850417ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8f049c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d38a00 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4194): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4194): [LBE] REF_JPN : true
I/SA      ( 4194): [BDC] create
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 39652(2MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 22MB/34MB, paused 2.737ms total 169.448ms
,V/AlarmManager( 1022): waitForAlarm result :8
,D/Finsky  ( 4169): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/AMMetaDataParserService( 3854): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/CalendarProvider2( 4256): CalendarProvider2.onCreate() called
,I/SA      ( 4194): [DBMV2] getEmailID
,E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/SA      ( 4194): [DBMV2] getDataV02ForItems
I/SA      ( 4194): [SSP] query invoked
,I/GFX raster( 3854): took 0.607812ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d37f28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d2fdb0 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4194): [SCU] get signed id from samsung account2.0 DB.
,I/SA      ( 4194): [SCU] get signed id from samsung account1.0 DB.
,I/AMMetaDataParserService( 3854): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/SA      ( 4194): [BDC] destroy
,I/ActivityManager( 1022): Killing 3517:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,W/libprocessgroup( 1022): failed to open /acct/uid_10055/pid_3517/cgroup.procs: No such file or directory
,I/Icing   ( 2121): Internal init done: storage state 0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3854): took 0.628958ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8984ae8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d16518 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1022): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4314 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,E/Zygote  ( 4314): MountEmulatedStorage(),
E/Zygote  ( 4314): v2
,I/libpersona( 4314): KNOX_SDCARD checking this for 10141
I/libpersona( 4314): KNOX_SDCARD not a persona
,I/AMMetaDataParserService( 3854): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/SELinux ( 4314): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4314): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4314): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/chromium( 4225): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/chromium( 4225): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,I/Icing   ( 2121): Post-init done
,I/GFX raster( 3854): took 0.859167ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d38a00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d37068 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3854): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4314): TimaSignature is unavailable
,D/ActivityThread( 4314): Added TimaKeyStore provider
,W/art     ( 4225): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4225): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 4225): *FMB* installDecor mIsFloating : false
I/ActivityManager( 1022): Waited long enough for: ServiceRecord{17df2a6b u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
D/PhoneWindow( 4225): *FMB* installDecor flags : -2139027200
,D/SystemWebViewEngine( 4225): CordovaWebView is running on device made by: samsung
,W/art     ( 4225): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4225): Attempt to remove local handle scope entry from IRT, ignoring
,E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3854): took 0.649428ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8add288 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d14428 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3854): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,W/ResourcesManager( 4314): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4314): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4314): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4314): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3854): took 0.970208ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d2fdb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a989c8 counterpartCT=4 counterpartW=96 counterparth=96
,D/OpenGLRenderer( 4225): Render dirty regions requested: true
,D/ActivityManager( 1022): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1022): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1022): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1022): handleActiveUserChange for user 0
D/PersonaManagerService( 1022): getPersonasForUser(): returning null!
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PhoneWindow( 4225): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 4225): *FMB* isFloatingMenuEnabled return false
,I/AMMetaDataParserService( 3854): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/SurfaceFlinger(  259): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/InputDispatcher( 1022): Focus entered window: 4225,
,D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
,D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 4225): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 4225): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4225): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 4225): Enabling debug mode 0
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/InputMethodManagerService( 1022): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/Zygote  ( 4362): MountEmulatedStorage(),
E/Zygote  ( 4362): v2
I/libpersona( 4362): KNOX_SDCARD checking this for 10068
I/libpersona( 4362): KNOX_SDCARD not a persona
,I/SELinux ( 4362): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4362): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4362): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4362 uid=10068 gids={50068, 9997} abi=armeabi-v7a
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
,I/Timeline( 4225): Timeline: Activity_idle id: android.os.BinderProxy@15d8ab32 time:45029
,D/TimaKeyStoreProvider( 4362): TimaSignature is unavailable
D/ActivityThread( 4362): Added TimaKeyStore provider
,I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4383): MountEmulatedStorage()
E/Zygote  ( 4383): v2
I/libpersona( 4383): KNOX_SDCARD checking this for 10142
I/libpersona( 4383): KNOX_SDCARD not a persona
,I/SELinux ( 4383): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4383): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4383): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4383 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1022): Displayed Component not be shown by security: +1s194ms
D/CustomFrequencyManagerService( 1022): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1022): mDVFSHelper.release()
I/Timeline( 1022): Timeline: Activity_windows_visible id: ActivityRecord{9e70335 u0 com.test.thalitest/.MainActivity t11} time:45081
,D/CustomFrequencyManagerService( 1022): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@11
I/ActivityManager( 1022): Killing 3287:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
I/ActivityManager( 1022): Killing 3548:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #32
,D/BadgeProvider( 4362): onCreate
D/BadgeProvider( 4362): DatabaseHelper
,D/TimaKeyStoreProvider( 4383): TimaSignature is unavailable
,D/ActivityThread( 4383): Added TimaKeyStore provider
,D/BadgeProvider( 4362): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Finsky  ( 4169): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/ActivityManager( 1022): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3854): took 0.569479ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d2d3a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d37068 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3854): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
W/ResourcesManager( 4383): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/Process ( 4314): Sending signal. PID: 4314 SIG: 9,
W/ActivityManager( 1022): getTasks: caller 10141 does not hold GET_TASKS; limiting output
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
W/ContextImpl( 3854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:assistant
I/AMMetaDataParserService( 3854,): Resource data:2131165203
,W/ResourcesManager( 3854): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ResourcesManager( 3854): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3854): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3854): getResourceTypeNamexml
,W/Settings( 4169): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,W/Settings( 4169): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/GFX construct_block_size_descriptor_2d second part( 3854): took 3.785364ms for 0*0 texture 0
,I/SamsungIME( 1880): getCurrentCandidateView
,W/libprocessgroup( 1022): failed to open /acct/uid_10056/pid_3548/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_10008/pid_3287/cgroup.procs: No such file or directory
,I/GFX generate_partition_tables( 3854): took 17.205365ms for 0*0 texture 0
I/GFX raster( 3854): took 21.558646ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d56960 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb8d56998 counterpartCT=4 counterpartW=80 counterparth=80
I/AMMetaDataParserService( 3854): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,I/ActivityManager( 1022): Process com.android.email (pid 4314)(adj 9) has died(34,631)
,D/Launcher.Model( 1511): reloadBadges entered.
,D/BadgeProvider( 4362): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 4362): sendNotify, [notify] : null
D/BadgeProvider( 4362): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4362): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4362): update, [UpdateCount] : 1
,D/Volley  ( 4169): [626] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 4169): [633] DiskBasedCache.clear: Cache cleared.
,D/Ads     ( 4169): Skipping gmscore version check
,I/ActivityManager( 1022): Killing 3577:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,I/SurfaceFlinger(  259): id=10 Removed uhalitest (7/8)
,I/SurfaceFlinger(  259): id=10 Removed uhalitest (-2/8)
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/GFX construct_block_size_descriptor_2d second part( 3854): took 2.211614ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3854): took 5.167396ms for 0*0 texture 0,
I/GFX raster( 3854): took 8.387917ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d56998 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8d36f00 counterpartCT=4 counterpartW=80 counterparth=80
,E/Zygote  ( 4407): MountEmulatedStorage()
E/Zygote  ( 4407): v2
I/libpersona( 4407): KNOX_SDCARD checking this for 1000
I/libpersona( 4407): KNOX_SDCARD not a persona
,I/SELinux ( 4407): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1022): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4407 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/SELinux ( 4407): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4407): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,I/art     (  307): Explicit concurrent mark sweep GC freed 8690(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 628us total 23.099ms
D/CustomFrequencyManagerService( 1022): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@11
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
I/AMMetaDataParserService( 3854): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,D/TimaKeyStoreProvider( 4407): TimaSignature is unavailable
,D/ActivityThread( 4407): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 17.281ms
,D/Finsky  ( 4169): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4169): [1] Libraries$2.run: Finished loading 1 libraries.
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 714us total 18.673ms,
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4425): MountEmulatedStorage(),
E/Zygote  ( 4425): v2
I/libpersona( 4425): KNOX_SDCARD checking this for 10141
I/libpersona( 4425): KNOX_SDCARD not a persona
I/SELinux ( 4425): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1022): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4425 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
I/SELinux ( 4425): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4425): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,D/TimaKeyStoreProvider( 4425): TimaSignature is unavailable
,D/ActivityThread( 4425): Added TimaKeyStore provider
,D/SamsungIME( 1880): Dismiss ExpandCandiate
,W/libprocessgroup( 1022): failed to open /acct/uid_10013/pid_3577/cgroup.procs: No such file or directory
,I/ActivityManager( 1022): Killing 3622:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,D/JsMessageQueue( 4225): Set native->JS mode to OnlineEventsBridgeMode
W/ResourcesManager( 4425): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4425): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4425): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4425): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4443): MountEmulatedStorage(),
E/Zygote  ( 4443): v2
I/libpersona( 4443): KNOX_SDCARD checking this for 1000
I/libpersona( 4443): KNOX_SDCARD not a persona
,I/SELinux ( 4443): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1022): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4443 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
I/ActivityManager( 1022): Killing 3643:com.android.managedprovisioning/u0a20 (adj 15): empty #31
,V/AlarmManager( 1022): waitForAlarm result :4
I/SELinux ( 4443): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4443): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4443): TimaSignature is unavailable
,D/ActivityThread( 4443): Added TimaKeyStore provider
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,W/libprocessgroup( 1022): failed to open /acct/uid_10058/pid_3622/cgroup.procs: No such file or directory
,W/libprocessgroup( 1022): failed to open /acct/uid_10020/pid_3643/cgroup.procs: No such file or directory
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,I/SamsungIME( 1880): getDebugLevel  : 0x4f4c
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 4443): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4443): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 4443): StateMachine : Current State = 1
,D/SecurityLogAgent( 4443): BootReceiver : completed task. Failed to return wakelock . 
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1022): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4471 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,E/Zygote  ( 4471): MountEmulatedStorage()
I/libpersona( 4471): KNOX_SDCARD checking this for 10148
E/Zygote  ( 4471): v2
I/libpersona( 4471): KNOX_SDCARD not a persona
I/ActivityManager( 1022): Killing 3307:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/SELinux ( 4471): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4471): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4471): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1022): getTasks: caller 10142 does not hold GET_TASKS; limiting output
,D/TimaKeyStoreProvider( 4471): TimaSignature is unavailable
,D/ActivityThread( 4471): Added TimaKeyStore provider
,I/Process ( 4383): Sending signal. PID: 4383 SIG: 9
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
D/BadgeProvider( 4362): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,W/libprocessgroup( 1022): failed to open /acct/uid_10014/pid_3307/cgroup.procs: No such file or directory
,E/SQLiteLog( 4471): (284) automatic index on shooting_modes(title_id)
,D/BadgeProvider( 4362): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 4362): sendNotify, [notify] : null
,D/Launcher.Model( 1511): reloadBadges entered.
,D/BadgeProvider( 4362): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 4362): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4362): update, [UpdateCount] : 1
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,I/ActivityManager( 1022): Process com.android.exchange (pid 4383)(adj 13) has died(25,630)
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4298, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 4490): MountEmulatedStorage(),
E/Zygote  ( 4490): v2
I/libpersona( 4490): KNOX_SDCARD checking this for 1000
I/libpersona( 4490): KNOX_SDCARD not a persona
,I/ActivityManager( 1022): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4490 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/SELinux ( 4490): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4490): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/SamsungIME( 1880): getDebugLevel  : 0x4f4c
E/SELinux ( 4490): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1446): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1446): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/TimaKeyStoreProvider( 4490): TimaSignature is unavailable
,D/ActivityThread( 4490): Added TimaKeyStore provider
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,I/SamsungIME( 1880): KeybaordView init() : load resources
,I/splitIntent( 1022): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1022): Killing 3671:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecurityLogAgent( 4443):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
D/SecurityLogAgent( 4443):  SeDenialReceiver : File path = /data/misc/audit/audit.old
,I/chromium( 4225): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 4225): 
,D/Finsky  ( 4169): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/SecurityLogAgent( 4443):  SeDenialReceiver : Start file Zipping Service 
,W/ContextImpl( 4443): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.securitylogagent, destAppInfo.processName = com.samsung.android.securitylogagent
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/SamsungIME( 1880): getCurrentKeyboard
I/SamsungIME( 1880): getTextKeyboard
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/GFX raster( 3854): took 0.770626ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d56998 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8d56960 counterpartCT=4 counterpartW=80 counterparth=80
,D/SecurityLogAgent( 4443): FileZippingService : onHandleIntent 
D/SecurityLogAgent( 4443): FileZippingService : file path =  /data/misc/audit/audit.old
,I/AMMetaDataParserService( 3854): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,D/SecurityLogAgent( 4443): FileZippingService : onPremise disabled. Zipping..  
D/SecurityLogAgent( 4443): DenialLogFileZipCreator : createZip
,D/SecurityLogAgent( 4443): DenialLogFileZipCreator : Not empty 
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecurityLogAgent( 4443): DenialLogFileZipCreator : Files exceeded the max limit 
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SamsungIME( 1880): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecurityLogAgent( 4443): DenialLogFileZipCreator File existence : true audit.old file size 1511
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecurityLogAgent( 4443): DenialLogFileZipCreator : denied strings found . Starts zipping . 
D/SecurityLogAgent( 4443): ProcessFileZipCreator : File name = denialLog
,D/Finsky  ( 4169): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/SecurityLogAgent( 4443): ProcessFileZipCreator : Created temp file 
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecurityLogAgent( 4443): ProcessFileZipCreator br.readline() has read  13 lines. 
D/SecurityLogAgent( 4443): ProcessFileZipCreator denialxxx.txt file file existence : true size after copying : 0
,D/SecurityLogAgent( 4443): ProcessFileZipCreator : Source = /data/data/com.samsung.android.securitylogagent/files/denialLogData/denialLog-728698263.txt
D/SecurityLogAgent( 4443): ProcessFileZipCreator : Destination = /data/data/com.samsung.android.securitylogagent/files/denialLogData/denialLog-728698263.txt.zip
,D/SecurityLogAgent( 4443): ProcessFileZipCreator : File compressed.
D/SecurityLogAgent( 4443): ProcessFileZipCreatordenialLog-728698263.txt has been deleted after compression. 
,D/SecurityLogAgent( 4443): FileCipher : getKey Called 
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/SecureStorage( 4443): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/GFX raster( 3854): took 0.780367ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8d56998 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb89d1030 counterpartCT=4 counterpartW=80 counterparth=80
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1022): Killing 3689:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3854): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1722): Starting #6
,I/Hs20UtilService( 1722): Message received 5007
D/NearbySettings( 1319): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1319): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1319): MountReceiver.onReceive - Keep current state
I/SecureStorage( 4443): [INFO]: SPID(0x00000000)This device supports Secure Storage
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
I/GFX raster( 3854): took 1.032396ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8add288 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8d56960 counterpartCT=4 counterpartW=80 counterparth=80
I/Hs20UtilService( 1722): Starting #7
,I/SecureStorage(  365): [INFO]: SPID(0x00000001)Credentials: uid 1000, gid 1000, pid 4443
I/SecureStorage(  365): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/Hs20UtilService( 1722): Message received 5007
,E/SMD     (  290): DCD OFF
,I/SecureStorage( 4443): [INFO]: SPID(0x00000000)SS Daemon is running,
,D/SecurityLogAgent( 4443): FileCipher : Secure Storage Supported 
I/SecureStorage( 4443): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  365): [INFO]: SPID(0x00000001)Credentials: uid 1000, gid 1000, pid 4443
I/SecureStorage(  365): [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
D/NearbySettings( 1319): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1319): MountReceiver.onReceive - Keep current state,
I/AMMetaDataParserService( 3854): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,W/ActivityManager( 1022): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/WifiStateMachine( 1022): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,E/        ( 3854): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,D/SecContentProvider2( 1022): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1022): mCursor = null
,D/SecContentProvider2( 1022): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1022): mCursor = null
,D/SecContentProvider2( 1022): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1022): mCursor = null
,I/GFX raster( 3854): took 0.755884ms for 80*80 texture 0
D/SecContentProvider2( 1022): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1022): mCursor = null
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3854): Bitmap=0xb8add288 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb89d1030 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3854): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,D/SecContentProvider2( 1022): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1022): mCursor = null
,D/SecContentProvider2( 1022): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1022): mCursor = null
,D/jxcore_app_log( 4225): JniHelper::setJavaVM(0xb897c448), pthread_self() = -1191313496
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
W/ContextImpl( 3854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3854): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,W/ActivityManager( 1022): userId = 0, bbcId = -10000,
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4225): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4225):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4225):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4225):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4225):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4225): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@372ad3a9 added. We now have 1 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4225): setBluetoothMacAddress: 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4225): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4225): setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/SIP     ( 1491): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4225): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4225):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4225):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4225):     - Bluetooth MAC address: 08:EC:A9:50:76:27
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4225):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4225):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4225):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4225):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4225):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4225):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4225): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13340165 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4225): addListener: New listener added - the number of listeners is now 1
I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=4, Uoast
,E/File    ( 1491): fail readDirectory() errno=2
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3854): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3854): getResourcePackageName:assistant
I/AMMetaDataParserService( 3854): Resource data:2131099648
,D/PowerManagerService( 1022): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1022
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4225): setDiscoveryMode: Discovery mode BLE is supported
,W/ResourcesManager( 3854): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/SRIB_DCS( 1174): log_dcs ThreadedRenderer::initialize entered! 
,I/AMMetaDataParserService( 3854): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3854): getResourceTypeNamexml
,D/accuweather( 1760): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionAPPWIDGET_UPDATE
,D/PowerManagerService( 1022): [s] UserActivityState : 1 -> 2
,D/daemonapp( 1812): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1760): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1760): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1760): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1760): [KK AccuPhone]>>> WCW:42 [0:0] weather widget id size = 1
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3671/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3689/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3854): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/accuweather( 1760): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionAPPWIDGET_UPDATE
,D/accuweather( 1760): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1760): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,I/chromium( 4225): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/daemonapp( 1812): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/AMMetaDataParserService( 3854): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 3854): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/daemonapp( 1812): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1812): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3854): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/daemonapp( 1812): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3854): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/accuweather( 1760): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1760): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,I/AMMetaDataParserService( 3854): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/accuweather( 1760): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1760): [KK AccuPhone]>>> UIM:964 [0:0]  cUI : cnt = 0
,D/accuweather( 1760): [KK AccuPhone]>>> UIM:983 [0:0]  composeEmptyCityUI : true
,E/accuweather( 1760): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 13 35
,E/accuweather( 1760): [KK AccuPhone]>>> UIM:967 [0:0] ========>>> mRefreshManagerisRefreshCompleted() = true
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:assistant
I/AMMetaDataParserService( 3854): Resource data:2131099648
,I/AMMetaDataParserService( 3854): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3854): getResourceTypeNamexml
,I/AMMetaDataParserService( 3854): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/AMMetaDataParserService( 3854): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/accuweather( 1760): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionAPPWIDGET_UPDATE,
,D/accuweather( 1760): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 1760): [KK AccuPhone]>>> UIMEM:89 [0:0] getInstance
,I/AMMetaDataParserService( 3854): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521,
,D/accuweather( 1760): [KK AccuPhone]>>> UIMEM:77 [0:0] UIManager : create ui manager
,D/accuweather( 1760): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 1760): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,I/AMMetaDataParserService( 3854): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/daemonapp( 1812): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3854): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/AMMetaDataParserService( 3854): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/accuweather( 1760): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1812): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
,I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:assistant
I/AMMetaDataParserService( 3854): Resource data:2131099648
,I/AMMetaDataParserService( 3854): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3854): getResourceTypeNamexml
,D/accuweather( 1760): [KK AccuPhone]>>> DBH:3426 [0:0] gADWI : count = 0
,D/daemonapp( 1812): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3854): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/accuweather( 1760): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!,
,I/AMMetaDataParserService( 3854): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/accuweather( 1760): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 1812): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1812): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1812): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3854): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/daemonapp( 1812): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1812): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/AMMetaDataParserService( 3854): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/daemonapp( 1812): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1812): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1812): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1812): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1812): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1812): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1812): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:widgetappapheroaccuweather, cp:Accuweather, aRS:false
,I/AMMetaDataParserService( 3854): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/daemonapp( 1812): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR,
D/daemonapp( 1812): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,I/CalendarProvider2( 4256): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/ActivityManager( 1022): Killing 3482:com.google.android.gm/u0a99 (adj 15): empty #31
,D/daemonapp( 1812): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/AMMetaDataParserService( 3854): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/daemonapp( 1812): [MSC_Daemon]>>> WDSM:140 [0:0] Widget flag autoRefreshSet :  false
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1022): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/DBG_POLICYDM( 4116): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/splitIntent( 1022): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,I/splitIntent( 1022): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
,I/splitIntent( 1022): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!,
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 4116): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4116): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4116): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4116): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3854): getResourcePackageName:assistant
I/AMMetaDataParserService( 3854): Resource data:2131099648
,I/AMMetaDataParserService( 3854): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3854): getResourceTypeNamexml
,I/AMMetaDataParserService( 3854): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/DBG_POLICYDM( 4116): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4116): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4116): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/AMMetaDataParserService( 3854): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3854): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1022): failed to open /acct/uid_10099/pid_3482/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3854): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1834): callingUid 10011, callindPid: 1834
,I/AMMetaDataParserService( 3854): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1834): [236] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2121): Restart initialization of location
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3854): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:assistant
I/AMMetaDataParserService( 3854): Resource data:2131099648
,I/AMMetaDataParserService( 3854): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3854): getResourceTypeNamexml
,I/SecureStorage(  365): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,I/AMMetaDataParserService( 3854): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/SecureStorage( 4443): [INFO]: SPID(0x00000002)Processing data has been completed
,I/SecureStorage( 4443): [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
,D/SecurityLogAgent( 4443): FileCipher : Got the key bytes 
D/SecurityLogAgent( 4443): FileCipher : Saving Key to SecureStorage.  
,I/SecureStorage( 4443): [INFO]: SPID(0x00000002)Processing data
,I/SecureStorage(  365): [INFO]: SPID(0x00000002)Credentials: uid 1000, gid 1000, pid 4443
I/SecureStorage(  365): [INFO]: SPID(0x00000002)Received function mask & code: 0x00000104
,I/AMMetaDataParserService( 3854): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 3854): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/AMMetaDataParserService( 3854): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 29692(1666KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/33MB, paused 2.526ms total 161.913ms
,I/AMMetaDataParserService( 3854): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/AMMetaDataParserService( 3854): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:assistant
I/AMMetaDataParserService( 3854): Resource data:2131099648
,I/AMMetaDataParserService( 3854): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3854): getResourceTypeNamexml
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3854): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/AMMetaDataParserService( 3854): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 3854): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521,
,I/AMMetaDataParserService( 3854): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3854): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/TP/SmsProvider( 1491): query,matched:0, calling pid = 2121
,D/TP/SmsProvider( 1491): match 0:Elapsed time : 1.283 ms
,D/TP/MmsProvider( 1491): Query uri=content://mms, match=0, calling pid = 2121
,I/AMMetaDataParserService( 3854): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/TP/SmsProvider( 1491): query,matched:0, calling pid = 2121
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
W/ContextImpl( 3854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3854): Resource data:Loop for ,running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3854): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity,
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
,D/TP/SmsProvider( 1491): match 0:Elapsed time : 15.909 ms
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3854): getResourcePackageName:assistant
I/AMMetaDataParserService( 3854): Resource data:2131165197
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ResourcesManager( 3854): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 3854): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3854): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3854): getResourceTypeNamexml
,D/TP/MmsProvider( 1491): Query uri=content://mms, match=0, calling pid = 2121
,I/AMMetaDataParserService( 3854): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3854): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3854): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/IcingInternalCorpora( 2121): getNumBytesRead when not calculated.
,I/AMMetaDataParserService( 3854): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
,I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 3854): getResourcePackageName:assistant
I/AMMetaDataParserService( 3854): Resource data:2131165197
,I/AMMetaDataParserService( 3854): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3854): getResourceTypeNamexml
,I/AMMetaDataParserService( 3854): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3854): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3854): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3854): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:assistant
I/AMMetaDataParserService( 3854): Resource data:2131165197
,I/AMMetaDataParserService( 3854): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3854): getResourceTypeNamexml
,I/AMMetaDataParserService( 3854): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3854): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3854): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/jxcore-log( 4225): Initializing JXcore engine
W/jxcore-log( 4225): JXcore engine is ready
,W/SecureStorage(  365): [WARN]: SPID(0x00000003)Trying update data block to DB
,I/AMMetaDataParserService( 3854): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/SecureStorage(  365): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
W/ContextImpl( 3854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3854): getResourcePackageName:assistant
I/AMMetaDataParserService( 3854): Resource data:2131099648
,W/ResourcesManager( 3854): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3854): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3854): getResourceTypeNamexml
,E/audit   ( 1901): type=1400 msg=audit(1457354147.962:205): avc:  denied  { ioctl } for  pid=4518 comm="Thread-657" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
E/audit   ( 1901):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1901): type=1300 msg=audit(1457354147.962:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9377f8f8 items=0 ppid=307 ppcomm=main pid=4518 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-657" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1901): type=1320 msg=audit(1457354147.962:205): 
,I/SecureStorage( 4443): [INFO]: SPID(0x00000003)Processing data has been completed
,I/SecureStorage( 4443): [INFO]: SPID(0x00000003)Skip using SecureStorageExceptionJNI
,D/SecurityLogAgent( 4443): FileCipher : Key loaded. 
,D/SecurityLogAgent( 4443): ProcessFileZipCreator : source file  :  file existence : true size after compression : 162
D/SecurityLogAgent( 4443): FileCipher : File ciphering 
D/SecurityLogAgent( 4443): FileCipher : Source file name = denialLog-728698263.txt.zip source file size 162
,I/AMMetaDataParserService( 3854): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
W/jxcore-log( 4225): Starting JXcore engine
,D/SecurityLogAgent( 4443): FileCipher : Destination file name = denialLog33127235.zip dest file Size 176
D/SecurityLogAgent( 4443): FileCipher : File ciphered successful 
D/SecurityLogAgent( 4443): ProcessFileZipCreator : source after encryption :  file existence : true file size:176
D/SecurityLogAgent( 4443): ProcessFileZipCreator : File ciphered 
D/SecurityLogAgent( 4443): ProcessFileZipCreatordenialLog-728698263.txt.zip has been deleted after encryption. 
D/SecurityLogAgent( 4443): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4443): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4443): StateMachine : Current State = 1
,D/SecurityLogAgent( 4443): FileZippingService : completed task. Returning wakelock . 
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3854): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,D/AuthorizationBluetoothService( 1834): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/a       ( 1834): Opening database auth.proximity.permit_store...
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
W/ContextImpl( 3854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/jxcore-log( 4225): Platform android
W/jxcore-log( 4225): 
,W/jxcore-log( 4225): Process ARCH arm
W/jxcore-log( 4225): 
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1022): Killing 3734:com.google.android.talk/u0a102 (adj 15): empty #31
,V/GLSActivity( 1834): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:assistant
I/AMMetaDataParserService( 3854): Resource data:2131165220
,W/GCM-DMM ( 1834): Force release of GOOGLE_C2DM lock
,W/ResourcesManager( 3854): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3854): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3854): getResourceTypeNamexml
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3854): Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,I/AMMetaDataParserService( 3854): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,W/GCoreFlp( 1834): No location to return for getLastLocation()
,W/FusedLocationProvider( 1834): location=null
,I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings,.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure,
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings,
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
,I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3854): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
W/ContextImpl( 3854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
,I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
,I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
,I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
,I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet,
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/splitIntent( 1022): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=15, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/splitIntent( 1022): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
,I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ManageApplications
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.RunningServices
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
,I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY,_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.an,droid.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/libpersona( 4543): KNOX_SDCARD checking this for 10108
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/libpersona( 4543): KNOX_SDCARD not a persona
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/ActivityManager( 1022): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4543 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/ActivityManager( 1022): Killing 3711:com.wssnps/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3854): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3854): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3854): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
I/PCWCLIENTTRACE_PushUtil( 3405): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 3405): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3405): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3405): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
E/Zygote  ( 4543): MountEmulatedStorage()
E/Zygote  ( 4543): v2
I/SELinux ( 4543): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4543): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4543): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3606): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 07 13:35:48 GMT+01:00 2016
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3606): KLMSAbstractReciever(): onReceive().END.
I/KLMS-2.5.123: ( 3606): KLMSIntentService(): onCreate()
I/KLMS-2.5.123: ( 3606): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.5.123: ( 3606): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/RCPManagerService( 1022): exchangeData() failure , invalid userId
I/KLMS-2.5.123: ( 3606): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.123: ( 3606): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
I/KLMS-2.5.123: ( 3606): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
D/TimaKeyStoreProvider( 4543): TimaSignature is unavailable
I/KLMS-2.5.123: ( 3606): StateImplV2(): networkChangeListener().START
D/ActivityThread( 4543): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3606): NetworkChangeOperations(): uploadRequestLog().START 
D/RCPManagerService( 1022): exchangeData() failure , invalid userId
I/KLMS-2.5.123: ( 3606): NetworkChangeOperations(): uploadRequestLog().END 
I/KLMS-2.5.123: ( 3606): StateImplV2(): networkChangeListener().END
D/SecurityLogAgent( 4443): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4443): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4443): StateMachine : Current State = 1
I/KLMS-2.5.123: ( 3606): KLMSIntentService(): onDestroy()
D/SecurityLogAgent( 4443): StateMachine : Changed Current State = 1
D/accuweather( 1760): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/libprocessgroup( 1022): failed to kill 1 processes for processgroup 3734
,D/daemonapp( 1812): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 1760): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1760): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1760): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1760): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 4116): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1760): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1760): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4561): MountEmulatedStorage()
E/Zygote  ( 4561): v2
I/libpersona( 4561): KNOX_SDCARD checking this for 10077
I/libpersona( 4561): KNOX_SDCARD not a persona
I/SELinux ( 4561): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4561): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4561): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4561 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3711/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4561): TimaSignature is unavailable
,D/ActivityThread( 4561): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4116): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4116): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 4116): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,E/SPPClientService( 4149): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 4194): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 4194): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 4194): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 4116): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 4194): [SLFUCHKMGR] constructor called
,I/DBG_POLICYDM( 4116): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4116): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4116): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4116): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4116): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4116): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4116): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 4116): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,D/NetworkLogImpl( 2121): Loaded NetworkSpeedPredictor
I/iu.SyncManager( 2121): SYNC; picasa accounts
,I/DBG_POLICYDM( 4116): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,I/iu.Environment( 2121): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,E/DBG_POLICYDM( 4116): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,I/SA      ( 4194): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4194): [OR] == isSIMCardReady false ==
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/DBG_POLICYDM( 4116): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4116): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4580): MountEmulatedStorage()
I/libpersona( 4580): KNOX_SDCARD checking this for 10009
E/Zygote  ( 4580): v2
I/libpersona( 4580): KNOX_SDCARD not a persona
I/SELinux ( 4580): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4580): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4580): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4580 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,I/jxcore-log( 4225): JXcore Cordova bridge is ready!
I/jxcore-log( 4225): 
W/jxcore-log( 4225): JXcore engine is started
,I/iu.UploadsManager( 2121): num queued entries: 0
,I/iu.UploadsManager( 2121): num updated entries: 0
,I/org.thaliproject.p2p.ThaliPermissions( 4225): execute: REQUEST_ACCESS_COARSE_LOCATION
I/iu.SyncManager( 2121): NEXT; no task
,E/jxcore  ( 4225): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4225): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,D/TimaKeyStoreProvider( 4580): TimaSignature is unavailable
,D/ActivityThread( 4580): Added TimaKeyStore provider
,I/chromium( 4225): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,D/FocusedStackFrame( 1022): Set to : 0
,I/SA      ( 4194): [SCU] == networkStateCheck == true
I/SA      ( 4194): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4194): isChinaCountryCode : false
I/SA      ( 4194): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 4194): [OR] == networkStateCheck true ==
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,I/SA      ( 4194): [OR] GetMyCountryZoneTask
I/SA      ( 4194): [OR] onReceive END,
D/InputDispatcher( 1022): Focused application set to: xxxx
,D/InputDispatcher( 1022): Focus left window: 4225
,D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (144 us)
,I/SA      ( 4194): [SRS] prepareGetMyCountryZone
,I/SA      ( 4194): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4194): [SSP] query invoked
,I/SA      ( 4194): [TPMU] GetMccFromDB : null
,I/SA      ( 4194): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4194): [TPM] isNoProxy(default) : true
,E/File    ( 4194): fail readDirectory() errno=2
,W/PluginManager( 4225): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 321ms. Plugin should use CordovaInterface.getThreadPool().
,D/CustomFrequencyManagerService( 1022): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1022): mDVFSHelper.acquire()
,V/DownloadManager( 1231): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,V/WindowOrientationListener( 1022): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1022): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1022): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/MusicStore( 4543): Database version: 104
,D/WindowOrientationListener( 1022):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1022): [SO] activate (ident=0xb9196588, enabled=0)
I/Sensors ( 1022): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/Launcher( 1511): onRestart, Launcher: 424420560
,D/Launcher( 1511): onStart, Launcher: 424420560
D/Launcher.HomeView( 1511): onStart
,D/Launcher( 1511): onResume, Launcher: 424420560
D/SettingsProvider( 1022): name = kids_home_mode,
D/SettingsProvider( 1022): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1022): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1022): selectionArgs: false
D/SettingsProvider( 1022): selectionArgs: 10006
D/SecContentProvider( 1022): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1022): ret = -1
D/SecContentProvider2( 1022): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1022): mCursor = null
,D/Launcher.HomeView( 1511): onResume
,D/SensorManager( 1022): unregisterListener ::   
,I/Sensors ( 1022): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1022): [SO] changed settle time [0]
D/SensorService( 1022): [SO] setDelay [200000000]
D/SensorService( 1022): [SO] activate (ident=0xb9196588, enabled=1)
D/SensorService( 1022): [SO] AR_init
I/Sensors ( 1022): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/Launcher( 1511): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1511): onResume
D/ActivityManager( 1022): handle home activity for 0
I/WallpaperManagerService( 1022): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1022): post home show event for user 0
D/ActivityManager( 1022): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1022): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1022): postActiveUserChange, showWhenLocked: false
,D/SensorManager( 1022): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
D/WallpaperManagerService( 1022):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1022): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1022): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1022): handleActiveUserChange for user 0
,I/SurfaceFlinger(  259): id=13 createSurf (540x960),1 flag=4, Mauncher
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1022): Focus entered window: 1511,
D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,E/Zygote  ( 4604): MountEmulatedStorage()
E/Zygote  ( 4604): v2
I/libpersona( 4604): KNOX_SDCARD checking this for 10110
I/libpersona( 4604): KNOX_SDCARD not a persona
,D/SRIB_DCS( 1511): log_dcs ThreadedRenderer::initialize entered! 
,I/SELinux ( 4604): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1022): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4604 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1022): Killing 3754:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31,
I/SELinux ( 4604): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4604): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/Launcher( 1511): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/InputMethodManagerService( 1022): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
,D/SamsungIME( 1880): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/IInputConnectionWrapper( 4225): showStatusIcon on inactive InputConnection
,I/Timeline( 1511): Timeline: Activity_idle id: android.os.BinderProxy@3f657c28 time:49004
,D/PersonaManager( 1022): isKioskContainerExistOnDevice
,D/TimaKeyStoreProvider( 4604): TimaSignature is unavailable
,D/ActivityThread( 4604): Added TimaKeyStore provider
,E/Watchdog( 1022): !@Sync 1
,I/ActivityManager( 1022): Displayed Component not be shown by security: +142ms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WaitQueueForNetworkActivate( 4580): notifyNetworkActivated
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3754/cgroup.procs: No such file or directory
,D/SettingsProvider( 1022): name = audio_safe_volume_state
,I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,D/SensorService( 1022): [SO] Reset Rotation Old [100], Init [1]
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 4580): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1022): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/ResourcesManager( 4543): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4543): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4543): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/SensorService( 1022): [SO] currT = 49321087000, prevT = 48831158000, diff = 489929000, [-0.402 0.172 9.883]
,D/SensorService( 1022): [SO] -0.402 0.172 9.883
D/SensorService( 1022): [SO] [100 -> 255]
,W/ActivityThread( 4543): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4543): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@8ac5b78: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4543): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4543): GMSCore installation verified
,D/CustomFrequencyManagerService( 1022): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1022): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1022): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@11
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ConfigStore( 4543): Config Database version: 1
,I/Timeline( 1022): Timeline: Activity_windows_visible id: ActivityRecord{2766112d u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:49445
,I/SurfaceFlinger(  259): id=11 Removed NainActivit (7/9)
,I/SurfaceFlinger(  259): id=11 Removed NainActivit (-2/9)
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4604): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,W/ScreenOrientationListener( 4225): Removing an inexistent observer!
,D/hcjo    ( 4580): AutoUpdateManager:IDLE:execute
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4604): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/InitializeManagerStateMachine( 4580): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 4580): exit::IDLE
D/InitializeManagerStateMachine( 4580): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4580): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4580): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4580): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4580): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4580): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4580): entry::SUCCESS
D/hcjo    ( 4580): AutoUpdateManager:INITCHECK:onInitializeSuccess
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4604): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4604): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/hcjo    ( 4580): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 4580): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 4580): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4580): exit::SUCCESS
,D/InitializeManagerStateMachine( 4580): entry::IDLE
,I/ActivityManager( 1022): Killing 3787:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4543): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4543): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4543): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1022): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/CustomFrequencyManagerService( 1022): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@11
,W/libprocessgroup( 1022): failed to open /acct/uid_10065/pid_3787/cgroup.procs: No such file or directory
,I/WebViewFactory( 4604): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/WifiDisplayAdapter( 1022): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1022): getStreamVolume 3 index 0
,I/MediaRouter( 4543): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/LibraryLoader( 4604): Loading: webviewchromium
,I/LibraryLoader( 4604): Time to load native libraries: 5 ms (timestamps 9715-9720)
I/LibraryLoader( 4604): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4604): Binding Chromium to main looper Looper (main, tid 1) {7f9dc42}
,I/LibraryLoader( 4604): Expected native library version number "",actual native library version number ""
,I/chromium( 4604): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/NetworkMonitor( 4543): type=WIFI subType= reason=null isConnected=true
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4653): MountEmulatedStorage(),
,E/Zygote  ( 4653): v2,
I/ActivityManager( 1022): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4653 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/libpersona( 4653): KNOX_SDCARD checking this for 10001
I/libpersona( 4653): KNOX_SDCARD not a persona
,I/SELinux ( 4653): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4653): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/BrowserStartupController( 4604): Initializing chromium process, renderers=0,
E/SELinux ( 4653): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/art     ( 4604): Attempt to remove local handle scope entry from IRT, ignoring
,D/WifiDisplayAdapter( 1022): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor( 4543): type=WIFI subType= reason=null isConnected=true
,W/chromium( 4604): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 4604): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium( 4604): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/ActivityManager( 1022): Killing 3771:com.vlingo.midas/u0a28 (adj 15): empty #31
,W/AudioManagerAndroid( 4604): Requires BLUETOOTH permission
,I/ActivityManager( 1022): Waited long enough for: ServiceRecord{3d0d191e u0 com.samsung.android.providers.context/.ContextService}
,D/PowerManagerService( 1022): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1022) eventTime = 49806
,D/PowerManagerService( 1022): [s] UserActivityState : 2 -> 1
D/PowerManagerService( 1022): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1022 (0x0)
D/PowerManagerService( 1022): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1022, ws=WorkSource{10049}) (elapsedTime=3410)
,D/TimaKeyStoreProvider( 4653): TimaSignature is unavailable
,D/ActivityThread( 4653): Added TimaKeyStore provider
,I/Adreno-EGL( 4604): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4604): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4604): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4604): Local Branch: 
I/Adreno-EGL( 4604): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4604): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4604):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/NSApplication( 4604): Starting up...
,I/ActivityManager( 1022): Killing 1411:com.android.defcontainer/u0a3 (adj 15): empty #31
,W/libprocessgroup( 1022): failed to open /acct/uid_10028/pid_3771/cgroup.procs: No such file or directory
,I/ActivityManager( 1022): Waited long enough for: ServiceRecord{399e0ae7 u0 com.android.settings/.wifi.WifiCredService}
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4689): MountEmulatedStorage()
,E/Zygote  ( 4689): v2
,I/libpersona( 4689): KNOX_SDCARD checking this for 1000
,I/libpersona( 4689): KNOX_SDCARD not a persona
,I/ActivityManager( 1022): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4689 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4689): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1022): Killing 3854:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,I/SELinux ( 4689): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4689): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/QuickConnect( 4080): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 4080): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 4080): PeriphStartReceiver.onReceive - no need to start
,I/ActivityManager( 1022): Killing 3914:com.samsung.helphub/1000 (adj 15): empty #31
,W/libprocessgroup( 1022): failed to open /acct/uid_10003/pid_1411/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4689): TimaSignature is unavailable
,D/ActivityThread( 4689): Added TimaKeyStore provider
,W/ContextImpl( 2927): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3914/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3854/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3176): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 3176): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,E/DBG_DM  ( 3176): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,I/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,I/Process ( 2927): Sending signal. PID: 2927 SIG: 9
,I/DIAGMON_AGENT( 4689): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 12 sec
,I/DBG_DM  ( 3176): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,I/DBG_DM  ( 3176): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/ActivityManager( 1022): Process com.sec.android.app.sysscope (pid 2927)(adj 0) has died(56,586)
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 8
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [8]
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 0
,I/DBG_DM  ( 3176): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 3176): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/SA      ( 4194): [RC New] Execute method=[GET] start
,I/DBG_DM  ( 3176): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 3176): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 3176): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 3176): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/DBG_DM  ( 3176): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:362673799
,I/DBG_DM  ( 3176): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,I/DIAGMON_AGENT( 4689): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,I/SA      ( 4194): [RC New] Security=[true]
,I/System.out( 4194): Thread-630(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 4194): Thread-630(ApacheHTTPLog):isSBSettingEnabled false
,I/DIAGMON_AGENT( 4689): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
I/System.out( 4194): Thread-630(ApacheHTTPLog):isShipBuild true
,I/DIAGMON_AGENT( 4689): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/System.out( 4194): Thread-630(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4194): Thread-630(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/DIAGMON_AGENT( 4689): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 4689): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 4689): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10036
I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 705624899
,I/DBG_DM  ( 3176): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,I/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,I/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,I/DBG_DM  ( 3176): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
I/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,E/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,E/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@238b1453
,I/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(755/lllllIIlIIIlIlIIIllI)] UI_id:223
,W/ContextImpl( 3176): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 com.wssyncmldm.llIIllllIIlllIIIIlll.handleMessage:1090 
,W/ContextImpl( 3176): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 
,I/Timeline( 3176): Timeline: Activity_launch_request id:com.wssyncmldm time:50276
,E/PersonaManagerService( 1022): inState():  stateMachine is null !!
,I/PersonaManagerService( 1022): PersonaId don't exist
I/ActivityManager( 1022): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,W/ResourcesManager( 1022): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/CustomFrequencyManagerService( 1022): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1022): mDVFSHelper.acquire()
,D/FocusedStackFrame( 1022): Set to : 0
,D/Launcher.HomeView( 1511): onPause
,D/Launcher( 1511): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/InputDispatcher( 1022): Focused application set to: xxxx
,D/InputDispatcher( 1022): Focus left window: 1511
,D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,I/DBG_POLICYDM( 4116): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 4116): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/WindowOrientationListener( 1022):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,I/DBG_POLICYDM( 4116): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
D/SensorService( 1022): [SO] activate (ident=0xb9196588, enabled=0)
I/Sensors ( 1022): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/DBG_POLICYDM( 4116): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/SensorManager( 1022): unregisterListener ::   ,
I/Sensors ( 1022): AccelerometerSensor(0) setDelay : 66000000(ns)
,I/DBG_POLICYDM( 4116): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
D/SensorService( 1022): [SO] changed settle time [1]
D/SensorService( 1022): [SO] setDelay [66000000],
D/SensorService( 1022): [SO] activate (ident=0xb9196588, enabled=1)
,D/SensorService( 1022): [SO] AR_init
I/Sensors ( 1022): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
I/DBG_POLICYDM( 4116): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/SurfaceFlinger(  259): id=12 Removed Uoast (8/8)
,I/SurfaceFlinger(  259): id=12 Removed Uoast (-2/8)
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/SensorManager( 1022): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  ,
,E/Zygote  ( 4709): MountEmulatedStorage(),
E/Zygote  ( 4709): v2
,I/libpersona( 4709): KNOX_SDCARD checking this for 10008
I/libpersona( 4709): KNOX_SDCARD not a persona
I/SELinux ( 4709): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4709 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 3176): [com.wssyncmldm.ui.XUIDialogActivity(2153/onResume)] 
I/SELinux ( 4709): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/DBG_DM  ( 3176): [com.wssyncmldm.ui.XUIDialogActivity(2195/lllIlIlIIIllIIlIllIl)] id 223
E/SELinux ( 4709): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,I/art     (  307): Explicit concurrent mark sweep GC freed 8704(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 619us total 28.458ms
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,D/TimaKeyStoreProvider( 4709): TimaSignature is unavailable
I/DBG_DM  ( 3176): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
D/ActivityThread( 4709): Added TimaKeyStore provider
,I/Timeline( 3176): Timeline: Activity_launch_request id:com.wssyncmldm time:50410
,E/PersonaManagerService( 1022): inState():  stateMachine is null !!
I/PersonaManagerService( 1022): PersonaId don't exist
I/ActivityManager( 1022): do not start freezing screen for locked container getKeyguardshowstate = false
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.735ms
,D/SensorService( 1022): [SO] Reset Rotation Old [100], Init [1]
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,D/CustomFrequencyManagerService( 1022): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@7
D/CustomFrequencyManagerService( 1022): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1022): mDVFSHelper.acquire()
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 20.154ms
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/InputDispatcher( 1022): Focused application set to: xxxx
,I/DBG_DM  ( 3176): [com.wssyncmldm.ui.IIllIIIlIllIIIllIIlI(252/llllIIIllIlIIIIllllI)] 
,D/ActivityManager( 1022): post active user change for 0 fullscreen false record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1022): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1022): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1022): handleActiveUserChange for user 0
D/PersonaManagerService( 1022): getPersonasForUser(): returning null!
I/KnoxTimeoutHandler( 1022): Target Activity is not fullscreen. We will not show this activity0
,I/DBG_DM  ( 3176): [com.wssyncmldm.ui.XUIDialogActivity(2145/onPause)] ,
,V/WindowOrientationListener( 1022): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowManager( 1022): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1022): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,D/SensorService( 1022): [SO] -0.383 0.172 9.883
D/SensorService( 1022): [SO] [100 -> 255]
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 3176): [com.wssyncmldm.ui.XUIInstallConfirmActivity(75/onCreate)] Postpone Count : 23
,I/ActivityManager( 1022): Killing 3938:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,I/FOTA_Client( 4709): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 4709): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 4709): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 4709): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/splitIntent( 1022): Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,I/ActivityManager( 1022): Killing 3961:com.sec.knox.bridge/1000 (adj 15): empty #31
,I/splitIntent( 1022): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
,I/splitIntent( 1022): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,D/PhoneWindow( 3176): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3176): *FMB* installDecor flags : -2139029248
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4726): MountEmulatedStorage()
,E/Zygote  ( 4726): v2
I/libpersona( 4726): KNOX_SDCARD checking this for 10058
I/libpersona( 4726): KNOX_SDCARD not a persona
,I/SELinux ( 4726): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4726): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4726): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4726 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/FOTA_Client( 4709): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/daemonapp( 1812): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1812): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1812): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1812): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1812): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/FOTA_Client( 4709): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,D/daemonapp( 1812): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1812): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1812): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1812): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1812): [MSC_Daemon]>>> ====================================================================================================================
I/art     ( 3176): Background partial concurrent mark sweep GC freed 16788(1144KB) AllocSpace objects, 24(388KB) LOS objects, 45% free, 4MB/8MB, paused 11.196ms total 44.949ms
D/daemonapp( 1812): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1812): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1812): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/daemonapp( 1812): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1812): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1812): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1812): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/SecurityLogAgent( 4443): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4443): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4443): StateMachine : Current State = 1
,E/daemonapp( 1812): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/TimaKeyStoreProvider( 4726): TimaSignature is unavailable
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
I/KLMS-2.5.123: ( 3606): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Mon Mar 07 13:35:50 GMT+01:00 2016
,D/ActivityThread( 4726): Added TimaKeyStore provider
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3938/cgroup.procs: No such file or directory
,D/comdaemonstockapp( 1812): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1812): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,V/AlarmManager( 1022): waitForAlarm result :4
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3961/cgroup.procs: No such file or directory
,I/KLMS-2.5.123: ( 3606): KLMSAbstractReciever(): onReceive().END.
,I/DBG_DM  ( 3176): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/KLMS-2.5.123: ( 3606): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3606): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3606): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3606): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,I/KLMS-2.5.123: ( 3606): KLMSIntentService(): TIME_CHANGED
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/KLMS-2.5.123: ( 3606): StateImplV2(): dateTimeChanged().START : Mon Mar 07 13:35:50 GMT+01:00 2016
,I/KLMS-2.5.123: ( 3606): StateImplV2(): dateTimeChanged().END
,I/KLMS-2.5.123: ( 3606): KLMSIntentService(): onDestroy()
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/DBG_DM  ( 3176): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 0
,D/WindowManager( 1022): showStatusBarByNotification() mOpenByNotification=false
,W/ContextImpl( 3176): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate:98 android.app.Activity.performCreate:6374 
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ResourcesManager( 1174): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KnoxNotification( 1174): ----- inflateViews : modified publicViewLocal -----
,D/KnoxNotification( 1174): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1174): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
,I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 28014(1623KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 2.530ms total 156.532ms
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4747): MountEmulatedStorage(),
I/libpersona( 4747): KNOX_SDCARD checking this for 10153
E/Zygote  ( 4747): v2
I/libpersona( 4747): KNOX_SDCARD not a persona
I/SELinux ( 4747): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1022): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4747 uid=10153 gids={50153, 9997} abi=armeabi-v7a,
,I/SELinux ( 4747): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4747): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SA      ( 4194): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/SettingsProvider( 1022): name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/CheckinService( 2121): Checkin interval check for package: unspecified last checkin: 1457166050648 min interval config: 0 actual interval: 188100392
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3176): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,D/TimaKeyStoreProvider( 4747): TimaSignature is unavailable
,D/ActivityThread( 4747): Added TimaKeyStore provider
,I/ExternalOEMControlProvider( 4726): onCreate
I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3176): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4747): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,E/Zygote  ( 4765): MountEmulatedStorage()
E/Zygote  ( 4765): v2
I/libpersona( 4765): KNOX_SDCARD checking this for 10041
I/libpersona( 4765): KNOX_SDCARD not a persona
I/SELinux ( 4765): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/SELinux ( 4765): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 4765): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4765 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3176): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/ Time Manager ( 4726): Time Difference not stored. TIME_DIFFERENCE
,D/accuweather( 1760): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1760): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/TimaKeyStoreProvider( 4765): TimaSignature is unavailable
,I/DBG_DM  ( 3176): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,D/ActivityThread( 4765): Added TimaKeyStore provider
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/ActivityManager( 1022): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4780 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 4780): MountEmulatedStorage(),
E/Zygote  ( 4780): v2
I/libpersona( 4780): KNOX_SDCARD checking this for 1000
I/SELinux ( 4780): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/libpersona( 4780): KNOX_SDCARD not a persona
,I/SELinux ( 4780): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3176): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 23
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/SELinux ( 4780): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,D/TimaKeyStoreProvider( 4780): TimaSignature is unavailable,
D/ActivityThread( 4780): Added TimaKeyStore provider
,E/Zygote  ( 4792): MountEmulatedStorage()
,E/Zygote  ( 4792): v2
I/libpersona( 4792): KNOX_SDCARD checking this for 10081
I/libpersona( 4792): KNOX_SDCARD not a persona
,I/SELinux ( 4792): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4792): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1022): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4792 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4792): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3176): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/ActivityManager( 1022): Killing 3976:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4792): TimaSignature is unavailable
D/ActivityThread( 4792): Added TimaKeyStore provider
I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/ActivityManager( 1022): Killing 4008:com.sec.android.app.mt/1000 (adj 15): empty #31
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,W/ResourcesManager( 4765): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4765): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4765): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4765): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4765): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3176): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
W/ResourcesManager( 4792): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4792): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4792): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4792): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4792): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/DBG_DM  ( 3176): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/DBG_DM  ( 3176): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3976/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_4008/cgroup.procs: No such file or directory
,D/OpenGLRenderer( 3176): Render dirty regions requested: true
,D/ActivityManager( 1022): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1022): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1022): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1022): handleActiveUserChange for user 0
,D/PersonaManagerService( 1022): getPersonasForUser(): returning null!
,D/PhoneWindow( 3176): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3176): *FMB* isFloatingMenuEnabled return false
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/SensorService( 1022): [SO] -0.402 0.172 9.902
,D/TimeService( 4780): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1457354151342
,D/        ( 4780): TimeServiceNative: User Time to be set is 1457354151342
D/QC-time-services( 4780): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4780): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4780): Lib:time_genoff_operation: pargs->ts_val = 1457354151342
,D/QC-time-services(  319): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 4780): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  319): Daemon:Received base = 2, unit = 1, operation = 0,value = 1457354151342
D/QC-time-services(  319): Daemon:genoff_opr: Base = 2, val = 1457354151342, operation = 0
D/QC-time-services(  319): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/2/70 16:12:35
D/QC-time-services(  319): Daemon:Value read from RTC seconds = 21139955000
D/QC-time-services(  319): Daemon:new time 1457354151342 
D/QC-time-services(  319): Daemon: delta 1436214196342 genoff 1436214196342 
D/QC-time-services(  319): Daemon:genoff_persistent_update: Writing genoff = 1436214196342 to memory
D/QC-time-services(  319): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  319): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/Mms/MmsApp( 4765): [start]    onCreate() consume time = 0.0
,D/QC-time-services(  319): Updating the TOD offset
D/QC-time-services(  319): Daemon:genoff_persistent_update: Writing genoff = 1436214196342 to memory
D/QC-time-services(  319): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  319): Daemon:time_persistent_memory_opr:Genoff write operation 
,I/SurfaceFlinger(  259): id=14 createSurf (1x1),1 flag=404, YUIInstallC
,D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/SettingsProvider( 1022): name = next_alarm_formatted
D/SettingsProvider( 1022): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1022): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1022): selectionArgs: false
D/SettingsProvider( 1022): selectionArgs: 10081
D/SecContentProvider( 1022): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1022): ret = -1
,D/InputDispatcher( 1022): Focus entered window: 3176
E/QC-time-services(  319): Daemon:Update to modem bit set
D/QC-time-services(  319): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  319): Daemon: Base = 2, Value being sent to MODEM = 1120249396342
,E/QC-time-services( 4780): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  319): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  319): Daemon: Time-services: Waiting to acceptconnection
,I/ActivityManager( 1022): Killing 4100:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
,D/SRIB_DCS( 3176): log_dcs ThreadedRenderer::initialize entered! 
,I/Adreno-EGL( 3176): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3176): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3176): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3176): Local Branch: 
I/Adreno-EGL( 3176): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3176): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3176):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
I/OpenGLRenderer( 3176): Initialized EGL, version 1.4
,D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,D/OpenGLRenderer( 3176): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3176): Enabling debug mode 0
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,W/art     ( 4765): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 116.665ms
,W/libprocessgroup( 1022): failed to open /acct/uid_10127/pid_4100/cgroup.procs: No such file or directory
,D/InputMethodManagerService( 1022): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PersonaManager( 1022): isKioskContainerExistOnDevice
,I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
I/ActivityManager( 1022): Displayed Component not be shown by security: +960ms (total +1s114ms)
,W/art     ( 4792): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 132.013ms
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SamsungIME( 1880): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/Timeline( 3176): Timeline: Activity_idle id: android.os.BinderProxy@13ffecbb time:51450
,D/Mms/TelephonyPermission( 4765): start operation mode monitor
,D/Mms/ArtClassLoader( 4765): init before art
,W/ResourcesManager( 4765): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4820): MountEmulatedStorage(),
,E/Zygote  ( 4820): v2
I/libpersona( 4820): KNOX_SDCARD checking this for 10090
I/SELinux ( 4820): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4820): KNOX_SDCARD not a persona
I/SELinux ( 4820): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1022): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=4820 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 4820): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Killing 4268:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,D/Mms/TelephonyPermission( 4765): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission( 4765): isDefault true
,D/Mms/MmsApp( 4765): onCreate() com.android.mms
,D/TimaKeyStoreProvider( 4820): TimaSignature is unavailable
,D/ActivityThread( 4820): Added TimaKeyStore provider
,I/SA      ( 4194): [RC New] [v2liruge] api execute + 1332
,I/SA      ( 4194): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4194): AsyncTask #1 calls detatch()
,I/SA      ( 4194): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 4194): [OCP] update openData : PL
,I/SA      ( 4194): [TPMU] getNetworkMcc : 
,I/SA      ( 4194): [SCU] saveMccToPreferece Start
,I/SA      ( 4194): [SCU] RegionMCC : 260
I/SA      ( 4194): [SSP] query invoked
,D/elm:15121( 4820): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15121( 4820): ELMEngine.ELMEngine( context ).
,D/elm:15121( 4820): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/Mms/MmsApp( 4765): [start]    initCountryIso consume time = 326.493854
,D/elm:15121( 4820): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/elm:15121( 4820): ElmAgentService : onCreate()
D/elm:15121( 4820): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
E/Zygote  ( 4838): MountEmulatedStorage()
E/Zygote  ( 4838): v2
I/libpersona( 4838): KNOX_SDCARD checking this for 10130
I/libpersona( 4838): KNOX_SDCARD not a persona
,I/SELinux ( 4838): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4838): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/CountryDetector( 1022): The first listener is added
E/SELinux ( 4838): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=4838 uid=10130 gids={50130, 9997} abi=armeabi-v7a
I/SA      ( 4194): [TPMU] GetMccFromDB : null
I/SA      ( 4194): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4194): [SCU] saveMccToPreferece End
I/SA      ( 4194): [RC New] executeRequest [v2liruge] end. 1429
I/SA      ( 4194): [RC New] Execute end
I/SA      ( 4194): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 4194): [OR] GetMyCountryZoneTask Success
,D/elm:15121( 4820): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:15121( 4820): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:15121( 4820): ModuleBase.ModifySetAlarm()
D/elm:15121( 4820): MDMBridge.getInstance()
D/elm:15121( 4820): MDMBridge.getAllLicenseInfoFromSDK()
,D/Mms/MmsApp( 4765): [end]    initCountryIso consume time = 38.378386
,D/Mms/MmsConfig( 4765): [start]    MmsConfig.init() consume time = 0.469687
,D/elm:15121( 4820): ElmAgentService : onDestroy().
,W/libprocessgroup( 1022): failed to open /acct/uid_10135/pid_4268/cgroup.procs: No such file or directory
,I/ActivityManager( 1022): Killing 4362:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4838): TimaSignature is unavailable
,D/ActivityThread( 4838): Added TimaKeyStore provider
,D/Mms/MmsConfig( 4765): before partial update
,W/ResourcesManager( 4838): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4838): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/Mms/MmsConfig( 4765): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 4765): serviceId : 1, features : -1
D/EasySignUpManager_1.0.1( 4765): isAuth is false
D/Mms/MmsConfig( 4765): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1491): query,matched:2117, calling pid = 4765
,D/TP/MmsSmsProvider( 1491): match 2117:Elapsed time : 2.678 ms
,D/EasySignUpManager_1.0.1( 4765): isAuth is false
D/EasySignUpManager_1.0.1( 4765): getServiceStatus : serviceId (1) is OFF
,W/libprocessgroup( 1022): failed to open /acct/uid_10068/pid_4362/cgroup.procs: No such file or directory
,E/CscParser( 4765): mps_code.dat does not exist
E/CscParser( 4765): customer_path =/system/csc/customer.xml
E/CscParser( 4765): fileName + /system/csc/customer.xml
,I/ActivityManager( 1022): Killing 4407:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,E/CscParser( 4765): mps_code.dat does not exist
E/CscParser( 4765): customer_path =/system/csc/customer.xml
E/CscParser( 4765): fileName + /system/csc/customer.xml
,D/CscParser( 4765): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 4765):  enable multiwindow = false
,E/Mms/MessageUtils( 4765): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 4765): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 4765): [end]    init() consume time = 110.159219
,D/Mms/Contact( 4765): [start]    init() consume time = 0.604635
,D/TP/MmsSmsProvider( 1491): query,matched:13, calling pid = 4765
,D/TP/MmsSmsProvider( 1491): match 13:Elapsed time : 1.621 ms
,D/Mms/Contact( 4765): [end]    init consume time = 9.311198
,D/Mms/DraftCache( 4765): [start]    rebuildCache consume time = 4.998073
,D/Mms/MethodReflector( 4765): getSubId is called
,D/Mms/TelephonyUtils( 4765): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4765): getTelephonyProperty is called
D/Mms/DownloadManager( 4765): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4765): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4765): auto download without roaming -> true
D/Mms/DownloadManager( 4765): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/MethodReflector( 4765): getSubId is called
,D/TP/MmsSmsProvider( 1491): query,matched:12, calling pid = 4765
,D/TP/MmsSmsProvider( 1491): match 12:Elapsed time : 1.542 ms
,D/Mms/MethodReflector( 4765): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 4765): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 4765): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 4765): getTelephonyProperty is called
D/Mms/DownloadManager( 4765): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4765): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 4765): auto download without roaming -> true
D/Mms/DownloadManager( 4765): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 4765): auto download during roaming secondary -> false
D/Mms/DownloadManager( 4765): mAutoDownload ------> true
,D/Mms/DraftCache( 4765): [end]    rebuildCache consume time = 11.667344
,D/ComposerPerformance( 4765): 1457354151894 ms / [DONE] Composer constructor
,D/Mms/Conversation( 4765): [start]    init() consume time = 11.316875
,D/TP/MmsSmsProvider( 1491): deleteConversation threadId: 9223372036854775807
,D/Mms/ArtClassLoader( 4765): init [DONE] art
,E/CII     ( 4765): CommonIMSInterface: VoLTE CSC feature disabled.
,D/TP/MmsSmsProvider( 1491): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1491): updateThread(), thread_id = 9223372036854775807
,I/Mms/ReservationManager( 4765): ReservationManager()
,I/Mms/ReservationManager( 4765): resetAfterConnected()
,V/TP/MmsSmsDatabaseHelper( 1491): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1491): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1491): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1491): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1491): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1491): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1491): (284) automatic index on im_threads(normal_thread_id)
,D/TP/MmsSmsProvider( 1491): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1491): need read changed broadcast:false
,D/Mms/Conversation( 4765): [end]    init consume time = 25.496406,
,D/TP/MmsSmsProvider( 1491): query,matched:7, calling pid = 4765
D/Mms/MessagingNotification( 4765): [start]    init() consume time = 2.195156,
D/TP/MmsSmsProvider( 1491): match 7:Elapsed time : 2.496 ms
,D/Mms/MessagingNotification( 4765): [end]    init consume time = 3.528334
,I/Mms/ReservationManager( 4765): getReservedSendMessageCount(): retMessageCount=0
,D/TP/MmsSmsProvider( 1491): query,matched:0, calling pid = 4765
,V/TP/MmsSmsProvider( 1491): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1491): match 0:Elapsed time : 1.960 ms
,D/Mms/MmsApp( 4765): [end]    onCreate() consume time = 1.024896
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_4407/cgroup.procs: No such file or directory
D/Mms/Synchronizer( 4765): [start]    doSync consume time = 9.840937
,D/Mms/SpamFilter( 4765): [start]    SpamFilter fill() begin consume time = 2.052552
,D/Mms/DownloadManager( 4765): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 4765): roaming ------> false, mSimSlot = 0
,D/TP/MmsSmsProvider( 1491): update, matched:300, calling pid = 4765
,V/TP/MmsSmsProvider( 1491): syncDBData start
,V/TP/MmsSmsProvider( 1491): syncDBData sms end
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
D/Mms/MethodReflector( 4765): getSubId is called
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
D/Mms/TelephonyUtils( 4765): getLongSubId from simSlot 0, return Value = -1
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,V/TP/MmsSmsProvider( 1491): syncDBData mms end
D/Mms/MethodReflector( 4765): getTelephonyProperty is called
D/Mms/DownloadManager( 4765): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4765): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4765): auto download without roaming -> true
D/Mms/DownloadManager( 4765): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/DownloadManager( 4765): mAutoDownload ------> true
,V/TP/MmsSmsProvider( 1491): syncDBData end
,E/Zygote  ( 4862): MountEmulatedStorage()
I/libpersona( 4862): KNOX_SDCARD checking this for 10068
E/Zygote  ( 4862): v2
I/libpersona( 4862): KNOX_SDCARD not a persona
,I/SELinux ( 4862): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4862 uid=10068 gids={50068, 9997} abi=armeabi-v7a
I/SELinux ( 4862): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/splitIntent( 1022): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/ActivityManager( 1022): Killing 4471:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
E/SELinux ( 4862): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/Mms/Synchronizer( 4765): [end]    doSync consume time = 29.234636
,W/ActivityManager( 1022): userId = 0, bbcId = -10000,
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/MmsSmsProvider( 1491): query,matched:400, calling pid = 4765
,D/CustomFrequencyManagerService( 1022): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@7
,I/Timeline( 1022): Timeline: Activity_windows_visible id: ActivityRecord{2fd85099 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t12} time:51849
W/ActivityManager( 1022): mDVFSHelper.release()
,I/SurfaceFlinger(  259): id=13 Removed Mauncher (5/8)
,I/SurfaceFlinger(  259): id=13 Removed Mauncher (-2/8)
,D/CustomFrequencyManagerService( 1022): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/Launcher.HomeView( 1511): onStop
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,V/ActivityThread( 1511): updateVisibility : ActivityRecord{225f14ea token=android.os.BinderProxy@3f657c28 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,D/Launcher( 1511): onTrimMemory. Level: 20
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TimaKeyStoreProvider( 4862): TimaSignature is unavailable
,D/ActivityThread( 4862): Added TimaKeyStore provider
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1022): Killing 4490:com.sec.modem.settings/1000 (adj 15): empty #31
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/SpamFilter( 4765): [end]    SpamFilter fill() finished consume time = 56.464166
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/BadgeProvider( 4862): onCreate
D/BadgeProvider( 4862): DatabaseHelper
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1022): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1022): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1022): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1022): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1834): [252] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1022): failed to open /acct/uid_10148/pid_4471/cgroup.procs: No such file or directory
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_4490/cgroup.procs: No such file or directory
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/MessagingNotification( 4765): checkBadgeCount unreadCount=0 badgeCount=0
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1491): query,matched:26, calling pid = 4765
,D/TP/SmsProvider( 1491): match 26:Elapsed time : 2.049 ms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2121): Restart initialization of location
,D/AuthorizationBluetoothService( 1834): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1834): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsSmsProvider( 1491): query,matched:6, calling pid = 4765,
,D/TP/MmsSmsProvider( 1491): match 6:Elapsed time : 1.122 ms
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1834): No location to return for getLastLocation()
,W/FusedLocationProvider( 1834): location=null
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4882): MountEmulatedStorage()
,E/Zygote  ( 4882): v2
I/libpersona( 4882): KNOX_SDCARD checking this for 10023
I/ActivityManager( 1022): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4882 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,I/libpersona( 4882): KNOX_SDCARD not a persona
,I/SELinux ( 4882): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
I/SELinux ( 4882): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4882): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4882): TimaSignature is unavailable
,D/ActivityThread( 4882): Added TimaKeyStore provider
,I/ActivityManager( 1022): Killing 4169:com.android.vending/u0a26 (adj 15): empty #31
,I/ActivityManager( 1022): Waited long enough for: ServiceRecord{1399c79a u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4898): MountEmulatedStorage()
,E/Zygote  ( 4898): v2
I/libpersona( 4898): KNOX_SDCARD checking this for 1000
,I/SELinux ( 4898): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4898): KNOX_SDCARD not a persona
I/ActivityManager( 1022): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4898 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4898): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4898): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CustomFrequencyManagerService( 1022): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@11
,D/Mms/Contact( 4765): sContactsObserver.onChange(),selfUpdate=false
,I/ValidateNoPeople( 1022): mEvictionCount: 0
,D/TimaKeyStoreProvider( 4898): TimaSignature is unavailable
,D/ActivityThread( 4898): Added TimaKeyStore provider
,D/Mms/Contact( 4765): performUpdate:widgetCount=0
,D/Mms/ContactsCache( 4765): [start]    invalidate() consume time = 297.110781
D/Mms/ContactsCache( 4765): [end]    invalidate() consume time = 0.133438
,E/SMD     (  290): DCD OFF
,E/MTPRx   ( 4898): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1022): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1022): mCursor = null
,W/libprocessgroup( 1022): failed to open /acct/uid_10026/pid_4169/cgroup.procs: No such file or directory
D/SecContentProvider2( 1022): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1022): mCursor = null
,I/OMACP   ( 4882): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
V/MTPRx   ( 4898): sealedState: false
V/MTPRx   ( 4898): sealedUsbMassStorageState: false
E/MTPRx   ( 4898): check value of boot_completed is1
E/MTPRx   ( 4898): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4898): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4898): Status for mount/Unmount :removed
E/MTPRx   ( 4898): SDcard is not available
,W/MTPRx   ( 4898): value of connected istrue
W/MTPRx   ( 4898): value of configured istrue
W/MTPRx   ( 4898): value of mtpEnabled istrue
W/MTPRx   ( 4898): value of ptpEnabled isfalse
,E/MTPRx   ( 4898): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 4898): mFirstTime: false
,D/PackageManager( 1022): [MSG] SEND_PENDING_BROADCAST
,D/Mms/Omacp( 4765): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,I/OMACP   ( 4882): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 4882): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 4882): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 4882): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 4882): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 4882): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 4882): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 4882): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 4882): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 4882): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 4882): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
I/OMACP   ( 4882): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 4882): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.PACKAGE_CHANGED
,D/        ( 4898): MTP: reading debug level property
,E/MTPJNIInterface( 4898): Getting CryptionKey from JAVA
E/MTPRx   ( 4898): currentUserId is 0
,E/MTPRx   ( 4898): Start observing USB_STATE_MATCH 
,I/PageBuddyNotiSvc( 4043): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,E/MTPRx   ( 4898): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 4898): is_Privatemode is NOT 1
,W/IntentResolver( 1022): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,D/SettingsProvider( 1022): name = boot_time_connected
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RegisteredServicesCache( 1469): empty dynamic service
,E/MTPRx   ( 4898): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 4898): noti = 17
,D/SettingsProvider( 1022): name = mtp_usb_conditions_met
,D/SecContentProvider( 1022): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 4898): sending MTP_ICON_ENABLED to stack
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1022): name = mtp_running_status
,D/SettingsProvider( 1022): name = mtp_usb_conditions_met
,E/MTPRx   ( 4898): else part ... so first time!!!
,E/MTPPlaObsrvr( 4898): inside setContext()
E/MTPPlaObsrvr( 4898):  inside createplafiles
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/MTPPlaObsrvr( 4898): playlist count is0
E/MTPPlaObsrvr( 4898):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4898):  inside deleteing plas createplafiles
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/MTPPlaObsrvr( 4898): Inside registerContentObserver
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1022): mCursor = null
,E/MtpAdbObserver( 4898): inside setContext()
E/MtpAdbObserver( 4898): Inside registerContentObserver
W/Settings( 4898): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1022): name = mtp_running_status
,D/SettingsProvider( 1022): name = mtp_usb_conditions_met
V/MtpMediaDBManager( 4898): inside deleteAllDB
,E/MtpService( 4898): onCreate.
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/MtpService( 1231): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpService( 4898): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 4898): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
E/MtpService( 4898): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 4898): onStartCommand.
,W/MTPRx   ( 4898): calling native method,
E/MTPJNIInterface( 4898): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 4898): handleMessage. msg= { when=-8ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,V/MtpMediaDBManager( 4898): inside Thread updateDB,
,E/Zygote  ( 4918): MountEmulatedStorage()
,E/Zygote  ( 4918): v2
I/libpersona( 4918): KNOX_SDCARD checking this for 1000
I/libpersona( 4918): KNOX_SDCARD not a persona,
I/SELinux ( 4918): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4918): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4918): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4918 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/MTPJNIInterface( 4898): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 4898): noti = 10
E/MtpService( 4898): onStartCommand.
,W/MTPRx   ( 4898): calling native method
E/MTPRx   ( 4898): Checking the driver time out
E/MTPJNIInterface( 4898): noti = 2
E/MtpService( 4898): handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,D/        ( 4898): deleting sockets before message queue initialization
,D/        ( 4898): event handler thread is created, so set the flag
,E/MTPRx   ( 4898): called native method
E/MTPJNIInterface( 4898): setting Media scanner status0
E/MTPJNIInterface( 4898): After setting Media scanner status0
,W/MTPRx   ( 4898): notification from stack 1
,E/        ( 4898): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4898): Getting media scanner status0
E/MTPJNIInterface( 4898): DeviceName is Thali Test (Galaxy A3)
,I/art     (  307): Explicit concurrent mark sweep GC freed 8704(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 29.804ms
,E/MtpMediaDBManager( 4898): count : 26
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 723us total 18.593ms
,W/MtpMediaDBManager( 4898): sending db update complete noti to stack
E/MTPJNIInterface( 4898): noti = 29
,W/ResourceType( 1022): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/TimaKeyStoreProvider( 4918): TimaSignature is unavailable
D/ActivityThread( 4918): Added TimaKeyStore provider
,E/SQLiteLog( 4898): (5) database is locked
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 25.346ms
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/MTPJNIInterface( 4898): Status for mount/Unmount :removed
E/MTPJNIInterface( 4898): SDcard is not available
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService( 1022): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1022): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/BackupManagerService( 1022): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1022): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1022): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1022): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/        ( 4898): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 4898): Status for mount/Unmount :removed
E/MTPJNIInterface( 4898): SDcard is not available
E/SQLiteLog( 4898): (21) API call with NULL database connection pointer
E/SQLiteLog( 4898): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4898): (21) API call with NULL database connection pointer
E/SQLiteLog( 4898): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4898): (21) API call with NULL database connection pointer
E/SQLiteLog( 4898): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4898): (21) API call with NULL database connection pointer
E/SQLiteLog( 4898): (21) misuse at line 106108 of [9491ba7d73]
,V/BackupManagerService( 1022): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/MTPRx   ( 4898): notification from stack 2
,V/BackupManagerService( 1022): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@29d9c09f
,D/        ( 4898): [mtp_init_device] Library open with 32 bits.
,D/        ( 4898): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 4898): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 4898): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 4898):  [sua_support_present:1287] returning false 
D/        ( 4898): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
