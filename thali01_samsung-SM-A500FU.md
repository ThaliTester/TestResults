#### Test 62560673e7cbba2_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
E/Zygote  ( 4025): MountEmulatedStorage()
E/Zygote  ( 4025): v2
I/SELinux ( 4025): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
--------- beginning of system
I/libpersona( 4025): KNOX_SDCARD checking this for 10033
I/libpersona( 4025): KNOX_SDCARD not a persona
I/System.out( 1930): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1930): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1930): (HTTPLog)-Static: isShipBuild true
I/System.out( 1930): (HTTPLog)-Thread-179-638350483: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1930): (HTTPLog)-Static: isSBSettingEnabled false
I/SELinux ( 4025): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
E/SELinux ( 4025): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4025 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/TimaKeyStoreProvider( 4025): TimaSignature is unavailable
D/ActivityThread( 4025): Added TimaKeyStore provider
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/System.out( 1930): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1930): Tagging socket 54 with tag 3000040100000000{805307393,0} for uid 10012, pid: 1930, getuid(): 10012
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Gmail   ( 3886): Error finding the version of the Email provider.....
E/Gmail   ( 3886): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3886): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3886): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 3886): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3886): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3886): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3886): We do not support migrating this version of the Email provider.
E/Zygote  ( 4054): MountEmulatedStorage()
I/libpersona( 4054): KNOX_SDCARD checking this for 10104
E/Zygote  ( 4054): v2
I/libpersona( 4054): KNOX_SDCARD not a persona
I/SELinux ( 4054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4054 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/SELinux ( 4054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4054): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/GoogleHttpClient( 1667): GMS http client unavailable, use old client
I/qtaguid ( 1930): Tagging socket 67 with tag 3000040100000000{805307393,0} for uid 10012, pid: 1930, getuid(): 10012
D/TimaKeyStoreProvider( 4054): TimaSignature is unavailable
D/ActivityThread( 4054): Added TimaKeyStore provider
I/AMMetaDataParserService( 3901): Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
W/ResourcesManager( 4054): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/Finsky  ( 3978): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/art     ( 3858): Suspending all threads took: 6.989ms
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
W/ContextImpl( 3901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 3886): Observing account changes for notifications
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:assistant
I/AMMetaDataParserService( 3901): Resource data:2131034113
W/ResourcesManager( 3901): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3901): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3901): getResourceTypeNamexml
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 3886): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@a36a5fb that was originally bound here
E/ActivityThread( 3886): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@a36a5fb that was originally bound here
E/ActivityThread( 3886): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3886): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3886): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3886): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3886): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3886): 	at com.android.emailcommon.service.ah.a(SourceFile:181)
E/ActivityThread( 3886): 	at com.android.emailcommon.service.ah.e(SourceFile:224)
E/ActivityThread( 3886): 	at com.android.email.service.n.c(SourceFile:161)
E/ActivityThread( 3886): 	at com.android.email.provider.b.a(SourceFile:173)
E/ActivityThread( 3886): 	at com.android.email.provider.b.a(SourceFile:117)
E/ActivityThread( 3886): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
E/ActivityThread( 3886): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
E/ActivityThread( 3886): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3886): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1016): Unbind failed: could not find connection for android.os.BinderProxy@11eeff88
E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX construct_block_size_descriptor_2d second part( 3901): took 2.413438ms for 0*0 texture 0
D/PowerManagerService( 1016): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1178 (0x0)
I/GFX generate_partition_tables( 3901): took 6.127187ms for 0*0 texture 0
I/GFX raster( 3901): took 9.817864ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb741fdc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7420150 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3901): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
I/System.out( 3341): Thread-512 calls detatch()
I/DBG_DM  ( 3238): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
D/AndroidRuntime( 4061): 
D/AndroidRuntime( 4061): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4061): CheckJNI is OFF
D/AndroidRuntime( 4061): readGMSProperty: start
D/AndroidRuntime( 4061): readGMSProperty: already setted!!
D/AndroidRuntime( 4061): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4061): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4061): readGMSProperty: end
D/AndroidRuntime( 4061): addProductProperty: start
D/Finsky  ( 3978): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
E/AffinityControl( 4061): AffinityControl: registerfunction enter
D/GCM     ( 1930): COMPAT: Multi user not supported
D/AndroidRuntime( 4061): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/Settings( 3978): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1016): mDVFSHelper.acquire()
W/Settings( 3978): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/FocusedStackFrame( 1016): Set to : 0
D/Launcher.HomeView( 1507): onPause
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1016): Focused application set to: xxxx
D/Launcher( 1507): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/InputDispatcher( 1016): Focus left window: 1507
D/AndroidRuntime( 4061): Shutting down VM
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : -2122120936
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=10 createSurf (1x1),1 flag=404, uhalitest
E/Zygote  ( 4101): MountEmulatedStorage()
W/ContextImpl( 3946): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
E/Zygote  ( 4101): v2
I/libpersona( 4101): KNOX_SDCARD checking this for 10155
I/SELinux ( 4101): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4101): KNOX_SDCARD not a persona
I/SELinux ( 4101): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4101): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4101 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3901): took 0.844688ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb741fdc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74281e0 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3901): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
V/ActivityThread( 1507): updateVisibility : ActivityRecord{315901d token=android.os.BinderProxy@241dfac5 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.bcservice, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 4025): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4025): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4025): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/art     (  302): Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 673us total 54.964ms
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 19.428ms
W/ResourcesManager( 4025): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4025): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4025): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 4101): TimaSignature is unavailable
D/ActivityThread( 4101): Added TimaKeyStore provider
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 658us total 20.529ms
W/ResourcesManager( 4025): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4025): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 4025): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/System.out( 3858): INFO:Resource not found:/Common.properties Using default values
E/Zygote  ( 4119): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4119 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 4119): v2
I/libpersona( 4119): KNOX_SDCARD checking this for 1000
I/SELinux ( 4119): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4119): KNOX_SDCARD not a persona
I/SELinux ( 4119): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
E/SELinux ( 4119): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Launcher.HomeView( 1507): onStop
V/ActivityThread( 1507): updateVisibility : ActivityRecord{315901d token=android.os.BinderProxy@241dfac5 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1016): isKioskContainerExistOnDevice
D/TimaKeyStoreProvider( 4119): TimaSignature is unavailable
D/ActivityThread( 4119): Added TimaKeyStore provider
E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX construct_block_size_descriptor_2d second part( 3901): took 2.910156ms for 0*0 texture 0
W/art     ( 4061): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/GFX generate_partition_tables( 3901): took 7.695938ms for 0*0 texture 0
,I/Gmail   ( 3886): getAccountsCursor
I/GFX raster( 3901): took 11.760627ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb74249e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7424b50 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531,
,W/SEAMService( 1016):  hashset_to_int_array returning null
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/PCWCLIENTTRACE_AccountAppFacade2_0( 3444): unregister AuthInfo UpdateReceiver v2.0
,V/GLSActivity( 1930): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/SEAMService( 1016):  hashset_to_int_array returning null
,D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,W/ResourcesManager( 4119): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/SensorService( 1016): [SO] activate (ident=0xb7a88858, enabled=0)
,I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/Launcher( 1507): onTrimMemory. Level: 20
,D/SensorManager( 1016): unregisterListener ::   
,I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1016): [SO] changed settle time [1]
,D/SensorService( 1016): [SO] setDelay [66000000]
D/SensorService( 1016): [SO] activate (ident=0xb7a88858, enabled=1)
,D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,E/SQLiteLog( 3946): (284) automatic index on seams_container_info(seams_container_id)
,E/SQLiteLog( 3946): (284) automatic index on seams_container_info(sp_id)
,D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,W/SEAMService( 1016):  hashset_to_int_array returning null
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.612240ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb74293b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7429520 counterpartCT=4 counterpartW=96 counterparth=96
,W/art     ( 3858): Suspending all threads took: 22.146ms
I/ActivityManager( 1016): Killing 3324:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,W/ContextImpl( 4119): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,D/Volley  ( 3978): [596] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager( 1016): Killing 3399:com.fmm.dm/1000 (adj 15): empty #31
,D/Volley  ( 3978): [603] DiskBasedCache.clear: Cache cleared.
,I/AMMetaDataParserService( 3901): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.882813ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7425eb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7426020 counterpartCT=4 counterpartW=96 counterparth=96
,E/SQLiteLog( 3886): (283) recovered 28 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/AMMetaDataParserService( 3901): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/WebViewFactory( 4101): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/Finsky  ( 3978): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3978): [1] Libraries$2.run: Finished loading 1 libraries.
,D/SensorService( 1016): [SO] currT = 43490311440, prevT = 43190207534, diff = 300103906, [0.134 0.364 10.151]
,D/SensorService( 1016): [SO] 0.134 0.364 10.151
D/SensorService( 1016): [SO] [100 -> 255]
,I/LibraryLoader( 4101): Time to load native libraries: 2 ms (timestamps 3493-3495)
,I/LibraryLoader( 4101): Expected native library version number "",actual native library version number ""
,D/FileApkUtils( 2109): Optimizing (staging complete)
,D/FileApkUtils( 2109): Optimizing: DynamiteModules-prod.apk [0224a548494bce36274e23f9f1b42d4fbe3d4d8de53a7872e503f8974e43c3c3]
,I/art     ( 2109): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,D/DexOptUtils( 2109): Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk appears to be unoptimized.
D/DexOptUtils( 2109): Lollipop platform, using <isa> directory.
D/DexOptUtils( 2109): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 2109): Primary ABI of odexing process is armeabi-v7a
E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3901): took 0.630416ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb74251c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7425328 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3324/cgroup.procs: No such file or directory
,D/Ads     ( 3978): Skipping gmscore version check
,I/F_PHONE ( 4119): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 4119): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,I/AMMetaDataParserService( 3901): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/ActivityManager( 1016): bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,V/WebViewChromiumFactoryProvider( 4101): Binding Chromium to main looper Looper (main, tid 1) {37db5ecc}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.721719ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7424850 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7424700 counterpartCT=4 counterpartW=96 counterparth=96
,I/LibraryLoader( 4101): Expected native library version number "",actual native library version number ""
,I/chromium( 4101): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/AMMetaDataParserService( 3901): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/Finsky  ( 3978): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/F_PHONE ( 4119): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 4119): default registerAction()
I/F_PHONE ( 4119): [[com.sec.bcservice]] sendPendingMessage()
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
I/BrowserStartupController( 4101): Initializing chromium process, singleProcess=true
,W/art     ( 4101): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4101): ApplicationContext is null in ApplicationStatus
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.531198ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7429010 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7422f70 counterpartCT=4 counterpartW=96 counterparth=96
,E/File    ( 3886): fail readDirectory() errno=2
,I/AMMetaDataParserService( 3901): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,W/chromium( 4101): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 4101): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 4101): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,D/Finsky  ( 3978): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Adreno-EGL( 4101): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4101): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4101): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4101): Local Branch: 
I/Adreno-EGL( 4101): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4101): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4101):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
,I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3901): Resource data:2131034113
,I/Gmail   ( 3886): notifyAccountChanged
,I/AMMetaDataParserService( 3901): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 3901): getResourceTypeNamexml
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.810521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb741fdc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7425e40 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/dex2oat ( 4150): ----------------------------------------------------
I/dex2oat ( 4150): <SS>: S T A R T I N G . . .
I/dex2oat ( 4150): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 4150): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/SMD     (  287): DCD OFF
,I/AMMetaDataParserService( 3901): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.810104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb741fdc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7425b38 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 3886): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/AMMetaDataParserService( 3901): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3399/cgroup.procs: No such file or directory
,I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/8)
,I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/8)
,I/System.out( 3382): Thread-488(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3382): Thread-488(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3382): Thread-488(ApacheHTTPLog):isShipBuild true
I/System.out( 3382): Thread-488(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3382): Thread-488(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10091
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10091
,I/DBG_DM  ( 3238): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,I/Gmail   ( 3886): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Babel   ( 4054): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 4054): MmsConfig.loadMmsSettings
,I/Babel   ( 4054): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 4054): MmsConfig.loadFromDatabase
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/chromium( 4101): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,I/Process ( 4025): Sending signal. PID: 4025 SIG: 9
,I/Gmail   ( 3886): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3886): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
E/Babel   ( 4054): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4054): MmsConfig.loadFromResources
D/SSRM:n  ( 1016): SIOP:: AP = 400
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/art     ( 4101): Attempt to remove local handle scope entry from IRT, ignoring
E/Babel   ( 4054): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4054): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/ActivityManager( 1016): Process com.sec.android.app.sns3 (pid 4025)(adj 0) has died(44,1162)
,W/AwContents( 4101): onDetachedFromWindow called when already detached. Ignoring
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4193): MountEmulatedStorage()
I/libpersona( 4193): KNOX_SDCARD checking this for 10034
E/Zygote  ( 4193): v2
I/libpersona( 4193): KNOX_SDCARD not a persona
I/SELinux ( 4193): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4193): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4193): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.629844ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb74249e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7425b38 counterpartCT=4 counterpartW=96 counterparth=96,
,D/PhoneWindow( 4101): *FMB* installDecor mIsFloating : false,
D/PhoneWindow( 4101): *FMB* installDecor flags : -2139027200
I/AMMetaDataParserService( 3901): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/ActivityManager( 1016): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4193 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a,
,D/SystemWebViewEngine( 4101): CordovaWebView is running on device made by: samsung
W/Settings( 4054): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/art     ( 4101): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4101): Attempt to remove local handle scope entry from IRT, ignoring
,D/TimaKeyStoreProvider( 4193): TimaSignature is unavailable
,D/ActivityThread( 4193): Added TimaKeyStore provider
,W/ResourcesManager( 3996): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/OpenGLRenderer( 4101): Render dirty regions requested: true
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
,D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,W/InstanceID/Rpc( 2109): Found 10012
,D/PhoneWindow( 4101): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 4101): *FMB* isFloatingMenuEnabled return false
,W/ResourcesManager( 3996): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3996): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3996): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 1930): Reading stored module config
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3901): took 1.125104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb74293b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7425b38 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530,
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.827605ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7425eb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7425b38 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.627240ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb741fcf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7425b38 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528,
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 43784(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/40MB, paused 2.647ms total 260.190ms
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, NainActivit
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.775364ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb73c6328 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb73e4778 counterpartCT=4 counterpartW=96 counterparth=96
,D/SecurityLogAgent:SEDenialService( 1016): Got CLOSE_WRITE Event sk.log
,D/SecurityLogAgent:SEDenialService( 1016): Got CLOSE_WRITE Event sk.log
I/AMMetaDataParserService( 3901): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/Babel_StickerModule( 4054): App launched.
,D/WearableService( 1930): callingUid 10012, callindPid: 1930
,D/InputDispatcher( 1016): Focus entered window: 4101
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,E/GmsWearableNodeHelper( 1930): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/SRIB_DCS( 4101): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 4101): Initialized EGL, version 1.4
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
W/art     ( 3858): Suspending all threads took: 14.961ms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/OpenGLRenderer( 4101): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 4101): Enabling debug mode 0
,I/ActivityManager( 1016): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4227 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 4227): MountEmulatedStorage()
I/libpersona( 4227): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4227): v2
I/libpersona( 4227): KNOX_SDCARD not a persona
I/SELinux ( 4227): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Killing 3300:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,I/SELinux ( 4227): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4227): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3901): took 0.539427ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7406e78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb73ddf80 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3901): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3901): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3901): getResourcePackageName:assistant
I/AMMetaDataParserService( 3901): Resource data:2131034112
,I/AMMetaDataParserService( 3901): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3901): getResourceTypeNamexml
E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.605104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb74293b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb73ff9a0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,I/AMMetaDataParserService( 3901): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.601094ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb74293b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7425b38 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1016): failed to open /acct/uid_10057/pid_3300/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4227): TimaSignature is unavailable
,D/ActivityThread( 4227): Added TimaKeyStore provider
,I/SamsungIME( 1842): getCurrentCandidateView
,I/AMMetaDataParserService( 3901): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,I/ActivityManager( 1016): Displayed Component not be shown by security: +1s634ms
,I/Timeline( 4101): Timeline: Activity_idle id: android.os.BinderProxy@16f3fd01 time:44682
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1016): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{1fce6d21 u0 com.test.thalitest/.MainActivity t12} time:44696
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.647864ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7407d60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb73ddf80 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/Babel   ( 4054): babel boot account: SMS,
,I/DBG_DM  ( 3238): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec,
,W/Babel   ( 4054): EsDatabaseHelper.static should not be called on main thread [called on main thread]
,W/BindingManager( 4101): Cannot call determinedVisibility() - never saw a connection for the pid: 4101
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/Babel   ( 4054): java.lang.Exception
W/Babel   ( 4054): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 4054): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 4054): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 4054): 	at ckh.a(SourceFile:67)
W/Babel   ( 4054): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 4054): 	at bhn.a(SourceFile:301)
W/Babel   ( 4054): 	at bhn.a(SourceFile:137)
W/Babel   ( 4054): 	at bhn.a(SourceFile:126)
W/Babel   ( 4054): 	at bhn.a(SourceFile:159)
W/Babel   ( 4054): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 4054): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 4054): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 4054): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 4054): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 4054): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 4054): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 4054): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 4054): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 4054): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 4054): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/GFX raster( 3901): took 0.671823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb741fcf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb73e4778 counterpartCT=4 counterpartW=96 counterparth=96
,W/Babel   ( 4054): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 4054): java.lang.Exception
W/Babel   ( 4054): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 4054): 	at aes.a(SourceFile:145)
W/Babel   ( 4054): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 4054): 	at ckh.a(SourceFile:67)
W/Babel   ( 4054): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 4054): 	at bhn.a(SourceFile:301)
W/Babel   ( 4054): 	at bhn.a(SourceFile:137)
W/Babel   ( 4054): 	at bhn.a(SourceFile:126)
W/Babel   ( 4054): 	at bhn.a(SourceFile:159)
W/Babel   ( 4054): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 4054): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 4054): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 4054): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 4054): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 4054): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 4054): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 4054): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 4054): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 4054): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 4054): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/AMMetaDataParserService( 3901): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
,D/SamsungIME( 1842): Dismiss ExpandCandiate
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:assistant
I/AMMetaDataParserService( 3901): Resource data:2131034113
,I/AMMetaDataParserService( 3901): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3901): getResourceTypeNamexml
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.813229ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7407a10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb73ff9a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/PeopleSync( 2109): Setting subscription: result=true [5005f081]
I/PeopleSync( 2109): Starting sync, feed=null [5005f081]
,I/SurfaceFlinger(  257): id=10 Removed uhalitest (7/8)
,I/SurfaceFlinger(  257): id=10 Removed uhalitest (-2/8)
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 4227): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 4227): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/AMMetaDataParserService( 3901): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@11
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/GFX raster( 3901): took 0.953906ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7407a10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7425b38 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/DBG_POLICYDM( 4227): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/DBG_POLICYDM( 4227): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,V/Babel   ( 4054): babel boot account: thalitester@gmail.com
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 2109): COMPAT: Multi user not supported
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.600729ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7407318 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb73ddf80 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4227): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,I/AMMetaDataParserService( 3901): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/Babel   ( 4054): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 4054): java.lang.Exception
W/Babel   ( 4054): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 4054): 	at aes.a(SourceFile:145)
W/Babel   ( 4054): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 4054): 	at ckh.a(SourceFile:67)
W/Babel   ( 4054): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 4054): 	at bhn.a(SourceFile:301)
W/Babel   ( 4054): 	at bhn.a(SourceFile:137)
W/Babel   ( 4054): 	at bhn.a(SourceFile:126)
W/Babel   ( 4054): 	at bhn.a(SourceFile:159)
W/Babel   ( 4054): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 4054): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 4054): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 4054): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 4054): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 4054): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 4054): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 4054): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 4054): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 4054): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 4054): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 4227): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.631927ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb74293b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb73ff9a0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3901): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/DBG_POLICYDM( 4227): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,I/GFX raster( 3901): took 0.840990ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7425eb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7425b38 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 3886): getAccountsCursor
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3901): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/JsMessageQueue( 4101): Set native->JS mode to OnlineEventsBridgeMode
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/DBG_POLICYDM( 4227): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 4227): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,I/DBG_POLICYDM( 4227): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/DBG_POLICYDM( 4227): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.651145ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb741fcf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb73e4778 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4227): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4267): MountEmulatedStorage()
E/Zygote  ( 4267): v2
I/libpersona( 4267): KNOX_SDCARD checking this for 1000
I/libpersona( 4267): KNOX_SDCARD not a persona
,I/SELinux ( 4267): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1016): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4267 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 4267): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4267): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GCoreUlr( 2109): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/ChimeraCfgMgr( 2109): Reading stored module config
I/ActivityManager( 1016): Waited long enough for: ServiceRecord{34aa440f u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,I/AMMetaDataParserService( 3901): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/TimaKeyStoreProvider( 4267): TimaSignature is unavailable
,D/ActivityThread( 4267): Added TimaKeyStore provider
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4283 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3461:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,E/Zygote  ( 4283): MountEmulatedStorage()
,E/Zygote  ( 4283): v2
I/libpersona( 4283): KNOX_SDCARD checking this for 10035
I/libpersona( 4283): KNOX_SDCARD not a persona,
,I/SELinux ( 4283): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4283): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4283): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/jxcore_app_log( 4101): JniHelper::setJavaVM(0xb704a450), pthread_self() = -1218853200
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4101): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4101):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4101):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4101):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4101):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4101): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2739bbc4 added. We now have 1 listener(s)
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.714219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb73c6328 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb73ddf80 counterpartCT=4 counterpartW=96 counterparth=96
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4101): setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4101): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4101): setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4101): load: ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4101):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4101):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4101):     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4101):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4101):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4101):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4101):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4101):     - Scan mode: 2,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4101):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4101): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33f8d030 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4101): addListener: New listener added - the number of listeners is now 1
,I/AMMetaDataParserService( 3901): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/CheckinService( 2109): Disabling old GoogleServicesFramework version
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  282): getCameraInfo: X
,D/TimaKeyStoreProvider( 4283): TimaSignature is unavailable
,D/ActivityThread( 4283): Added TimaKeyStore provider
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  282): getCameraInfo: X
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4101): setDiscoveryMode: Discovery mode BLE is supported
,D/BootCompletedReceiver( 2109): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 2109): Got an BootCompleted event.
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.534219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7406e78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7425b38 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527,
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
W/ContextImpl( 3901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4303): MountEmulatedStorage(),
E/Zygote  ( 4303): v2
I/libpersona( 4303): KNOX_SDCARD checking this for 1000
I/libpersona( 4303): KNOX_SDCARD not a persona
I/SELinux ( 4303): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4303): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
D/BootCompletedReceiver( 2109): Will NOT schedule AdAttestation signal task because it's disabled.
,D/SystemUpdateService( 2109): onCreate
,E/SELinux ( 4303): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4303 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3361:com.google.android.configupdater/u0a86 (adj 15): empty #31
,I/DBG_POLICYDM( 4227): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,W/libprocessgroup( 1016): failed to open /acct/uid_10003/pid_3461/cgroup.procs: No such file or directory
,I/chromium( 4101): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/TimaKeyStoreProvider( 4303): TimaSignature is unavailable
,D/ActivityThread( 4303): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:assistant
I/AMMetaDataParserService( 3901,): Resource data:2131165203
W/VideoCapabilities( 4054): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4054): Unsupported mime audio/evrc
W/AudioCapabilities( 4054): Unsupported mime audio/qcelp
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1445): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1445): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,I/DBG_POLICYDM( 4227): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4227): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 4227): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,I/DBG_DM  ( 3238): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,I/DBG_POLICYDM( 4227): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,V/HeadsetService( 2695): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2695): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/dex2oat ( 4150): Verification of void com.google.android.gms.ads.internal.formats.k.onGlobalLayout() took 109.614ms
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ResourcesManager( 3901): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3901): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/AudioCapabilities( 4054): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 4054): Unsupported mime audio/mpeg-L2
,I/AMMetaDataParserService( 3901): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3901): getResourceTypeNamexml
,D/SystemUpdateService( 2109): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3901): took 3.039740ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3901): took 11.428385ms for 0*0 texture 0
,I/GFX raster( 3901): took 15.628595ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb75d8510 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb75d8548 counterpartCT=4 counterpartW=96 counterparth=96
,W/dex2oat ( 4150): Verification of com.google.android.gms.ads.internal.formats.b com.google.android.gms.ads.internal.formats.i.a(android.view.View$OnClickListener) took 188.015ms
,I/AMMetaDataParserService( 3901): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,D/GCMRegistrar( 3484): resetting backoff for com.dropbox.android
,V/GCMRegistrar( 3484): Registering app com.dropbox.android of senders 735665981150
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 1.006615ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb75d8548 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb73e88e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,V/AuthZen ( 2109): Handling intent: android.intent.action.BOOT_COMPLETED
,I/DBG_POLICYDM( 4227): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,D/KnoxSetupWizardDbHelper( 4303): dbMigrationFlag : false
,E/SPPClientService( 4283): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4283): [PushClientApplication] Push log off : This is Ship build version
,W/libprocessgroup( 1016): failed to open /acct/uid_10086/pid_3361/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/SPPClientService( 4283): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,D/SPPClientService( 4283): PushLog.txt file is not deleted.
D/SPPClientService( 4283): PushLog.txt file is not deleted.
D/SPPClientService( 4283): ============PushLog. stop!
,I/DBG_POLICYDM( 4227): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.google.process.gapps
,D/ShortcutReceiver( 4303):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3901): took 0.787032ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb75d8548 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb73f6498 counterpartCT=4 counterpartW=96 counterparth=96
,D/KnoxShortcutUtil( 4303): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4303):  KnoxContainerVersion 2.4.0
,W/AudioCapabilities( 4054): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 4054): Unsupported mime audio/x-ima
,W/AudioCapabilities( 4054): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4054): Unsupported mime audio/evrc
,D/ShortcutReceiver( 4303):  shortcut migration not required 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3901): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 4054): Unsupported mime video/wvc1
,W/VideoCapabilities( 4054): Unsupported mime video/x-ms-wmv
,E/Zygote  ( 4332): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4332 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 4332): v2
I/libpersona( 4332): KNOX_SDCARD checking this for 1000
I/libpersona( 4332): KNOX_SDCARD not a persona
,I/SELinux ( 4332): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4332): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4332): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 3484:com.dropbox.android/u0a92 (adj 15): empty #31
,D/AuthZenEventHandler( 2109): Handling event: android.intent.action.BOOT_COMPLETED
,W/VideoCapabilities( 4054): Unrecognized profile/level 32768/2 for video/mp4v-es
,I/ActivityManager( 1016): Killing 3499:com.fmm.ds/1000 (adj 15): empty #31
,I/DBG_POLICYDM( 4227): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 4227): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 4227): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
I/DBG_POLICYDM( 4227): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.791458ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb75d8548 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb73fb3a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,I/CheckinService( 2109): Checking schedule, now: 1457713638164 next: 1458246240395
I/CheckinService( 2109): active receiver: disabled
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4332): TimaSignature is unavailable
,D/ActivityThread( 4332): Added TimaKeyStore provider
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/libpersona( 4347): KNOX_SDCARD checking this for 10041
E/Zygote  ( 4347): MountEmulatedStorage()
I/libpersona( 4347): KNOX_SDCARD not a persona
,E/Zygote  ( 4347): v2
I/GFX raster( 3901): took 0.628281ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb73f8f38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb73f9070 counterpartCT=4 counterpartW=96 counterparth=96
I/SELinux ( 4347): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4347): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4347): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4347 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3522:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,I/DBG_POLICYDM( 4227): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/TimaKeyStoreProvider( 4347): TimaSignature is unavailable
,D/ActivityThread( 4347): Added TimaKeyStore provider
,W/VideoCapabilities( 4054): Unsupported mime video/wvc1
,I/DBG_POLICYDM( 4227): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
,I/DBG_POLICYDM( 4227): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 4227): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/11/17:27:18
,I/DBG_POLICYDM( 4227): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 4227): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,W/VideoCapabilities( 4054): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 4054): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 4054): Unsupported mime video/x-ms-wmv8
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 4227): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0,
,I/DBG_POLICYDM( 4227): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0,
,I/DBG_POLICYDM( 4227): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0,
,I/DBG_POLICYDM( 4227): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.,
,W/VideoCapabilities( 4054): Unsupported mime video/mp43,
,I/SamsungIME( 1842): getDebugLevel  : 0x4f4c
,I/DBG_POLICYDM( 4227): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,W/VideoCapabilities( 4054): Unsupported mime video/sorenson
,I/DBG_POLICYDM( 4227): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 4227): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,E/KnoxSetupWizardClient( 4332): isShipMode : 1
,I/KnoxSetupWizardClient( 4332): onReceive : android.intent.action.BOOT_COMPLETED
,I/DBG_POLICYDM( 4227): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,I/AMMetaDataParserService( 3901): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/VideoCapabilities( 4054): Unsupported mime video/mp4v-esdp
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.616146ms for 96*96 texture 0
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb73f8f38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb73dd210 counterpartCT=4 counterpartW=96 counterparth=96
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/SamsungIME( 1842): getDebugLevel  : 0x4f4c
,I/DBG_POLICYDM( 4227): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,I/SamsungIME( 1842): KeybaordView init() : load resources
,I/AMMetaDataParserService( 3901): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
W/ContextImpl( 3901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3901): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/DBG_POLICYDM( 4227): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] ,
,I/SystemUpdateService( 2109): cancelUpdate (empty URL)
,I/SystemUpdateService( 2109): active receiver: disabled
,I/SamsungIME( 1842): getCurrentKeyboard
,I/SamsungIME( 1842): getTextKeyboard
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4368): MountEmulatedStorage(),
E/Zygote  ( 4368): v2
I/libpersona( 4368): KNOX_SDCARD checking this for 10107
I/libpersona( 4368): KNOX_SDCARD not a persona
,I/SELinux ( 4368): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4368): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4368): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4368 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3545:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,W/dex2oat ( 4150): Verification of byte[] com.google.maps.api.android.lib6.gmm6.streetview.r.a(com.google.maps.api.android.lib6.gmm6.streetview.r$a, long) took 116.362ms
,W/dex2oat ( 4150): Verification of void com.google.maps.api.android.lib6.gmm6.streetview.l.glTexEnvfv(int, int, java.nio.FloatBuffer) took 116.984ms
,W/dex2oat ( 4150): Verification of float[] com.google.maps.api.android.lib6.gmm6.streetview.w.a(boolean) took 115.269ms
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 4368): TimaSignature is unavailable
,D/ActivityThread( 4368): Added TimaKeyStore provider
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/VideoCapabilities( 4054): Unsupported profile 4 for video/mp4v-es
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 2109): Using Auth Proxy for data requests.
,I/SA      ( 4347): [SSP] onCreated
,D/SyncManager( 1016): handleSyncHandlerMessage: dropping since the sync is no longer active: startTime 37681, mTimeoutStartTime 37681, mHistoryRowId 11, syncOperation thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, LOCAL, currentRunTime 26873, reason: 10091
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
,W/libprocessgroup( 1016): failed to open /acct/uid_10092/pid_3484/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3499/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10060/pid_3522/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3901): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3901): getResourcePackageName:assistant
I/AMMetaDataParserService( 3901): Resource data:2131099648
,W/System.err( 4332): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 4332): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4332): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4332): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 4332): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
W/System.err( 4332): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4332): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,W/ResourcesManager( 3901): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3901): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3901): getResourceTypeNamexml
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.732605ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb741fb18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb73f1e88 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 3238): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_10062/pid_3545/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3901): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/BaseAppContext( 2109): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 2109): Using Auth Proxy for data requests.
,I/AuthZen ( 2109): Fetching signing key...
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,D/SamsungIME( 1842): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/GFX construct_block_size_descriptor_2d second part( 3901): took 2.866458ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3901): took 8.933230ms for 0*0 texture 0
,I/GFX raster( 3901): took 12.915261ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7926860 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7926908 counterpartCT=4 counterpartW=96 counterparth=96
,I/AuthZen ( 2109): Signing key fetched successfully!
,D/SystemUpdateService( 2109): onDestroy
,I/DBG_POLICYDM( 4227): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,I/AMMetaDataParserService( 3901): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/SA      ( 4347): [TPM] There is no property file
,I/SA      ( 4347): [SCU] isHaveSA() - false
,I/SA      ( 4347): [TPM] getModelProperty : null
I/SA      ( 4347): [TPM] getCSCProperty : null
,I/SA      ( 4347): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4347): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4347): [DM] TFT FEATURE: false
,I/DBG_POLICYDM( 4227): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.634895ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb79299b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7929a58 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/SA      ( 4347): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4347): [DM] init START
,W/dex2oat ( 4150): Verification of void maps.am.e.a() took 116.679ms
,W/BaseAppContext( 2109): Using Auth Proxy for data requests.
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.640469ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb74139d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7413a78 counterpartCT=4 counterpartW=96 counterparth=96
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,V/GLSActivity( 1930): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1930): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/SA      ( 4347): [DM] This device is not a Vodafone
,W/BaseAppContext( 2109): Using Auth Proxy for data requests.
,I/Gmail   ( 3886): getAccountsCursor
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,W/ResourceType( 4347): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4347): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4347): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4347): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4347): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4347): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4347): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4347): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4347): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4347): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4347): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4347): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4347): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4347): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,I/DBG_POLICYDM( 4227): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,W/ResourceType( 4347): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 4347): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4347): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 4347): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,I/AMMetaDataParserService( 3901): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ResourceType( 4347): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4347): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 4347): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 4347): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4347): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4347): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4347): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,W/art     ( 1842): Suspending all threads took: 16.440ms
,I/DBG_POLICYDM( 4227): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,I/SA      ( 4347): [SCU] isHaveSA() - false
I/SA      ( 4347): support phone number id : false
I/SA      ( 4347): [DM] Supports Ref Jpn : true
,I/SA      ( 4347): [DM] init END
,W/art     ( 4054): Suspending all threads took: 14.733ms
,I/SA      ( 4347): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 4347): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/ActivityManager( 1016): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/dex2oat ( 4150): Verification of void maps.an.c$a$a.a(maps.bu.a, com.google.android.gms.ads.internal.client.AdSizeParcel, com.google.android.gms.ads.internal.client.AdRequestParcel, java.lang.String, java.lang.String, maps.an.d) took 221.217ms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,W/dex2oat ( 4150): Verification of android.os.IBinder maps.ap.c$a$a.a(maps.bu.a) took 161.737ms
,I/SA      ( 4347): [OR] onReceive END
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3901): took 0.651823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7413718 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7926d28 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4409): MountEmulatedStorage(),
E/Zygote  ( 4409): v2
I/libpersona( 4409): KNOX_SDCARD checking this for 10042
I/libpersona( 4409): KNOX_SDCARD not a persona
,I/SELinux ( 4409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,W/jxcore-log( 4101): Initializing JXcore engine
W/jxcore-log( 4101): JXcore engine is ready
,I/SELinux ( 4409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 4409): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4409 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SA      ( 4347): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4347): [ODM] queryOpenData(key= GEO_IP )
,I/AMMetaDataParserService( 3901): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/TimaKeyStoreProvider( 4409): TimaSignature is unavailable
,D/ActivityThread( 4409): Added TimaKeyStore provider
,I/SA      ( 4347): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4347): [LBE] REF_JPN : true
,I/SA      ( 4347): [BDC] create
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.751511ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7927c38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7927ce0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,I/AMMetaDataParserService( 3901): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,E/audit   ( 1958): type=1400 msg=audit(1457713639.389:205): avc:  denied  { ioctl } for  pid=4302 comm="Thread-633" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1958):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1958): type=1300 msg=audit(1457713639.389:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9d6158f8 items=0 ppid=302 ppcomm=main pid=4302 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-633" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1958): type=1320 msg=audit(1457713639.389:205): 
,I/GAV2    ( 3886): Thread[GAThread,5,main]: No campaign data found.
,W/ResourcesManager( 4409): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/SQLiteLog( 4054): (284) automatic index on conversation_participants_view(conversation_id)
,W/jxcore-log( 4101): Starting JXcore engine
,I/SA      ( 4347): [DBMV2] getEmailID
,I/GCM     ( 1930): GCM config loaded
,I/SA      ( 4347): [DBMV2] getDataV02ForItems
I/SA      ( 4347): [SSP] query invoked
,I/SA      ( 4347): [SCU] get signed id from samsung account2.0 DB.
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:assistant
I/AMMetaDataParserService( 3901): Resource data:2131099648
,I/AMMetaDataParserService( 3901): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3901): getResourceTypeNamexml
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.689583ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb741fb18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb75d84d0 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4347): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4347): [BDC] destroy
,I/AMMetaDataParserService( 3901): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523,
I/ActivityManager( 1016): Killing 3563:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.658854ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7926860 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb75d84d0 counterpartCT=4 counterpartW=96 counterparth=96
,I/CalendarProvider2( 4409): CalendarProvider2.onCreate() called
,I/AMMetaDataParserService( 3901): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/SQLiteLog( 4054): (284) automatic index on conversation_participants_view(conversation_id)
,W/jxcore-log( 4101): Platform android
W/jxcore-log( 4101): 
W/jxcore-log( 4101): Process ARCH arm
W/jxcore-log( 4101): 
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.642188ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb79299b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb75d84d0 counterpartCT=4 counterpartW=96 counterparth=96
,E/SQLiteLog( 4054): (284) automatic index on conversation_participants_view(conversation_id)
,I/AMMetaDataParserService( 3901): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.655313ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb74139d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb75d84d0 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1016): failed to open /acct/uid_10092/pid_3563/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3901): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.654999ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7413718 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb75d84d0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/SQLiteLog( 4054): (284) automatic index on conversation_participants_view(conversation_id)
,I/SecDataIO(  256): Write to block
,E/SQLiteLog( 4054): (284) automatic index on conversation_participants_view(conversation_id)
,I/ActivityManager( 1016): Killing 3597:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ContextImpl( 2642): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
I/GFX raster( 3901): took 0.756979ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7927c38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb75d84d0 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 3238): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 3238): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,E/DBG_DM  ( 3238): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,I/DBG_DM  ( 3238): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/AMMetaDataParserService( 3901): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3901): getResourcePackageName:assistant
I/AMMetaDataParserService( 3901): Resource data:2131099648
,I/AMMetaDataParserService( 3901): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3901): getResourceTypeNamexml
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.711511ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb741fb18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb75d84d0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/Process ( 2642): Sending signal. PID: 2642 SIG: 9
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.721404ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7926860 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb741f670 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     ( 2109): Explicit concurrent mark sweep GC freed 18601(1436KB) AllocSpace objects, 19(303KB) LOS objects, 25% free, 11MB/15MB, paused 1.519ms total 543.206ms
,I/AMMetaDataParserService( 3901): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.683647ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb79299b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb75d84d0 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3597/cgroup.procs: No such file or directory
,I/ActivityManager( 1016): Process com.sec.android.app.sysscope (pid 2642)(adj 0) has died(37,1116)
,I/AMMetaDataParserService( 3901): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.659845ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb74139d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7929808 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.650155ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7413718 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7929808 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/DBG_DM  ( 3238): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.789688ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7927c38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74141a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
,I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:assistant
I/AMMetaDataParserService( 3901): Resource data:2131099648
,I/DBG_DM  ( 3238): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3238): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3238): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,I/AMMetaDataParserService( 3901): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3901): getResourceTypeNamexml
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.703594ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb741fb18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74141a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/DBG_DM  ( 3238): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/jxcore-log( 4101): JXcore Cordova bridge is ready!
I/jxcore-log( 4101): 
,W/jxcore-log( 4101): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 4101): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/ActivityManager( 1016): Killing 3289:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/System.out( 3382): cpb calls detatch()
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3238): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/DBG_DM  ( 3238): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,I/GFX raster( 3901): took 0.658853ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7926860 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb74141a8 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_DM  ( 3238): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/AMMetaDataParserService( 3901): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/StrictMode( 4368): StrictMode policy violation; ~duration=1134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4368): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4368): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4368): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4368): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4368): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4368): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4368): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4368): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4368): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4368): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4368): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4368): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4368): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4368): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4368): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4368): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4368): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4368): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4368): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4368): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4368): StrictMode policy violation; ~duration=1123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4368): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4368): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4368): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4368): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4368): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4368): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4368): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4368): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4368): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4368): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4368): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4368): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4368): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4368): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4368),: 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4368): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4368): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4368): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4368): StrictMode policy violation; ~duration=993 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4368): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4368): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4368): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4368): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4368): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4368): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4368): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4368): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4368): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4368): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4368): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4368): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4368): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4368): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4368): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4368): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4368): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4368): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4368): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4368): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4368): StrictMode policy violation; ~duration=993 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4368): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4368): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4368): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4368): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4368): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4368): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4368): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4368): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4368): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4368): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4368): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4368): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4368): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4368): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4368): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4368): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4368): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4368): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4368): StrictMode policy violation; ~duration=987 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4368): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4368): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4368): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4368): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4368): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4368): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4368): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4368): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4368): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4368): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4368): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4368): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4368): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4368): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4368): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4368): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4368): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4368): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4368): StrictMode policy violation; ~duration=771 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4368): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4368): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4368): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4368): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4368): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4368): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4368): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4368): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4368): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4368): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4368): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4368): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4368): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4368): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4368): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4368): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4368): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4368): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4368): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4368): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4368): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4368): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4368): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4368): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4368): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4368): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4368): StrictMode policy violation; ~duration=768 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4368): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4368): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4368): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4368): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4368): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4368): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4368): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4368): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4368): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4368): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4368): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4368): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4368): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4368): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4368): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4368): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4368): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4368): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4368): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4368): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4368): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4368): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4368): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4368): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4368): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4368): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4368): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4368): StrictMode policy violation; ~duration=521 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4368): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4368): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4368): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4368): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4368): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4368): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4368): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 4368): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4368): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4368): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4368): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4368): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4368): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4368): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4368): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4368): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4368): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4368): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4368): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4368): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4368): StrictMode policy violation; ~duration=520 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4368): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4368): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4368): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4368): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4368): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4368): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4368): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4368): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4368): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4368): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4368): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4368): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4368): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4368): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4368): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4368): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4368): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3901): took 0.665991ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb79299b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb74141a8 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3901): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/Zygote  ( 4441): MountEmulatedStorage()
E/Zygote  ( 4441): v2
I/libpersona( 4441): KNOX_SDCARD checking this for 1000
I/libpersona( 4441): KNOX_SDCARD not a persona
I/SELinux ( 4441): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4441): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4441): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4441 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/art     (  302): Explicit concurrent mark sweep GC freed 8759(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.478ms total 31.023ms
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3901): took 0.638281ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb74139d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74141a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 18.053ms
,I/AMMetaDataParserService( 3901): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.723906ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7413718 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74141a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 3238): [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 602us total 16.785ms
,D/TimaKeyStoreProvider( 4441): TimaSignature is unavailable
,I/DBG_DM  ( 3238): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,D/ActivityThread( 4441): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3901): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/DBG_DM  ( 3238): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 3238): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 3238): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,W/com.google.a.a.b.d.a( 4368): Application name is not set. Call Builder#setApplicationName.,
,I/DBG_DM  ( 3238): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:308289685,
,I/DBG_DM  ( 3238): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 3238): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.918750ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7927c38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74141a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/StatusChecker( 4441): onReceive : android.intent.action.BOOT_COMPLETED
W/libprocessgroup( 1016): failed to open /acct/uid_10009/pid_3289/cgroup.procs: No such file or directory
,I/StatusChecker( 4441): onReceive : net.mt.init : DONE
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3238): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity,
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:assistant
I/AMMetaDataParserService( 3901): Resource data:2131099648,
,I/AMMetaDataParserService( 3901): getResourceName:com.android.mms:xml/assistant_messaging,
I/ActivityManager( 1016): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4459 uid=10116 gids={50116, 9997} abi=armeabi-v7a
I/AMMetaDataParserService( 3901): getResourceTypeNamexml
I/ActivityManager( 1016): Killing 3616:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3901): took 0.977604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb741fb18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74141a8 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4459): MountEmulatedStorage(),
E/Zygote  ( 4459): v2
I/libpersona( 4459): KNOX_SDCARD checking this for 10116
,I/libpersona( 4459): KNOX_SDCARD not a persona
,I/SELinux ( 4459): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/AMMetaDataParserService( 3901): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523,
,I/SELinux ( 4459): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4459): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4459): TimaSignature is unavailable
,D/ActivityThread( 4459): Added TimaKeyStore provider
,I/DBG_DM  ( 3238): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3901): took 0.669584ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7926860 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb74141a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/PageBuddyNotiSvc( 4459): Intent received : action=android.intent.action.BOOT_COMPLETED
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.880885ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb79299b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb74141a8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ContextImpl( 4459): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,I/PageBuddyNotiSvc( 4459): onCreate mCpBitFlag=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3901): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521,
,E/Zygote  ( 4476): MountEmulatedStorage(),
E/Zygote  ( 4476): v2,
I/libpersona( 4476): KNOX_SDCARD checking this for 10125
I/libpersona( 4476): KNOX_SDCARD not a persona,
,I/SELinux ( 4476): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4476): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3901): took 0.828542ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb74139d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74141a8 counterpartCT=4 counterpartW=96 counterparth=96
E/SELinux ( 4476): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4476 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/AMMetaDataParserService( 3901): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/DBG_DM  ( 3238): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.834219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7413718 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7413760 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4476): TimaSignature is unavailable
,D/ActivityThread( 4476): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3901): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520,
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.778646ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7927c38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74141a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3901): getResourcePackageName:assistant
I/AMMetaDataParserService( 3901): Resource data:2131099648
,I/AMMetaDataParserService( 3901): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3901): getResourceTypeNamexml
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.793229ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb741fb18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7413760 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/DBG_DM  ( 3238): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.640521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7926860 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb74141a8 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1016): failed to open /acct/uid_10014/pid_3616/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3901): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/DBG_DM  ( 3238): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 678432842
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/DBG_DM  ( 3238): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,I/GFX raster( 3901): took 0.798124ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb79299b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7413760 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 3238): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3238): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,I/AMMetaDataParserService( 3901): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/art     ( 1667): Explicit concurrent mark sweep GC freed 5418(220KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 71.179ms total 1.435s
,W/SQLiteConnectionPool( 1667): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.716718ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb74139d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74141a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 34225(1973KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/40MB, paused 2.643ms total 172.871ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/DBG_DM  ( 3238): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,I/DBG_DM  ( 3238): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,I/DBG_DM  ( 3238): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,E/DBG_DM  ( 3238): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,W/GAV2    ( 3382): BaseSyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,E/DBG_DM  ( 3238): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@12f2b78c
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,I/GFX raster( 3901): took 0.636510ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7413718 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7413760 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3901): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ResourcesManager( 4476): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4476): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4476): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.726094ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7927c38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74141a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 3238): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,I/AMMetaDataParserService( 3901): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/DBG_DM  ( 3238): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,I/art     ( 1930): Explicit concurrent mark sweep GC freed 26856(1895KB) AllocSpace objects, 35(752KB) LOS objects, 40% free, 12MB/20MB, paused 1.426ms total 94.367ms
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
W/ContextImpl( 3901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3901): Resource data:Loop for ,running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3901): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:android.app.default_searchable,
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity,
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity,
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
,I/DBG_DM  ( 3238): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,W/ContextImpl( 3238): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:172 llllIIIllIllIlllIIlI.llIIIIlllllIIllIIllI:732 
,D/SettingsProvider( 1016): name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,D/QuickConnect( 4476): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/a       ( 2109): Opening database auth.proximity.permit_store...
,D/QuickConnect( 4476): Util.setSCRunningSetting - [value]0
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
,I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3901): Resource data:2131165197
,D/SettingsProvider( 1016): name = scon_is_running
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10125
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,D/AuthZenTransactionCache( 2109): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 2109): Clearing transaction cache
I/QuickConnect( 4476): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,W/ResourcesManager( 3901): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 3901): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,I/AMMetaDataParserService( 3901): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3901): getResourceTypeNamexml
,I/DBG_DM  ( 3238): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/QuickConnect( 4476): PeriphStartReceiver.onReceive - no need to start
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3901): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/ActivityManager( 1016): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4497 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,E/Zygote  ( 4497): MountEmulatedStorage()
I/libpersona( 4497): KNOX_SDCARD checking this for 10131
E/Zygote  ( 4497): v2
I/libpersona( 4497): KNOX_SDCARD not a persona
,I/SELinux ( 4497): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Killing 3633:com.wssnps/1000 (adj 15): empty #31
,I/SELinux ( 4497): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4497): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3901): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/GCoreUlr( 1930): DispatchingService.onCreate()
,W/BaseAppContext( 2109): Using Auth Proxy for data requests.
,D/TimaKeyStoreProvider( 4497): TimaSignature is unavailable
,D/ActivityThread( 4497): Added TimaKeyStore provider
,I/DBG_DM  ( 3238): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/AMMetaDataParserService( 3901): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/ResourcesManager( 4497): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4497): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4497): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/GCM     ( 1930): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,V/GLSActivity( 1930): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SamsungIME( 1842): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/AMMetaDataParserService( 3901): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/ActivityManager( 1016): Killing 3406:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3633/cgroup.procs: No such file or directory
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 1016): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ResourcesManager( 1178): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityEnabledState
D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1016): mCursor = null
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1016): mCursor = null
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1930): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/PeopleSync( 2109): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,D/SBrowserFeatureFlag( 4497): initialized in static block : loadCscFeatureValue() succeed! 
,I/DBG_DM  ( 3238): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,D/KnoxNotification( 1178): ----- inflateViews : modified publicViewLocal -----
,I/System.out( 1930): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3901): getResourcePackageName:assistant
I/AMMetaDataParserService( 3901): Resource data:2131165197
,I/CalendarProvider2( 4409): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/AMMetaDataParserService( 3901): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3901): getResourceTypeNamexml
,D/SecContentProvider2( 1016): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1016): mCursor = null
,I/AMMetaDataParserService( 3901): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/SecContentProvider2( 1016): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1016): mCursor = null
,D/KnoxNotification( 1178): ----- inflateViews : modified KnoxViewLocal -----
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
I/GCoreUlr( 1930): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/PersonaManager( 1178): PersonaID is invalid or persona doesn't exists. : 0
,W/dex2oat ( 4150): Verification of void maps.k.b$c.a(byte[], byte[]) took 185.003ms
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/dex2oat ( 4150): Verification of void maps.k.b$d.a(byte[], byte[]) took 187.205ms
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/OpenGLRenderer( 3238): Render dirty regions requested: true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,W/dex2oat ( 4150): Verification of void maps.k.b$g.a(byte[], byte[]) took 130.367ms
,W/dex2oat ( 4150): Verification of void maps.k.b$f.a(byte[], byte[]) took 216.094ms
,I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1016): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 19 -> 19
,D/DisplayPowerController( 1016): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  ( 1016): lcd : 56 +
,D/PowerManagerService( 1016): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 60 -> 60
D/DisplayPowerController( 1016): animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1016): lcd : 56 -
,D/lights  ( 1016): lcd : 60 +
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 60 -> 60
D/DisplayPowerController( 1016): animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/SRIB_DCS( 3238): log_dcs ThreadedRenderer::initialize entered! 
,I/Adreno-EGL( 3238): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3238): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3238): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3238): Local Branch: 
I/Adreno-EGL( 3238): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3238): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3238):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/OpenGLRenderer( 3238): Initialized EGL, version 1.4
I/DBG_DM  ( 3238): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/AMMetaDataParserService( 3901): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/lights  ( 1016): lcd : 60 -
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 60 -> 60
,D/DisplayPowerController( 1016): animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
,I/AMMetaDataParserService( 3901): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/OpenGLRenderer( 3238): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 3238): Enabling debug mode 0
,D/ManifestProvider( 4497): onCreate()
,I/DBG_DM  ( 3238): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 3238): [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,I/DBG_DM  ( 3238): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,W/dex2oat ( 4150): Verification of void maps.k.b$k.a(byte[], byte[]) took 113.943ms
,W/GCoreFlp( 1930): No location to return for getLastLocation()
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/FusedLocationProvider( 1930): location=null
,W/Auth    ( 1930): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/AMMetaDataParserService( 3901): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1016): failed to open /acct/uid_10015/pid_3406/cgroup.procs: No such file or directory
,E/NetworkSettingsReceiver( 4497): onReceive: android.intent.action.BOOT_COMPLETED
,W/dex2oat ( 4150): Verification of void maps.k.b$m.a(byte[], byte[]) took 142.385ms
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:assistant
I/AMMetaDataParserService( 3901): Resource data:2131165197
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3901): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3901): getResourceTypeNamexml
,I/AMMetaDataParserService( 3901): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/ActivityManager( 1016): Killing 3718:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1930): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 3901): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/GCoreFlp( 1930): No location to return for getLastLocation()
,W/FusedLocationProvider( 1930): location=null
,E/SBrowserFeatureFlag( 4497): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@31e58d91
,D/SBrowserFeatureFlag( 4497): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4497): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,E/Watchdog( 1016): !@Sync 1
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/SettingsProvider( 1016): name = audio_safe_volume_state,
,E/Zygote  ( 4531): MountEmulatedStorage(),
E/Zygote  ( 4531): v2
I/libpersona( 4531): KNOX_SDCARD checking this for 10135
I/libpersona( 4531): KNOX_SDCARD not a persona
,I/AMMetaDataParserService( 3901): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622,
I/SELinux ( 4531): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1016): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4531 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 4531): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 4531): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4531): TimaSignature is unavailable
,D/ActivityThread( 4531): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 3746:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,D/PersistentNotificationBroadcastReceiver( 1930): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/AMMetaDataParserService( 3901): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4531): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
W/ContextImpl( 3901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,W/ResourcesManager( 4531): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4531): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3901): getResourcePackageName:assistant
I/AMMetaDataParserService( 3901): Resource data:2131099648
,W/ResourcesManager( 3901): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3901): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3901): getResourceTypeNamexml
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3901): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,I/GCoreUlr( 1930): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.apps.docs, action: android.content.SyncAdapter
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1016): failed to open /acct/uid_10022/pid_3718/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3746/cgroup.procs: No such file or directory
,E/SMD     (  287): DCD OFF
,I/AMMetaDataParserService( 3901): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511,
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ContextImpl( 3901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
I/GCoreUlr( 1930): Unbound from all location providers
I/GCoreUlr( 1930): Place inference reporting - stopped
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/System.out( 1930): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1930): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1930): Tagging socket 87 with tag 3000040100000000{805307393,0} for uid 10012, pid: 1930, getuid(): 10012
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4557): MountEmulatedStorage()
E/Zygote  ( 4557): v2
I/libpersona( 4557): KNOX_SDCARD checking this for 10139
I/libpersona( 4557): KNOX_SDCARD not a persona
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/SELinux ( 4557): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/AMMetaDataParserService( 3901): getResourcePackageName:assistant
I/AMMetaDataParserService( 3901): Resource data:2131165220
,I/SELinux ( 4557): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/GAV2    ( 3382): BaseSyncManager-thalitester@gmail.com: Need to call initialize() and be in fallback mode to start dispatch.,
,I/qtaguid ( 1930): Tagging socket 90 with tag 3000040100000000{805307393,0} for uid 10012, pid: 1930, getuid(): 10012,
,E/SELinux ( 4557): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4557 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
,I/AMMetaDataParserService( 3901): getResourceName:com.android.settings:xml/assistant
W/ResourcesManager( 3901): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3901): getResourceTypeNamexml
W/ResourcesManager( 3901): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.707917ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7b37808 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b37538 counterpartCT=4 counterpartW=96 counterparth=96
,I/GCoreUlr( 1930): DispatchingService.onDestroy()
,I/GCoreUlr( 1930): Stopping handler for UlrDispSvcFast
,I/AMMetaDataParserService( 3901): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,I/GCoreUlr( 1930): Unbound from all location providers
I/GCoreUlr( 1930): Place inference reporting - stopped
,D/TimaKeyStoreProvider( 4557): TimaSignature is unavailable
D/ActivityThread( 4557): Added TimaKeyStore provider
,W/ResourcesManager( 4557): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 4557): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4557): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4557): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4557): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/        ( 3901): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3901): took 0.624479ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3901): Bitmap=0xb7b37658 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b4aa00 counterpartCT=4 counterpartW=96 counterparth=96
,W/Flag    ( 3382): Duration spec must be at least 2 characters long
,I/AMMetaDataParserService( 3901): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4577): MountEmulatedStorage()
,E/Zygote  ( 4577): v2
I/libpersona( 4577): KNOX_SDCARD checking this for 10145
I/libpersona( 4577): KNOX_SDCARD not a persona
,I/SELinux ( 4577): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/dex2oat ( 4150): dex2oat took 6.329s (threads: 4),
,I/ActivityManager( 1016): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4577 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/SELinux ( 4577): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4577): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 3765:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings,.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settin,gs.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity,
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
,I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
,I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
,I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
,I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.LanguageSettings,
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
D/TimaKeyStoreProvider( 4577): TimaSignature is unavailable,
D/ActivityThread( 4577): Added TimaKeyStore provider
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity,
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
,I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
,I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
,I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
,I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
,I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ManageApplications
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
D/DexOptUtils( 2109): Odex created at:/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex
D/DexOptUtils( 2109): Set odex to world readable.
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/DexOptUtils( 2109): Renamed odex to /data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.odex
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePacka,geName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
W/ContextImpl( 3901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED,
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ApnEditor
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/ActivityManager( 1016): Killing 2816:com.google.android.apps.plus/u0a120 (adj 15): empty #31
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
,I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.RadioInfo
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
,I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataPa,rserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/ResourcesManager( 4577): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
W/ResourcesManager( 4577): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
W/ResourcesManager( 4577): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
W/ResourcesManager( 4577): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
W/ResourcesManager( 4577): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AM,MetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3901): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3901): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3901): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
I/DBG_POLICYDM( 4227): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
I/DBG_POLICYDM( 4227): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
I/DBG_POLICYDM( 4227): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
I/DBG_POLICYDM( 4227): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
I/DBG_POLICYDM( 4227): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
I/DBG_POLICYDM( 4227): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
I/DBG_POLICYDM( 4227): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/libprocessgroup( 1016): failed to open /acct/uid_10094/pid_3765/cgroup.procs: No such file or directory
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.PeopleSyncService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1016): failed to open /acct/uid_10120/pid_2816/cgroup.procs: No such file or directory
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 26873, reason: Periodic, SyncResult: syncAlreadyInProgress: true stats []
,I/System.out( 3382): Thread-497(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3382): Thread-497(ApacheHTTPLog):isShipBuild true
I/System.out( 3382): Thread-497(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3382): Thread-497(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4600): MountEmulatedStorage(),
I/libpersona( 4600): KNOX_SDCARD checking this for 10072
E/Zygote  ( 4600): v2
,I/libpersona( 4600): KNOX_SDCARD not a persona
D/RCPManagerService( 1016): exchangeData() failure , invalid userId,
I/SELinux ( 4600): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4600 uid=10072 gids={50072, 9997} abi=armeabi-v7a,
I/SELinux ( 4600): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4600): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): startService callerProcessName:com.android.email, calleePkgName: com.android.email
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,D/TimaKeyStoreProvider( 4600): TimaSignature is unavailable
,D/ActivityThread( 4600): Added TimaKeyStore provider
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 4600): onCreate
,E/Zygote  ( 4621): MountEmulatedStorage()
,E/Zygote  ( 4621): v2
I/libpersona( 4621): KNOX_SDCARD checking this for 10146
I/libpersona( 4621): KNOX_SDCARD not a persona
,I/SELinux ( 4621): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4621 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
D/BadgeProvider( 4600): DatabaseHelper
,I/SELinux ( 4621): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4621): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 3807:com.sec.factory.camera/1000 (adj 15): empty #31
I/ActivityManager( 1016): Killing 3789:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #32
,D/BadgeProvider( 4600): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 4600): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4600): sendNotify, [notify] : null
D/BadgeProvider( 4600): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4600): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4600): update, [UpdateCount] : 1
,D/TimaKeyStoreProvider( 4621): TimaSignature is unavailable
,D/ActivityThread( 4621): Added TimaKeyStore provider
,D/Launcher.Model( 1507): reloadBadges entered.
,W/ResourcesManager( 4621): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3789/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3807/cgroup.procs: No such file or directory
,I/System.out( 3382): cpb calls detatch()
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.appcert.AppCertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,I/Process ( 4577): Sending signal. PID: 4577 SIG: 9
,W/GAV2    ( 3382): BaseSyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,W/AppCertServiceClient( 2109): Interrupted when getting service: java.lang.InterruptedException
,E/lowmemorykiller(  254): Error writing /proc/4577/oom_score_adj; errno=22
,I/ActivityManager( 1016): Killing 3828:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
I/ActivityManager( 1016): Killing 3444:com.sec.pcw.device/1000 (adj 15): empty #32
,W/AbstractServer( 2109): GoogleAuthException while getting app cert is being ignored.
W/AbstractServer( 2109): com.google.android.gms.auth.p: Interrupted
W/AbstractServer( 2109): 	at com.google.android.gms.auth.b.a.a(:com.google.android.gms:124)
W/AbstractServer( 2109): 	at com.google.android.gms.auth.b.a.a(:com.google.android.gms:90)
W/AbstractServer( 2109): 	at com.google.android.gms.common.server.c.d(:com.google.android.gms:74)
W/AbstractServer( 2109): 	at com.google.android.gms.common.server.o.d(:com.google.android.gms:31)
W/AbstractServer( 2109): 	at com.google.android.gms.common.server.o.b(:com.google.android.gms:379)
W/AbstractServer( 2109): 	at com.google.android.gms.common.server.o.a(:com.google.android.gms:348)
W/AbstractServer( 2109): 	at com.google.android.gms.common.server.o.a(:com.google.android.gms:327)
W/AbstractServer( 2109): 	at com.google.android.gms.plus.service.v2whitelisted.b.a(:com.google.android.gms:1671)
W/AbstractServer( 2109): 	at com.google.android.gms.people.sync.x.g(:com.google.android.gms:1152)
W/AbstractServer( 2109): 	at com.google.android.gms.people.sync.x.a(:com.google.android.gms:246)
W/AbstractServer( 2109): 	at com.google.android.gms.people.sync.p.a(:com.google.android.gms:274)
W/AbstractServer( 2109): 	at com.google.android.gms.people.sync.p.a(:com.google.android.gms:189)
W/AbstractServer( 2109): 	at com.google.android.gms.people.sync.p.a(:com.google.android.gms:91)
W/AbstractServer( 2109): 	at com.google.android.gms.common.m.a.onPerformSync(:com.google.android.gms:98)
W/AbstractServer( 2109): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/PeopleSync( 2109): Sync finished, successful=false, took 1495ms
I/PeopleSync( 2109): Cancelled in volley
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/System.out( 2109): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 2109): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 2109): (HTTPLog)-Static: isShipBuild true
I/System.out( 2109): (HTTPLog)-Thread-247-594259773: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 2109): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 2109): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 2109): Tagging socket 39 with tag 3000150000000000{805311744,0} for uid 10012, pid: 2109, getuid(): 10012
,E/Zygote  ( 4640): MountEmulatedStorage()
E/Zygote  ( 4640): v2
I/libpersona( 4640): KNOX_SDCARD checking this for 1000
I/libpersona( 4640): KNOX_SDCARD not a persona
I/SELinux ( 4640): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4640 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{33744ea7 u0 com.samsung.android.providers.context/.ContextService}
I/SELinux ( 4640): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4640): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Process com.android.email (pid 4577)(adj 11) has died(56,1090)
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.exchange, calleePkgName: com.android.email
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1016): failed to open /acct/uid_10069/pid_3828/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4640): TimaSignature is unavailable,
,D/ActivityThread( 4640): Added TimaKeyStore provider
,E/Zygote  ( 4657): MountEmulatedStorage(),
E/Zygote  ( 4657): v2
I/libpersona( 4657): KNOX_SDCARD checking this for 10145
I/SELinux ( 4657): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/libpersona( 4657): KNOX_SDCARD not a persona
I/SELinux ( 4657): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4657 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3444/cgroup.procs: No such file or directory
,E/SELinux ( 4657): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4657): TimaSignature is unavailable
D/ActivityThread( 4657): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 3843:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4673): MountEmulatedStorage()
E/Zygote  ( 4673): v2
I/libpersona( 4673): KNOX_SDCARD checking this for 1000
I/libpersona( 4673): KNOX_SDCARD not a persona
,I/SELinux ( 4673): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/qtaguid ( 2109): Tagging socket 44 with tag 3000150000000000{805311744,0} for uid 10012, pid: 2109, getuid(): 10012
,I/SELinux ( 4673): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4673 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 4673): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 1272:com.android.defcontainer/u0a4 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4673): TimaSignature is unavailable
,D/ActivityThread( 4673): Added TimaKeyStore provider
,I/art     (  302): Explicit concurrent mark sweep GC freed 8732(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 655us total 24.437ms
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 18.824ms
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 603us total 17.060ms
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 38870(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 26MB/40MB, paused 2.530ms total 148.369ms
,W/ResourcesManager( 4657): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4657): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4657): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4657): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4657): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/SecurityLogAgent( 4673): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4673): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4673): StateMachine : Current State = 1
,D/SecurityLogAgent( 4673): BootReceiver : completed task. Failed to return wakelock . 
,I/splitIntent( 1016): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1016): Killing 3686:com.samsung.android.sm/1000 (adj 15): empty #31
,I/PeopleSync( 2109): ***Sync canceled***, duration: 10142 [5005f081]
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/libprocessgroup( 1016): failed to open /acct/uid_10100/pid_3843/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10004/pid_1272/cgroup.procs: No such file or directory
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1930): callingUid 10012, callindPid: 1930
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,E/MDM     ( 1930): [239] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2109): Restart initialization of location
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/TP/SmsProvider( 1485): query,matched:0, calling pid = 2109
,D/TP/SmsProvider( 1485): match 0:Elapsed time : 1.738 ms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 2109): Untagging socket 39
,D/BadgeProvider( 4600): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TP/MmsProvider( 1485): Query uri=content://mms, match=0, calling pid = 2109
,D/BadgeProvider( 4600): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4600): sendNotify, [notify] : null
D/BadgeProvider( 4600): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4600): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4600): update, [UpdateCount] : 1
D/Launcher.Model( 1507): reloadBadges entered.
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/ActivityManager( 1016): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/TP/SmsProvider( 1485): query,matched:0, calling pid = 2109
,D/TP/SmsProvider( 1485): match 0:Elapsed time : 1.365 ms
,I/Process ( 4621): Sending signal. PID: 4621 SIG: 9
,D/TP/MmsProvider( 1485): Query uri=content://mms, match=0, calling pid = 2109
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,D/AuthorizationBluetoothService( 1930): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/a       ( 1930): Opening database auth.proximity.permit_store...
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Process com.android.exchange (pid 4621)(adj 11) has died(46,1092)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{296e0308 u0 com.android.settings/.wifi.WifiCredService}
,W/IcingInternalCorpora( 2109): getNumBytesRead when not calculated.
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1930): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SyncManager( 1016): handleSyncHandlerMessage: dropping since the sync is no longer active: startTime 40475, mTimeoutStartTime 40475, mHistoryRowId 12, syncOperation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 82828, reason: Periodic
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3686/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/GCoreFlp( 1930): No location to return for getLastLocation()
,W/FusedLocationProvider( 1930): location=null
,I/Hs20UtilService( 2446): Starting #5
,I/Hs20UtilService( 2446): Message received 5007
,D/NearbySettings( 1357): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1357): MountReceiver.onReceive - Keep current state
,D/SensorService( 1016): [SO] 0.134 0.364 10.132
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2446): Starting #6
I/Hs20UtilService( 2446): Message received 5007
,D/NearbySettings( 1357): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1357): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1357): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1357): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1357): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1357): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2446): Starting #7
,D/NearbySettings( 1357): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/Hs20UtilService( 2446): Message received 5007
,I/NearbySettings( 1357): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1016): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityEnabledState
D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1016): mCursor = null
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1930): [254] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2109): Restart initialization of location
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1930): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1930): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/GCoreFlp( 1930): No location to return for getLastLocation()
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/FusedLocationProvider( 1930): location=null
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4726): MountEmulatedStorage()
,I/libpersona( 4726): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4726): v2
I/libpersona( 4726): KNOX_SDCARD not a persona
,I/SELinux ( 4726): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=4726 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4726): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4726): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 4726): TimaSignature is unavailable
,D/ActivityThread( 4726): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_LOG( 4726): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 4726): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 4726): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 4726): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4726): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 4726): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4726): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1016): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=10, mSplitNum[1]=17, mSplitNum[2]=26, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=34
,I/splitIntent( 1016): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4742): MountEmulatedStorage()
,E/Zygote  ( 4742): v2
I/libpersona( 4742): KNOX_SDCARD checking this for 10111
I/libpersona( 4742): KNOX_SDCARD not a persona,
,I/SELinux ( 4742): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4742 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4742): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4742): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3674): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Mar 11 17:27:23 GMT+01:00 2016
D/accuweather( 1768): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/SecurityLogAgent( 4673): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4673): KnoxConfiguration : Current State Mapping Found ,
D/SecurityLogAgent( 4673): StateMachine : Current State = 1
,D/SecurityLogAgent( 4673): StateMachine : Changed Current State = 1
,I/KLMS-2.5.183: ( 3674): KLMSAbstractReciever(): onReceive().END.
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,I/KLMS-2.5.183: ( 3674): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3674): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3674): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/Zygote  ( 4757): MountEmulatedStorage()
E/Zygote  ( 4757): v2
I/libpersona( 4757): KNOX_SDCARD checking this for 10159
I/libpersona( 4757): KNOX_SDCARD not a persona
I/SELinux ( 4757): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4757 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4757): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4757): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4742): TimaSignature is unavailable
,D/accuweather( 1768): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1768): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/ActivityThread( 4742): Added TimaKeyStore provider
D/accuweather( 1768): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1768): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/KLMS-2.5.183: ( 3674): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3674): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,D/accuweather( 1768): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1768): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4757): TimaSignature is unavailable
,I/KLMS-2.5.183: ( 3674): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
D/ActivityThread( 4757): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3674): StateImplV2(): networkChangeListener().START,
,E/Zygote  ( 4773): MountEmulatedStorage()
,E/Zygote  ( 4773): v2
I/libpersona( 4773): KNOX_SDCARD checking this for 10081
I/libpersona( 4773): KNOX_SDCARD not a persona
I/SELinux ( 4773): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/SELinux ( 4773): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4773 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 4773): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3674): NetworkChangeOperations(): uploadRequestLog().START 
,D/TimaKeyStoreProvider( 4773): TimaSignature is unavailable
,D/ActivityThread( 4773): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3674): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3674): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.183: ( 3674): KLMSIntentService(): onDestroy()
,E/SPPClientService( 4283): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/DBG_POLICYDM( 4227): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/DBG_POLICYDM( 4227): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 4227): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,I/SA      ( 4347): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 4347): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 4347): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4347): [SLFUCHKMGR] constructor called
,I/SA      ( 4347): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 4347): [OR] == isSIMCardReady false ==
,I/DBG_POLICYDM( 4227): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4227): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4227): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4227): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4227): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4227): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4227): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 4227): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,E/DBG_POLICYDM( 4227): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,I/DBG_POLICYDM( 4227): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 4347): [SCU] == networkStateCheck == true
,I/SA      ( 4347): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4347): isChinaCountryCode : false
I/SA      ( 4347): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 4347): [OR] == networkStateCheck true ==
,I/MusicStore( 4742): Database version: 108
,I/SA      ( 4347): [OR] GetMyCountryZoneTask
,I/SA      ( 4347): [OR] onReceive END
,V/DownloadManager( 1241): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/iu.SyncManager( 2109): SYNC; picasa accounts
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/NetworkLogImpl( 2109): Loaded NetworkSpeedPredictor
,I/iu.Environment( 2109): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SA      ( 4347): [SRS] prepareGetMyCountryZone
,D/SecContentProvider2( 1016): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1016): mCursor = null
,I/SA      ( 4347): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4347): [SSP] query invoked
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 4347): [TPMU] GetMccFromDB : null
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4805): MountEmulatedStorage()
E/Zygote  ( 4805): v2
I/libpersona( 4805): KNOX_SDCARD checking this for 10010
I/libpersona( 4805): KNOX_SDCARD not a persona
,I/SELinux ( 4805): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4805): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4805): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4805 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SA      ( 4347): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4347): [TPM] isNoProxy(default) : true
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1016): Killing 3901:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,I/iu.UploadsManager( 2109): num queued entries: 0
,I/iu.UploadsManager( 2109): num updated entries: 0
,I/iu.SyncManager( 2109): NEXT; no task
,E/File    ( 4347): fail readDirectory() errno=2
,D/TimaKeyStoreProvider( 4805): TimaSignature is unavailable
,D/ActivityThread( 4805): Added TimaKeyStore provider
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4821): MountEmulatedStorage(),
,E/Zygote  ( 4821): v2,
I/libpersona( 4821): KNOX_SDCARD checking this for 10113
I/libpersona( 4821): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4821 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1016): Killing 3341:com.google.android.youtube/u0a166 (adj 15): empty #31
,I/SELinux ( 4821): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4821): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4821): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4821): TimaSignature is unavailable
,D/ActivityThread( 4821): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3901/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/libprocessgroup( 1016): failed to open /acct/uid_10166/pid_3341/cgroup.procs: No such file or directory
,W/ResourcesManager( 4742): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4742): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4742): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/WaitQueueForNetworkActivate( 4805): notifyNetworkActivated
,W/ActivityThread( 4742): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4742): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3741da19: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4742): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4742): GMSCore installation verified
,D/PowerManagerService( 1016): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1016) eventTime = 52631
,D/PowerManagerService( 1016): [s] UserActivityState : 2 -> 1
D/PowerManagerService( 1016): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016 (0x0)
,D/PowerManagerService( 1016): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1016, ws=WorkSource{1000}) (elapsedTime=3454)
D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1016): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,D/SRIB_DCS( 1178): log_dcs ThreadedRenderer::initialize entered! 
,I/ConfigStore( 4742): Config Database version: 1,
,W/ContextImpl( 4805): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,E/SMD     (  287): DCD OFF,
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4742): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4742): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4742): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4821): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1016): getStreamVolume 3 index 0
,I/MediaRouter( 4742): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/ActivityManager( 1016): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,W/ContextImpl( 4821): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files,
V/MusicLeanback( 4742): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,D/hcjo    ( 4805): AutoUpdateManager:IDLE:execute,
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.example.hello, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/NetworkMonitor( 4742): type=WIFI subType= reason=null isConnected=true
,D/InitializeManagerStateMachine( 4805): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4805): exit::IDLE
D/InitializeManagerStateMachine( 4805): entry::NETWORK_CHECK
,E/Zygote  ( 4852): MountEmulatedStorage()
E/Zygote  ( 4852): v2
I/libpersona( 4852): KNOX_SDCARD checking this for 10174
I/libpersona( 4852): KNOX_SDCARD not a persona
,I/SELinux ( 4852): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4852): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4852): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1016): Start proc com.example.hello for broadcast com.example.hello/io.jxcore.node.ConnectivityChangeListener: pid=4852 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a,
,D/InitializeManagerStateMachine( 4805): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4805): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4805): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4805): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4805): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4805): entry::SUCCESS
D/hcjo    ( 4805): AutoUpdateManager:INITCHECK:onInitializeSuccess
,V/AlarmManager( 1016): waitForAlarm result :4
,D/hcjo    ( 4805): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 4805): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4805): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4805): exit::SUCCESS
,D/InitializeManagerStateMachine( 4805): entry::IDLE
,D/TimaKeyStoreProvider( 4852): TimaSignature is unavailable
,D/ActivityThread( 4852): Added TimaKeyStore provider
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4821): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4821): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/jxcore_app_log( 4852): JniHelper::setJavaVM(0xb704a450), pthread_self() = -1224958264
,E/JX-Cordova( 4852): JXcore wasn't initialized yet
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1016): Killing 3858:com.vlingo.midas/u0a31 (adj 15): empty #31
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/NetworkMonitor( 4742): type=WIFI subType= reason=null isConnected=true
,E/Zygote  ( 4870): MountEmulatedStorage(),
I/libpersona( 4870): KNOX_SDCARD checking this for 10002
E/Zygote  ( 4870): v2
I/libpersona( 4870): KNOX_SDCARD not a persona,
I/SELinux ( 4870): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4870): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4870 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4870): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4870): TimaSignature is unavailable
,D/ActivityThread( 4870): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_10031/pid_3858/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/GoogleHttpClient( 4742): Failed to load SSLCertificateSocketFactory from package
I/GoogleHttpClient( 4742): Falling back to old SSLCertificateSocketFactory
,I/GHttpClientFactory( 4742): Using the GMSCore's GoogleHttpClient
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SurfaceFlinger(  257): id=12 Removed Uoast (8/9)
,I/SurfaceFlinger(  257): id=12 Removed Uoast (-2/9)
,I/ActivityManager( 1016): Killing 3886:com.google.android.gm/u0a101 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/WebViewFactory( 4821): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,E/Zygote  ( 4902): MountEmulatedStorage()
,E/Zygote  ( 4902): v2
,I/libpersona( 4902): KNOX_SDCARD checking this for 1000
I/libpersona( 4902): KNOX_SDCARD not a persona
,I/SELinux ( 4902): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4902): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4902): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4902 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/libprocessgroup( 1016): failed to open /acct/uid_10101/pid_3886/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4902): TimaSignature is unavailable
,D/ActivityThread( 4902): Added TimaKeyStore provider
,I/LibraryLoader( 4821): Time to load native libraries: 8 ms (timestamps 3348-3356)
I/LibraryLoader( 4821): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4821): Binding Chromium to main looper Looper (main, tid 1) {14266c24}
,I/LibraryLoader( 4821): Expected native library version number "",actual native library version number ""
,I/chromium( 4821): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4821): Initializing chromium process, singleProcess=true
I/DIAGMON_AGENT( 4902): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/art     ( 4821): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4821): ApplicationContext is null in ApplicationStatus
,W/chromium( 4821): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 4821): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
I/chromium( 4821): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,I/Adreno-EGL( 4821): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4821): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4821): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4821): Local Branch: 
I/Adreno-EGL( 4821): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4821): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4821):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/NSApplication( 4821): Starting up...
,I/DIAGMON_AGENT( 4902): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,W/AudioManagerAndroid( 4821): Requires BLUETOOTH permission
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DIAGMON_AGENT( 4902): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
I/DIAGMON_AGENT( 4902): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 4902): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:,
I/DIAGMON_AGENT( 4902): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 4902): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver,
,I/ActivityManager( 1016): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4934 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,E/Zygote  ( 4934): MountEmulatedStorage()
E/Zygote  ( 4934): v2
I/ActivityManager( 1016): Killing 3978:com.android.vending/u0a28 (adj 15): empty #31
I/libpersona( 4934): KNOX_SDCARD checking this for 10120
I/libpersona( 4934): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Killing 3946:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #32
I/SELinux ( 4934): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4934): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4934): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4934): TimaSignature is unavailable
,D/ActivityThread( 4934): Added TimaKeyStore provider
,W/ResourcesManager( 4934): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4953): MountEmulatedStorage()
E/Zygote  ( 4953): v2
I/libpersona( 4953): KNOX_SDCARD checking this for 10009
,I/libpersona( 4953): KNOX_SDCARD not a persona
,I/SELinux ( 4953): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4953): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4953): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4953 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup( 1016): failed to open /acct/uid_10028/pid_3978/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4953): TimaSignature is unavailable
,D/ActivityThread( 4953): Added TimaKeyStore provider
,I/art     (  302): Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 22.758ms
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3946/cgroup.procs: No such file or directory
,I/SA      ( 4347): [RC New] Execute method=[GET] start
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 18.270ms
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 720us total 17.148ms
,I/SA      ( 4347): [RC New] Security=[true]
,I/System.out( 4347): Thread-655(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 4347): Thread-655(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 4347): Thread-655(ApacheHTTPLog):isShipBuild true
I/System.out( 4347): Thread-655(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4347): Thread-655(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10041
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10041
,I/ActivityManager( 1016): Killing 4267:com.samsung.helphub/1000 (adj 15): empty #31
,I/FOTA_Client( 4953): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 4953): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 4953): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 4953): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/ActivityManager( 1016): Killing 4303:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4267/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4303/cgroup.procs: No such file or directory
,D/QuickConnect( 4476): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 4476): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 4476): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/splitIntent( 1016): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1016): Killing 4332:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,I/splitIntent( 1016): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=18, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=24
I/splitIntent( 1016): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4975): MountEmulatedStorage()
I/libpersona( 4975): KNOX_SDCARD checking this for 10062
E/Zygote  ( 4975): v2
I/libpersona( 4975): KNOX_SDCARD not a persona
,I/SELinux ( 4975): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4975): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
D/SSRM:n  ( 1016): SIOP:: AP = 400
,E/SELinux ( 4975): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1016): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4975 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/FOTA_Client( 4953): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/TimaKeyStoreProvider( 4975): TimaSignature is unavailable
,D/ActivityThread( 4975): Added TimaKeyStore provider
,D/daemonapp( 1334): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1334): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/FOTA_Client( 4953): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1334): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1334): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1334): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1334): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1334): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1334): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1334): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,I/KLMS-2.5.183: ( 3674): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Fri Mar 11 17:27:26 GMT+01:00 2016
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,D/daemonapp( 1334): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1334): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1334): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/SecurityLogAgent( 4673): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4673): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4673): StateMachine : Current State = 1
,I/KLMS-2.5.183: ( 3674): KLMSAbstractReciever(): onReceive().END.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/daemonapp( 1334): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/SA      ( 4347): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/KLMS-2.5.183: ( 3674): KLMSIntentService(): onCreate()
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4332/cgroup.procs: No such file or directory
,E/Zygote  ( 4994): MountEmulatedStorage()
,E/Zygote  ( 4994): v2
I/libpersona( 4994): KNOX_SDCARD checking this for 10157
I/libpersona( 4994): KNOX_SDCARD not a persona
,I/SELinux ( 4994): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4994 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,I/SELinux ( 4994): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4994): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3674): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/comdaemonstockapp( 1334): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1334): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
I/KLMS-2.5.183: ( 3674): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3674): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,I/KLMS-2.5.183: ( 3674): KLMSIntentService(): TIME_CHANGED
,I/ExternalOEMControlProvider( 4975): onCreate,
,E/Zygote  ( 5007): MountEmulatedStorage()
I/libpersona( 5007): KNOX_SDCARD checking this for 10046
E/Zygote  ( 5007): v2
I/libpersona( 5007): KNOX_SDCARD not a persona
,I/SELinux ( 5007): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5007): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=5007 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/SELinux ( 5007): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4994): TimaSignature is unavailable
D/ActivityThread( 4994): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3674): StateImplV2(): dateTimeChanged().START : Fri Mar 11 17:27:26 GMT+01:00 2016
,D/TimaKeyStoreProvider( 5007): TimaSignature is unavailable
,D/ActivityThread( 5007): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3674): StateImplV2(): dateTimeChanged().END
,I/KLMS-2.5.183: ( 3674): KLMSIntentService(): onDestroy()
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 29788(1678KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 26MB/40MB, paused 2.508ms total 147.915ms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5026): MountEmulatedStorage(),
E/Zygote  ( 5026): v2
I/libpersona( 5026): KNOX_SDCARD checking this for 1000
,I/libpersona( 5026): KNOX_SDCARD not a persona
,I/SELinux ( 5026): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.contextagent.ContextAgentReceiver: pid=5026 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 5026): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5026): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ Time Manager ( 4975): Time Difference not stored. TIME_DIFFERENCE
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5026): TimaSignature is unavailable
,D/ActivityThread( 5026): Added TimaKeyStore provider
,W/ResourcesManager( 5007): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5007): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5007): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5007): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5007): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5007): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 4994): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5026): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5041): MountEmulatedStorage()
,I/libpersona( 5041): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5041): v2
I/libpersona( 5041): KNOX_SDCARD not a persona
I/SELinux ( 5041): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5041): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5041 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 5041): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 4368:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Killing 4441:com.sec.android.app.mt/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5041): TimaSignature is unavailable
,D/ActivityThread( 5041): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/accuweather( 1768): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1768): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5057): MountEmulatedStorage()
E/Zygote  ( 5057): v2
I/libpersona( 5057): KNOX_SDCARD checking this for 10085
I/libpersona( 5057): KNOX_SDCARD not a persona
,I/SELinux ( 5057): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5057): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=5057 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 5057): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5057): TimaSignature is unavailable
,D/ActivityThread( 5057): Added TimaKeyStore provider
,I/SA      ( 4347): [RC New] [v2liruge] api execute + 784
,D/TimeService( 5041): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1457713646664
D/        ( 5041): TimeServiceNative: User Time to be set is 1457713646665
D/QC-time-services( 5041): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5041): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5041): Lib:time_genoff_operation: pargs->ts_val = 1457713646665
,I/SA      ( 4347): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
D/QC-time-services(  316): Daemon: Connection accepted:time_genoff
D/QC-time-services( 5041): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  316): Daemon:Received base = 2, unit = 1, operation = 0,value = 1457713646665
D/QC-time-services(  316): Daemon:genoff_opr: Base = 2, val = 1457713646665, operation = 0
D/QC-time-services(  316): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/10/70 14:32:46
,D/QC-time-services(  316): Daemon:Value read from RTC seconds = 21825166000
D/QC-time-services(  316): Daemon:new time 1457713646665 
D/QC-time-services(  316): Daemon: delta 1435888480665 genoff 1435888480665 
D/QC-time-services(  316): Daemon:genoff_persistent_update: Writing genoff = 1435888480665 to memory
D/QC-time-services(  316): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  316): Daemon:time_persistent_memory_opr:Genoff write operation 
,I/System.out( 4347): AsyncTask #1 calls detatch()
,W/ResourcesManager( 5057): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5057): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5057): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5057): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 5057): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5057): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/Mms/MmsApp( 5007): [start]    onCreate() consume time = 0.0
,I/SA      ( 4347): [ODM] saveOpenData( GEO_IP, PL )
,D/QC-time-services(  316): Updating the TOD offset
D/QC-time-services(  316): Daemon:genoff_persistent_update: Writing genoff = 1435888480665 to memory
D/QC-time-services(  316): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  316): Daemon:time_persistent_memory_opr:Genoff write operation 
,I/SA      ( 4347): [OCP] update openData : PL
,D/SettingsProvider( 1016): name = next_alarm_formatted
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
E/QC-time-services(  316): Daemon:Update to modem bit set
D/QC-time-services(  316): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  316): Daemon: Base = 2, Value being sent to MODEM = 1119923680665
,D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10085
E/QC-time-services( 5041): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,E/QC-time-services(  316): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  316): Daemon: Time-services: Waiting to acceptconnection
,I/SA      ( 4347): [TPMU] getNetworkMcc : 
,I/SA      ( 4347): [SCU] saveMccToPreferece Start
I/SA      ( 4347): [SCU] RegionMCC : 260
I/SA      ( 4347): [SSP] query invoked
,I/ActivityManager( 1016): Killing 4497:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,I/SA      ( 4347): [TPMU] GetMccFromDB : null
,I/SA      ( 4347): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4347): [SCU] saveMccToPreferece End
,I/SA      ( 4347): [RC New] executeRequest [v2liruge] end. 928
I/SA      ( 4347): [RC New] Execute end
,I/SA      ( 4347): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 4347): [OR] GetMyCountryZoneTask Success
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4441/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10107/pid_4368/cgroup.procs: No such file or directory
,I/ActivityManager( 1016): Killing 4557:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ActivityManager( 1016): Killing 4600:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,W/art     ( 5057): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 104.618ms
,W/art     ( 5007): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 122.275ms
,W/libprocessgroup( 1016): failed to open /acct/uid_10131/pid_4497/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10139/pid_4557/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10072/pid_4600/cgroup.procs: No such file or directory
,D/Mms/ArtClassLoader( 5007): init before art
,D/Mms/TelephonyPermission( 5007): start operation mode monitor
,D/ActivityManager( 1016): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,W/ResourcesManager( 5007): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5075): MountEmulatedStorage()
,I/libpersona( 5075): KNOX_SDCARD checking this for 10094
E/Zygote  ( 5075): v2
I/libpersona( 5075): KNOX_SDCARD not a persona
I/SELinux ( 5075): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5075): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5075 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 5075): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/TelephonyPermission( 5007): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 5007): isDefault true
,D/Mms/MmsApp( 5007): onCreate() com.android.mms
,I/ActivityManager( 1016): Killing 3382:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5075): TimaSignature is unavailable
,D/ActivityThread( 5075): Added TimaKeyStore provider
,D/elm:15183( 5075): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15183( 5075): ELMEngine.ELMEngine( context ).
,D/elm:15183( 5075): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1016): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 5075): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,D/elm:15183( 5075): ElmAgentService : onCreate()
,D/elm:15183( 5075): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/elm:15183( 5075): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:15183( 5075): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:15183( 5075): ModuleBase.ModifySetAlarm()
D/elm:15183( 5075): MDMBridge.getInstance()
D/elm:15183( 5075): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 5093): MountEmulatedStorage()
,E/Zygote  ( 5093): v2
I/SELinux ( 5093): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5093): KNOX_SDCARD checking this for 10134
I/libpersona( 5093): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5093 uid=10134 gids={50134, 9997} abi=armeabi-v7a
,D/elm:15183( 5075): ElmAgentService : onDestroy().
,I/SELinux ( 5093): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5093): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 4640:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5093): TimaSignature is unavailable
,D/ActivityThread( 5093): Added TimaKeyStore provider
,W/ResourcesManager( 5093): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5093): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_10091/pid_3382/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4640/cgroup.procs: No such file or directory
,D/Mms/MmsApp( 5007): [start]    initCountryIso consume time = 573.516041
,D/CountryDetector( 1016): The first listener is added
,D/Mms/MmsApp( 5007): [end]    initCountryIso consume time = 7.872292
D/Mms/MmsConfig( 5007): [start]    MmsConfig.init() consume time = 0.117291
,D/Mms/MmsConfig( 5007): before partial update
,D/Mms/MmsConfig( 5007): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 5007): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 5007): isAuth is false
,D/Mms/MmsConfig( 5007): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1485): query,matched:2117, calling pid = 5007
,D/TP/MmsSmsProvider( 1485): match 2117:Elapsed time : 1.526 ms
,D/EasySignUpManager_1.0.1( 5007): isAuth is false
,D/EasySignUpManager_1.0.1( 5007): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 5007): mps_code.dat does not exist
,E/CscParser( 5007): customer_path =/system/csc/customer.xml
,E/CscParser( 5007): fileName + /system/csc/customer.xml
,E/CscParser( 5007): mps_code.dat does not exist
E/CscParser( 5007): customer_path =/system/csc/customer.xml
E/CscParser( 5007): fileName + /system/csc/customer.xml
,D/CscParser( 5007): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 5007):  enable multiwindow = true
,E/Mms/MessageUtils( 5007): setCountryDetector : update country detector info 
,E/Mms/MessageUtils( 5007): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 5007): [end]    init() consume time = 76.089532
,D/Mms/Contact( 5007): [start]    init() consume time = 1.535208
,D/TP/MmsSmsProvider( 1485): query,matched:13, calling pid = 5007
,D/TP/MmsSmsProvider( 1485): match 13:Elapsed time : 1.434 ms
,D/Mms/Contact( 5007): [end]    init consume time = 17.058177
,D/Mms/DraftCache( 5007): [start]    rebuildCache consume time = 3.934219
,D/TP/MmsSmsProvider( 1485): query,matched:12, calling pid = 5007
,D/TP/MmsSmsProvider( 1485): match 12:Elapsed time : 1.927 ms
,D/Mms/DraftCache( 5007): [end]    rebuildCache consume time = 13.063385
,D/Mms/MethodReflector( 5007): getSubId is called
,D/Mms/TelephonyUtils( 5007): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 5007): getTelephonyProperty is called
,D/Mms/DownloadManager( 5007): roaming -> false (slotId = 0)
,D/Mms/DownloadManager( 5007): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5007): auto download without roaming -> true
,D/Mms/DownloadManager( 5007): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5007): getSubId is called
,D/Mms/MethodReflector( 5007): getDefaultSmsSubId is called
,E/Mms/TelephonyUtils( 5007): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5007): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5007): getTelephonyProperty is called
D/Mms/DownloadManager( 5007): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5007): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5007): auto download without roaming -> true
D/Mms/DownloadManager( 5007): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5007): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5007): mAutoDownload ------> true
,D/Mms/ArtClassLoader( 5007): init [DONE] art
,D/ComposerPerformance( 5007): 1457713647435 ms / [DONE] Composer constructor
,E/CII     ( 5007): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 5007): ReservationManager()
,I/Mms/ReservationManager( 5007): resetAfterConnected()
,D/TP/MmsSmsProvider( 1485): query,matched:7, calling pid = 5007
,D/Mms/Conversation( 5007): [start]    init() consume time = 52.231511
,D/TP/MmsSmsProvider( 1485): match 7:Elapsed time : 2.975 ms
,D/TP/MmsSmsProvider( 1485): deleteConversation threadId: 9223372036854775807
,I/Mms/ReservationManager( 5007): getReservedSendMessageCount(): retMessageCount=0
,D/TP/MmsSmsProvider( 1485): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1485): updateThread(), thread_id = 9223372036854775807
,D/Mms/MmsApp( 5007): [end]    onCreate() consume time = 10.92302
,D/Mms/DownloadManager( 5007): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 5007): roaming ------> false, mSimSlot = 0
I/splitIntent( 1016): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
,V/TP/MmsSmsDatabaseHelper( 1485): sUpgradeVersion = 0, db.getVersion() = 81
D/Mms/MethodReflector( 5007): getSubId is called
D/Mms/TelephonyUtils( 5007): getLongSubId from simSlot 0, return Value = -1
E/SQLiteLog( 1485): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1485): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1485): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1485): (284) automatic index on im_threads(normal_thread_id)
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
E/SQLiteLog( 1485): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1485): (284) automatic index on im_threads(normal_thread_id)
,I/ActivityManager( 1016): Killing 4726:com.sec.pcw.device/1000 (adj 15): empty #31
,D/Mms/MethodReflector( 5007): getTelephonyProperty is called
D/Mms/DownloadManager( 5007): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5007): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5007): auto download without roaming -> true
D/Mms/DownloadManager( 5007): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5007): mAutoDownload ------> true
,D/TP/MmsSmsProvider( 1485): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1485): need read changed broadcast:false
,D/Mms/Conversation( 5007): [end]    init consume time = 15.862136
,D/Mms/MessagingNotification( 5007): [start]    init() consume time = 0.320364
,D/Mms/MessagingNotification( 5007): [end]    init consume time = 3.461511
,D/TP/MmsSmsProvider( 1485): query,matched:0, calling pid = 5007
V/TP/MmsSmsProvider( 1485): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1485): match 0:Elapsed time : 1.146 ms
,D/Mms/Synchronizer( 5007): [start]    doSync consume time = 5.338906
,D/TP/MmsSmsProvider( 1485): update, matched:300, calling pid = 5007
V/TP/MmsSmsProvider( 1485): syncDBData start
,V/TP/MmsSmsProvider( 1485): syncDBData sms end
,V/TP/MmsSmsProvider( 1485): syncDBData mms end
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,V/TP/MmsSmsProvider( 1485): syncDBData end
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/Mms/SpamFilter( 5007): [start]    SpamFilter fill() begin consume time = 6.234427
,E/Zygote  ( 5118): MountEmulatedStorage(),
I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5118 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,E/Zygote  ( 5118): v2
D/ActivityManager( 1016): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
I/SELinux ( 5118): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5118): KNOX_SDCARD checking this for 10072
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,I/libpersona( 5118): KNOX_SDCARD not a persona
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
D/Mms/Synchronizer( 5007): [end]    doSync consume time = 18.937604
I/SELinux ( 5118): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5118): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TP/MmsSmsProvider( 1485): query,matched:400, calling pid = 5007
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/SpamFilter( 5007): [end]    SpamFilter fill() finished consume time = 15.075209
,D/TimaKeyStoreProvider( 5118): TimaSignature is unavailable
,D/ActivityThread( 5118): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 3996:com.samsung.android.app.galaxyfinder:tagService/u0a32 (adj 15): empty #31
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5134): MountEmulatedStorage()
E/Zygote  ( 5134): v2
I/libpersona( 5134): KNOX_SDCARD checking this for 1000
I/libpersona( 5134): KNOX_SDCARD not a persona
,I/SELinux ( 5134): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5134): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1016): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5134 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 5134): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 4193:com.sec.android.soagent/u0a34 (adj 15): empty #31
,D/BadgeProvider( 5118): onCreate
,D/BadgeProvider( 5118): DatabaseHelper
,I/art     ( 1667): Explicit concurrent mark sweep GC freed 4188(178KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 818us total 24.239ms
,D/TimaKeyStoreProvider( 5134): TimaSignature is unavailable
,D/ActivityThread( 5134): Added TimaKeyStore provider
,D/Mms/MessagingNotification( 5007): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1485): query,matched:26, calling pid = 5007
,D/TP/SmsProvider( 1485): match 26:Elapsed time : 1.634 ms
,D/TP/MmsSmsProvider( 1485): query,matched:6, calling pid = 5007
,E/MTPRx   ( 5134): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/TP/MmsSmsProvider( 1485): match 6:Elapsed time : 5.917 ms
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedState
D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1016): mCursor = null
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4726/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10032/pid_3996/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10034/pid_4193/cgroup.procs: No such file or directory
,V/MTPRx   ( 5134): sealedState: false
V/MTPRx   ( 5134): sealedUsbMassStorageState: false
,E/MTPRx   ( 5134): check value of boot_completed is1
E/MTPRx   ( 5134): check booting is completed_sys.boot_completed
,E/MTPRx   ( 5134): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 5134): Status for mount/Unmount :removed
E/MTPRx   ( 5134): SDcard is not available
,W/MTPRx   ( 5134): value of connected istrue
,W/MTPRx   ( 5134): value of configured istrue
W/MTPRx   ( 5134): value of mtpEnabled istrue
W/MTPRx   ( 5134): value of ptpEnabled isfalse
,E/MTPRx   ( 5134): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 5134): mFirstTime: false
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/        ( 5134): MTP: reading debug level property
,E/MTPJNIInterface( 5134): Getting CryptionKey from JAVA,
E/MTPRx   ( 5134): currentUserId is 0
,E/MTPRx   ( 5134): Start observing USB_STATE_MATCH 
E/MTPRx   ( 5134): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 5134): is_Privatemode is NOT 1
D/SettingsProvider( 1016): name = boot_time_connected
,E/Zygote  ( 5151): MountEmulatedStorage()
I/libpersona( 5151): KNOX_SDCARD checking this for 10025
E/Zygote  ( 5151): v2
I/libpersona( 5151): KNOX_SDCARD not a persona
I/SELinux ( 5151): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/MTPRx   ( 5134): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 5134): noti = 17
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,I/SELinux ( 5151): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5151): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1016): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5151 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,D/SecContentProvider( 1016): uri = 18 selection = isUsbMediaPlayerAvailable
E/MTPRx   ( 5134): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1016): name = mtp_running_status
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,I/art     (  302): Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 23.123ms
,E/MTPRx   ( 5134): else part ... so first time!!!
,E/MTPPlaObsrvr( 5134): inside setContext()
E/MTPPlaObsrvr( 5134):  inside createplafiles
,D/TimaKeyStoreProvider( 5151): TimaSignature is unavailable
,D/ActivityThread( 5151): Added TimaKeyStore provider
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,I/ActivityManager( 1016): Killing 4757:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 606us total 17.606ms
,W/ResourcesManager( 5151): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/MTPPlaObsrvr( 5134): playlist count is0
,E/MTPPlaObsrvr( 5134):  inside try branch createplafiles
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 16.928ms
E/MTPPlaObsrvr( 5134):  inside deleteing plas createplafiles
,I/ValidateNoPeople( 1016): mEvictionCount: 0
,D/Mms/Contact( 5007): sContactsObserver.onChange(),selfUpdate=false
,E/MTPPlaObsrvr( 5134): Inside registerContentObserver
,E/MtpAdbObserver( 5134): inside setContext()
E/MtpAdbObserver( 5134): Inside registerContentObserver
W/Settings( 5134): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/Mms/Contact( 5007): performUpdate:widgetCount=0
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1016): name = mtp_running_status
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,V/MtpMediaDBManager( 5134): inside deleteAllDB
,E/MtpService( 5134): onCreate.
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MtpService( 5134): < MTP > Registering BroadCast receiver :::::
,D/Mms/ContactsCache( 5007): [start]    invalidate() consume time = 260.153645
D/Mms/ContactsCache( 5007): [end]    invalidate() consume time = 0.161459
,E/MtpService( 5134): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 5134): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,D/MtpService( 1241): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpService( 5134): onStartCommand.
,W/MTPRx   ( 5134): calling native method
E/MTPJNIInterface( 5134): < MTP > Registering BroadCast receiver :::::
,E/MTPJNIInterface( 5134): < MTP > Registering BroadCast receiver :::::::
,E/SMD     (  287): DCD OFF,
W/libprocessgroup( 1016): failed to open /acct/uid_10159/pid_4757/cgroup.procs: No such file or directory
,I/OMACP   ( 5151): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,E/MtpService( 5134): handleMessage. msg= { when=-10ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,E/MTPJNIInterface( 5134): noti = 10
,E/MtpService( 5134): onStartCommand.
,W/MTPRx   ( 5134): calling native method
E/MTPRx   ( 5134): Checking the driver time out
E/MTPJNIInterface( 5134): noti = 2
D/        ( 5134): deleting sockets before message queue initialization
,D/        ( 5134): event handler thread is created, so set the flag
,E/MTPRx   ( 5134): called native method
E/MTPJNIInterface( 5134): setting Media scanner status0
E/MTPJNIInterface( 5134): After setting Media scanner status0
E/MtpService( 5134): handleMessage. msg= { when=-2ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,D/Mms/Omacp( 5007): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,W/MTPRx   ( 5134): notification from stack 1
,V/MtpMediaDBManager( 5134): inside Thread updateDB
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/        ( 5134): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
,E/MTPJNIInterface( 5134): Getting media scanner status0
,E/MTPJNIInterface( 5134): DeviceName is A5-1
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/MtpMediaDBManager( 5134): count : 27
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1930): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,I/OMACP   ( 5151): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 5151): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 5151): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 5151): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 5151): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 5151): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 5151): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 5151): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 5151): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 5151): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 5151): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 5151): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 5151): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BluetoothNotiBroadcastReceiver( 1357): onReceive
,W/MtpMediaDBManager( 5134): sending db update complete noti to stack
E/MTPJNIInterface( 5134): noti = 29
,V/BluetoothStatusReceiver( 1178): Received android.bluetooth.adapter.action.STATE_CHANGED,
D/BluetoothStatusReceiver( 1178): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5172): MountEmulatedStorage()
,E/Zygote  ( 5172): v2
I/libpersona( 5172): KNOX_SDCARD checking this for 10003
I/libpersona( 5172): KNOX_SDCARD not a persona
,I/SELinux ( 5172): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5172 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
I/SELinux ( 5172): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,E/SELinux ( 5172): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1445): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1445): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2695): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2695): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/MTPJNIInterface( 5134): Status for mount/Unmount :removed
E/MTPJNIInterface( 5134): SDcard is not available
,D/TimaKeyStoreProvider( 5172): TimaSignature is unavailable
,D/ActivityThread( 5172): Added TimaKeyStore provider
,E/        ( 5134): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,E/        ( 5134): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 5134): Status for mount/Unmount :removed
E/MTPJNIInterface( 5134): SDcard is not available
E/SQLiteLog( 5134): (21) API call with NULL database connection pointer
E/SQLiteLog( 5134): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 5134): (21) API call with NULL database connection pointer
E/SQLiteLog( 5134): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5134): (21) API call with NULL database connection pointer
E/SQLiteLog( 5134): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5134): (21) API call with NULL database connection pointer
E/SQLiteLog( 5134): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 5134): notification from stack 2
,D/        ( 5134): [mtp_init_device] Library open with 32 bits.
D/        ( 5134): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 5134): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 5134): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 5134):  [sua_support_present:1287] returning false 
D/        ( 5134): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,D/UserAnalysis.PlaceProvider( 5172): PlaceProvider onCreate()

```
