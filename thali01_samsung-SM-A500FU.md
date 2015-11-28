#### Test 50388019809f971_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
D/TimaKeyStoreProvider( 3678): TimaSignature is unavailable
D/ActivityThread( 3678): Added TimaKeyStore provider
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 644us total 18.186ms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
--------- beginning of system
W/ContextImpl( 3663): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 727us total 17.775ms
W/libprocessgroup( 1017): failed to open /acct/uid_10159/pid_2902/cgroup.procs: No such file or directory
D/PackageIntentReceiver( 3678): ACTION_BOOT_COMPLETED
D/PackageIntentReceiver( 3678): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3699): MountEmulatedStorage()
I/libpersona( 3699): KNOX_SDCARD checking this for 10101
E/Zygote  ( 3699): v2
I/libpersona( 3699): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3699 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2916:com.sec.knox.bridge/1000 (adj 15): empty #31
I/SELinux ( 3699): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3699): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3699): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3699): TimaSignature is unavailable
D/ActivityThread( 3699): Added TimaKeyStore provider
E/SMD     (  288): DCD OFF
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2916/cgroup.procs: No such file or directory
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3224): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3224): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3224): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
D/ActivityManager( 1017): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
I/VlingoApplication( 3640): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
I/ServiceManager(  314): Waiting for service AtCmdFwd...
D/BluetoothAdapter( 3640): 628196584: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3640): 628196584: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3640): 628196584: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore( 3640): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
D/ActivityManager( 1017): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/FactoryTestApp( 2543): [DummyFtClient$onDestroy](2543) Destroy DummyFtClient service
D/FactoryTestApp( 2543): [Support$Values.getString](2543) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2543): [ModuleCommon$isConnectionModeNone](2543) mConnectionMode = gsm
I/FactoryTestApp( 2543): [ModuleCommon$isRunningFtClient](2543) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2543): [DummyFtClient$onDestroy](2543) kill process
I/Process ( 2543): Sending signal. PID: 2543 SIG: 9
D/VlingoApplication( 3640): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 3640): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
D/ActivityManager( 1017): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/DialogFlow( 3640): initQueue()
D/ActivityManager( 1017): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3663): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3663): Resource data:2131165186
W/ResourcesManager( 3663): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3663): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3663): getResourceTypeNamexml
D/ActivityManager( 1017): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
I/ActivityManager( 1017): Process com.sec.factory (pid 2543)(adj 0) has died(235,1044)
I/AMMetaDataParserService( 3663): Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
I/DBG_DM  ( 2986): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 1949): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
E/Zygote  ( 3751): MountEmulatedStorage()
E/Zygote  ( 3751): v2
I/libpersona( 3751): KNOX_SDCARD checking this for 10032
I/libpersona( 3751): KNOX_SDCARD not a persona
I/SELinux ( 3751): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3751 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2935:com.sec.android.diagmonagent/1000 (adj 15): empty #31
D/ActivityManager( 1017): startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
D/SecUISvc( 1949): Service started flags 0 startId 1
I/SELinux ( 3751): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/SecUISvc( 1949): Thread created.
E/SELinux ( 3751): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 3751): TimaSignature is unavailable
D/ActivityManager( 1017): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
D/ActivityThread( 3751): Added TimaKeyStore provider
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
I/AMMetaDataParserService( 3663): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
I/AMMetaDataParserService( 3663): Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
I/ActivityManager( 1017): Killing 2952:com.sec.usbsettings/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
W/ContextImpl( 3663): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2935/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2952/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:assistant
I/AMMetaDataParserService( 3663): Resource data:2131034113
W/ResourcesManager( 3663): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3663): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3663): getResourceTypeNamexml
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX construct_block_size_descriptor_2d second part( 3663): took 2.844375ms for 0*0 texture 0
I/GFX generate_partition_tables( 3663): took 6.802501ms for 0*0 texture 0
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/GFX raster( 3663): took 11.371357ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f8f868 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f8f830 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3663): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
E/Zygote  ( 3775): MountEmulatedStorage()
E/Zygote  ( 3775): v2
I/libpersona( 3775): KNOX_SDCARD checking this for 10033
I/libpersona( 3775): KNOX_SDCARD not a persona
I/SELinux ( 3775): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3775 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3022:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
I/SELinux ( 3775): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3775): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3775): TimaSignature is unavailable
D/ActivityThread( 3775): Added TimaKeyStore provider
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/libprocessgroup( 1017): failed to open /acct/uid_10150/pid_3022/cgroup.procs: No such file or directory
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3663): took 0.859948ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f8f868 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f8f830 counterpartCT=4 counterpartW=96 counterparth=96
W/ResourcesManager( 3775): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3663): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
D/FileApkUtils( 1914): Spent 29ms computing apk sha1.
D/FileApkUtils( 1914): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 1914): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d93aca1818df11c4cd5bccf493ad94e2b544d57a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
W/ResourcesManager( 3775): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/DexOptUtils( 1914): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk appears to be unoptimized.
D/DexOptUtils( 1914): Lollipop platform, using <isa> directory.
D/DexOptUtils( 1914): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 1914): Primary ABI of odexing process is armeabi-v7a
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ResourcesManager( 3775): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/GFX construct_block_size_descriptor_2d second part( 3663): took 2.258855ms for 0*0 texture 0
I/GFX generate_partition_tables( 3663): took 7.450573ms for 0*0 texture 0
I/GFX raster( 3663): took 10.669897ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f8f830 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f94320 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3663): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3663): took 0.602343ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f98ec8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f99020 counterpartCT=4 counterpartW=96 counterparth=96
I/dex2oat ( 3792): ----------------------------------------------------
I/dex2oat ( 3792): <SS>: S T A R T I N G . . .
I/dex2oat ( 3792): <SS>: Zip is absent. Canceled.
I/dex2oat ( 3792): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk --oat-fd=41 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/AMMetaDataParserService( 3663): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3663): took 0.823854ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f958d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f95a28 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3663): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
I/Gmail   ( 3699): getAccountsCursor
D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/GAV2    ( 3699): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/GCM     ( 1914): COMPAT: Multi user not supported
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/GCM     ( 1630): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3663): took 0.696457ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f8fcb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f943b0 counterpartCT=4 counterpartW=96 counterparth=96
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/GCoreUlr( 1914): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/AMMetaDataParserService( 3663): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/CheckinService( 1914): Checkin interval check for package: unspecified last checkin: 1448204549172 min interval config: 0 actual interval: 504803588
I/GCoreUlr( 1774): DispatchingService.onCreate()
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3663): took 0.679271ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f98bb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f95840 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/CheckinService( 1914): Disabling old GoogleServicesFramework version
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3663): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/SystemUpdateService( 1914): onCreate
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/Gmail   ( 3699): Observing account changes for notifications
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/SystemUpdateService( 1914): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
V/AuthZen ( 1914): Handling intent: android.intent.action.BOOT_COMPLETED
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/AuthZenEventHandler( 1914): Handling event: android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_DM  ( 2986): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3663): took 0.523333ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f95840 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f5aee8 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3663): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:assistant
I/AMMetaDataParserService( 3663): Resource data:2131034113
I/AMMetaDataParserService( 3663): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3663): getResourceTypeNamexml
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3663): took 0.807239ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f10ae0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f777d8 counterpartCT=4 counterpartW=96 counterparth=96
E/Gmail   ( 3699): Error finding the version of the Email provider.....
E/Gmail   ( 3699): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3699): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3699): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 3699): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3699): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3699): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3699): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3699): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3699): We do not support migrating this version of the Email provider.
I/AMMetaDataParserService( 3663): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
I/CheckinService( 1914): Checking schedule, now: 1448709353140 next: 1448743812129
I/CheckinService( 1914): active receiver: disabled
I/art     ( 1017): Explicit concurrent mark sweep GC freed 53920(3MB) AllocSpace objects, 6(216KB) LOS objects, 33% free, 26MB/39MB, paused 3.381ms total 207.923ms
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
W/BaseAppContext( 1914): Using Auth Proxy for data requests.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/GFX raster( 3663): took 0.979895ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f10ae0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f5aee8 counterpartCT=4 counterpartW=96 counterparth=96
I/SystemUpdateService( 1914): cancelUpdate (empty URL)
I/SystemUpdateService( 1914): active receiver: disabled
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AndroidRuntime( 3842): 
D/AndroidRuntime( 3842): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3842): CheckJNI is OFF
D/AndroidRuntime( 3842): readGMSProperty: start
D/AndroidRuntime( 3842): readGMSProperty: already setted!!
D/AndroidRuntime( 3842): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3842): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3842): readGMSProperty: end
D/AndroidRuntime( 3842): addProductProperty: start
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/Process ( 3775): Sending signal. PID: 3775 SIG: 9
W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/AMMetaDataParserService( 3663): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
I/Gmail   ( 3699): getAccountsCursor
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3858 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
E/Zygote  ( 3858): MountEmulatedStorage()
E/Zygote  ( 3858): v2
I/libpersona( 3858): KNOX_SDCARD checking this for 10104
I/libpersona( 3858): KNOX_SDCARD not a persona
D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/SELinux ( 3858): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3858): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3858): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3858): TimaSignature is unavailable
E/AffinityControl( 3842): AffinityControl: registerfunction enter
D/ActivityThread( 3858): Added TimaKeyStore provider
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3663): took 0.707447ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f777d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f5aee8 counterpartCT=4 counterpartW=96 counterparth=96
D/AndroidRuntime( 3842): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1017): mDVFSHelper.acquire()
I/SurfaceFlinger(  258): id=8 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  258): id=9 createSurf (16x16),-1 flag=20004, EimLayer(An
I/AMMetaDataParserService( 3663): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
D/FocusedStackFrame( 1017): Set to : 0
D/Launcher.HomeView( 1469): onPause
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 1469
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
D/Launcher( 1469): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/AndroidRuntime( 3842): Shutting down VM
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ActivityManager( 1017): Process com.sec.android.app.sns3 (pid 3775)(adj 0) has died(205,1061)
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=10 createSurf (1x1),1 flag=404, iello
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3882): MountEmulatedStorage()
E/Zygote  ( 3882): v2
I/libpersona( 3882): KNOX_SDCARD checking this for 10034
I/libpersona( 3882): KNOX_SDCARD not a persona
I/SELinux ( 3882): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=3882 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 3882): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3882): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 3858): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/Zygote  ( 3892): MountEmulatedStorage()
I/libpersona( 3892): KNOX_SDCARD checking this for 10174
E/Zygote  ( 3892): v2
I/libpersona( 3892): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3892 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 3892): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3892): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3892): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/TimaKeyStoreProvider( 3882): TimaSignature is unavailable
D/ActivityThread( 3882): Added TimaKeyStore provider
E/ActivityThread( 3699): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@a90373 that was originally bound here
E/ActivityThread( 3699): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@a90373 that was originally bound here
E/ActivityThread( 3699): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3699): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3699): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3699): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3699): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3699): 	at com.android.emailcommon.service.ah.a(SourceFile:181)
E/ActivityThread( 3699): 	at com.android.emailcommon.service.ah.e(SourceFile:224)
E/ActivityThread( 3699): 	at com.android.email.service.n.c(SourceFile:161)
E/ActivityThread( 3699): 	at com.android.email.provider.b.a(SourceFile:173)
E/ActivityThread( 3699): 	at com.android.email.provider.b.a(SourceFile:117)
E/ActivityThread( 3699): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
E/ActivityThread( 3699): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
E/ActivityThread( 3699): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3699): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3699): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3699): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/ActivityThread( 1469): updateVisibility : ActivityRecord{1532cb19 token=android.os.BinderProxy@1ad6f841 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
W/ActivityManager( 1017): Unbind failed: could not find connection for android.os.BinderProxy@3214d2ac
D/TimaKeyStoreProvider( 3892): TimaSignature is unavailable
D/ActivityThread( 3892): Added TimaKeyStore provider
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1469): onStop
V/ActivityThread( 1469): updateVisibility : ActivityRecord{1532cb19 token=android.os.BinderProxy@1ad6f841 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
W/art     ( 3842): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/DBG_DM  ( 2986): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,D/Launcher( 1469): onTrimMemory. Level: 20
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.598750ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f5aee8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f59c78 counterpartCT=4 counterpartW=96 counterparth=96
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1017): [SO] activate (ident=0xb92533d0, enabled=0)
,I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/AMMetaDataParserService( 3663): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/ResourcesManager( 3751): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1017): [SO] changed settle time [1]
D/SensorService( 1017): [SO] setDelay [66000000]
D/SensorService( 1017): [SO] activate (ident=0xb9350ae0, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.871563ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f76b38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f98c90 counterpartCT=4 counterpartW=96 counterparth=96
D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
I/AMMetaDataParserService( 3663): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
I/art     ( 1630): Explicit concurrent mark sweep GC freed 16721(971KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 10MB/17MB, paused 1.084ms total 747.545ms
,I/GoogleHttpClient( 1630): GMS http client unavailable, use old client
,V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/WebViewFactory( 3892): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,I/dex2oat ( 3792): dex2oat took 1.647s (threads: 4)
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.635000ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f8fcb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f98c20 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 3751): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3751): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3751): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3663): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/LibraryLoader( 3892): Time to load native libraries: 2 ms (timestamps 108-110)
,I/LibraryLoader( 3892): Expected native library version number "",actual native library version number ""
,D/SensorService( 1017): [SO] 0.211 0.172 10.151
D/SensorService( 1017): [SO] [100 -> 255]
,D/ChimeraCfgMgr( 1914): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/DexOptUtils( 1914): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/arm/MapsModule.dex
D/DexOptUtils( 1914): Set odex to world readable.
,D/DexOptUtils( 1914): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/arm/MapsModule.odex
,D/FileApkUtils( 1914): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,D/GmsModuleFndr( 1914): Beginning GMS chimera module scan
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,V/WebViewChromiumFactoryProvider( 3892): Binding Chromium to main looper Looper (main, tid 1) {3dd73db8}
,I/LibraryLoader( 3892): Expected native library version number "",actual native library version number ""
,I/chromium( 3892): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,E/Zygote  ( 3927): MountEmulatedStorage()
E/Zygote  ( 3927): v2
,I/libpersona( 3927): KNOX_SDCARD checking this for 10035
I/SELinux ( 3927): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3927): KNOX_SDCARD not a persona
,I/SELinux ( 3927): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3927): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=3927 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 1554:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,I/AuthZen ( 1914): Fetching signing key...
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.732292ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f98bb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f76d38 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/BrowserStartupController( 3892): Initializing chromium process, singleProcess=true
D/GmsModuleFndr( 1914): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
W/art     ( 3892): Attempt to remove local handle scope entry from IRT, ignoring
D/ChimeraCfgMgr( 1914): Beginning module configuration check
W/ActivityManager( 1017): userId = 0, bbcId = -10000
E/SysUtils( 3892): ApplicationContext is null in ApplicationStatus
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AuthZen ( 1914): Signing key fetched successfully!
,D/TimaKeyStoreProvider( 3927): TimaSignature is unavailable
,D/ActivityThread( 3927): Added TimaKeyStore provider
,W/chromium( 3892): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,W/BaseAppContext( 1914): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 1914): Module APKs unchanged, check complete
,W/chromium( 3892): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 3892): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 3892): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,E/SQLiteLog( 3699): (283) recovered 49 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/Adreno-EGL( 3892): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3892): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3892): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3892): Local Branch: 
I/Adreno-EGL( 3892): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3892): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3892):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/System.out( 3640): INFO:Resource not found:/Common.properties Using default values
,I/AMMetaDataParserService( 3663): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/a       ( 1914): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 1914): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1914): Clearing transaction cache
,I/SurfaceFlinger(  258): id=6 Removed Mauncher (5/8)
,I/GCoreUlr( 1774): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/BluetoothAdapter( 3892): 201853901: getState() :  mService = null. Returning STATE_OFF
,W/libprocessgroup( 1017): failed to open /acct/uid_10072/pid_1554/cgroup.procs: No such file or directory
,E/SPPClientService( 3927): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 3927): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 3927): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,W/art     ( 3892): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 1914): Explicit concurrent mark sweep GC freed 28563(2MB) AllocSpace objects, 26(416KB) LOS objects, 39% free, 10MB/17MB, paused 1.139ms total 91.170ms
,W/chromium( 3892): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,W/AwContents( 3892): onDetachedFromWindow called when already detached. Ignoring
,E/SMD     (  288): DCD OFF
,D/PhoneWindow( 3892): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 3892): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 3892): CordovaWebView is running on device made by: samsung
,D/SPPClientService( 3927): PushLog.txt file is not deleted.
,D/SPPClientService( 3927): PushLog.txt file is not deleted.
,W/art     ( 3892): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3892): Attempt to remove local handle scope entry from IRT, ignoring
D/SPPClientService( 3927): ============PushLog. stop!
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.660104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f95840 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f76d38 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3663): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3663): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3663): getResourcePackageName:assistant
I/AMMetaDataParserService( 3663): Resource data:2131034112
,I/AMMetaDataParserService( 3663): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3663): getResourceTypeNamexml
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.824063ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f5aee8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f76d38 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,I/AMMetaDataParserService( 3663): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/OpenGLRenderer( 3892): Render dirty regions requested: true
,E/Zygote  ( 3978): MountEmulatedStorage()
E/Zygote  ( 3978): v2
I/libpersona( 3978): KNOX_SDCARD checking this for 10041
I/libpersona( 3978): KNOX_SDCARD not a persona
,I/SELinux ( 3978): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=3978 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3978): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3978): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 3136:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,D/PhoneWindow( 3892): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3892): *FMB* isFloatingMenuEnabled return false
,E/File    ( 3699): fail readDirectory() errno=2
,I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, NainActivit
,I/Gmail   ( 3699): notifyAccountChanged
,D/TimaKeyStoreProvider( 3978): TimaSignature is unavailable
,D/ActivityThread( 3978): Added TimaKeyStore provider
,D/InputDispatcher( 1017): Focus entered window: 3892
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 3892): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 3892): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3892): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3892): Enabling debug mode 0
,I/Gmail   ( 3699): getAccountsCursor
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PowerManagerService( 1017): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1176 (0x0)
,I/ActivityManager( 1017): Killing 3047:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,I/Gmail   ( 3699): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10003/pid_3136/cgroup.procs: No such file or directory
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
,I/ActivityManager( 1017): Displayed Component not be shown by security: +1s213ms
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{137f514 u0 com.example.hello/.MainActivity t2} time:40880
W/ActivityManager( 1017): mDVFSHelper.release()
I/DBG_DM  ( 2986): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/Timeline( 3892): Timeline: Activity_idle id: android.os.BinderProxy@23297fe7 time:40894
,I/SamsungIME( 1792): getCurrentCandidateView
W/libprocessgroup( 1017): failed to open /acct/uid_10057/pid_3047/cgroup.procs: No such file or directory
,D/SSRM:n  ( 1017): SIOP:: AP = 370
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 3699): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/SA      ( 3978): [SSP] onCreated
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/BindingManager( 3892): Cannot call determinedVisibility() - never saw a connection for the pid: 3892
,I/Babel   ( 3858): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3858): MmsConfig.loadMmsSettings
I/Babel   ( 3858): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 3858): MmsConfig.loadFromDatabase
,I/Gmail   ( 3699): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3699): calculateUnknownSyncRationalesAndPurgeInBackground: running
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.626927ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f5aee8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f76d38 counterpartCT=4 counterpartW=96 counterparth=96
,E/Babel   ( 3858): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3858): MmsConfig.loadFromResources
,I/SurfaceFlinger(  258): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  258): id=10 Removed iello (-2/8)
,D/ChimeraCfgMgr( 1914): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/Babel   ( 3858): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3858): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/SystemUpdateService( 1914): onDestroy,
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
I/AMMetaDataParserService( 3663): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
I/chromium( 3892): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1774): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/GCoreFlp( 1774): No location to return for getLastLocation()
,W/FusedLocationProvider( 1914): location=null
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,W/Auth    ( 1630): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,I/SA      ( 3978): [TPM] There is no property file
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.692657ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f76d38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f98c90 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.722187ms for 96*96 texture 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Kids    ( 1914): [AbstractKidsOperation] Invalid device state 3
,I/SA      ( 3978): [SCU] isHaveSA() - false
,I/Kids    ( 1914): [KidAccountFixer] No network connection
,I/SA      ( 3978): [TPM] getModelProperty : null
I/SA      ( 3978): [TPM] getCSCProperty : null
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f8fcb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f59c78 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 3978): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 3978): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 3978): [DM] TFT FEATURE: false
,I/AMMetaDataParserService( 3663): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,I/GCoreUlr( 1774): Unbound from all location providers
,I/SA      ( 3978): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 3978): [DM] init START
,V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SamsungIME( 1792): Dismiss ExpandCandiate
,I/SA      ( 3978): [DM] This device is not a Vodafone
,D/JsMessageQueue( 3892): Set native->JS mode to OnlineEventsBridgeMode
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
,E/AndroidProtocolHandler( 3892): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
V/GmsCoreStatsServiceLauncher( 1914): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.,contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:assistant
I/AMMetaDataParserService( 3663): Resource data:2131034113
I/AMMetaDataParserService( 3663): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3663): getResourceTypeNamexml
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3663): took 0.803854ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f10ae0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f6f600 counterpartCT=4 counterpartW=96 counterparth=96
I/EventLogService( 1914): Aggregate from 1448707064874 (log), 1448707064874 (data)
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/AMMetaDataParserService( 3663): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.825416ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f10ae0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f83d20 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/AMMetaDataParserService( 3663): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/GCoreFlp( 1774): No location to return for getLastLocation()
,W/FusedLocationProvider( 1914): location=null
,W/ResourceType( 3978): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 3978): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 3978): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 3978): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 3978): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 3978): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 3978): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 3978): No package identifier when getting value for resource number 0x00000000
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.610781ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f777d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bb1ee8 counterpartCT=4 counterpartW=96 counterparth=96
,W/Settings( 3858): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/AMMetaDataParserService( 3663): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/ResourceType( 3978): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 3978): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 3978): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 3978): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 3978): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 3978): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 3978): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 3978): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 3978): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 3978): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 3978): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 3978): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 3978): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 3978): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 3978): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 3978): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 3978): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,D/PackageManager( 1017): [MSG] MCS_UNBIND
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.622344ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f5aee8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f98c20 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/SA      ( 3978): [SCU] isHaveSA() - false
,I/SA      ( 3978): support phone number id : false
,I/SA      ( 3978): [DM] Supports Ref Jpn : true
,I/SA      ( 3978): [DM] init END
,I/ActivityManager( 1017): Killing 2969:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/jxcore_app_log( 3892): JniHelper::setJavaVM(0xb8baa450), pthread_self() = -1190089768
,D/JX-Cordova( 3892): jxcore cordova android initializing
,I/SA      ( 3978): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 3978): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/PersistentNotificationBroadcastReceiver( 1630): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,I/GFX raster( 3663): took 1.090521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f76b38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bfd8f0 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3663): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,E/Zygote  ( 4018): MountEmulatedStorage()
E/Zygote  ( 4018): v2
I/libpersona( 4018): KNOX_SDCARD checking this for 10028
I/libpersona( 4018): KNOX_SDCARD not a persona
,I/SELinux ( 4018): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4018 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
D/ActivityManager( 1017): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,I/SELinux ( 4018): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4018): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,W/jxcore-log( 3892): Initializing JXcore engine
W/jxcore-log( 3892): JXcore engine is ready
,W/jxcore-log( 3892): Starting JXcore engine
,D/TimaKeyStoreProvider( 4018): TimaSignature is unavailable
,D/ActivityThread( 4018): Added TimaKeyStore provider
,I/Babel_StickerModule( 3858): App launched.
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.674896ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f8fcb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f98c90 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 3978): [OR] onReceive END
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3663): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/Zygote  ( 4035): MountEmulatedStorage(),
E/Zygote  ( 4035): v2
I/libpersona( 4035): KNOX_SDCARD checking this for 10042
I/libpersona( 4035): KNOX_SDCARD not a persona
,I/SELinux ( 4035): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4035): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1017): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4035 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4035): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
I/GCoreUlr( 1774): DispatchingService.onDestroy()
I/GCoreUlr( 1774): Stopping handler for UlrDispSvcFast
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/SA      ( 3978): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/GFX raster( 3663): took 0.680417ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f98bb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f59c78 counterpartCT=4 counterpartW=96 counterparth=96
I/SA      ( 3978): [ODM] queryOpenData(key= GEO_IP )
,I/GCoreUlr( 1774): Unbound from all location providers
I/AMMetaDataParserService( 3663): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/libprocessgroup( 1017): failed to open /acct/uid_10085/pid_2969/cgroup.procs: No such file or directory
,E/audit   ( 1904): type=1400 msg=audit(1448709355.654:203): avc:  denied  { ioctl } for  pid=3892 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1904):  SEPF_SM-A500FU_5.0.2-1_0038
,E/audit   ( 1904): type=1300 msg=audit(1448709355.654:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=bead7d58 items=0 ppid=305 ppcomm=main pid=3892 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1904): type=1320 msg=audit(1448709355.654:203): 
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.553386ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f95840 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f6f600 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4035): TimaSignature is unavailable
,D/ActivityThread( 4035): Added TimaKeyStore provider
,I/SA      ( 3978): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 3978): [LBE] REF_JPN : true
,I/SA      ( 3978): [BDC] create
,I/SamsungIME( 1792): getDebugLevel  : 0x4f4c
,W/ResourcesManager( 4035): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3663): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,V/Babel   ( 3858): babel boot account: SMS
,W/Babel   ( 3858): EsDatabaseHelper.static should not be called on main thread [called on main thread]
,I/SecDataIO(  257): Write to block
,W/jxcore-log( 3892): Platform android
W/jxcore-log( 3892): 
,W/jxcore-log( 3892): Process ARCH arm
W/jxcore-log( 3892): 
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
W/ContextImpl( 3663): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,W/ContextImpl( 2527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,W/Babel   ( 3858): java.lang.Exception
W/Babel   ( 3858): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3858): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 3858): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3858): 	at ckh.a(SourceFile:67)
W/Babel   ( 3858): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3858): 	at bhn.a(SourceFile:301)
W/Babel   ( 3858): 	at bhn.a(SourceFile:137)
W/Babel   ( 3858): 	at bhn.a(SourceFile:126)
W/Babel   ( 3858): 	at bhn.a(SourceFile:159)
W/Babel   ( 3858): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3858): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3858): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3858): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3858): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3858): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3858): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3858): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3858): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3858): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3858): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/Babel   ( 3858): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 3858): java.lang.Exception
W/Babel   ( 3858): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3858): 	at aes.a(SourceFile:145)
W/Babel   ( 3858): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3858): 	at ckh.a(SourceFile:67)
W/Babel   ( 3858): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3858): 	at bhn.a(SourceFile:301)
W/Babel   ( 3858): 	at bhn.a(SourceFile:137)
W/Babel   ( 3858): 	at bhn.a(SourceFile:126)
W/Babel   ( 3858): 	at bhn.a(SourceFile:159)
W/Babel   ( 3858): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3858): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3858): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3858): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3858): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3858): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3858): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3858): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3858): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3858): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3858): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/jxcore-log( 3892): JXcore Cordova bridge is ready!
I/jxcore-log( 3892): 
,W/jxcore-log( 3892): JXcore engine is started
,I/CalendarProvider2( 4035): CalendarProvider2.onCreate() called
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 29398(1722KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 26MB/39MB, paused 2.496ms total 154.152ms
,I/Process ( 2527): Sending signal. PID: 2527 SIG: 9
,I/DBG_DM  ( 2986): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 2986): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,E/DBG_DM  ( 2986): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,I/SamsungIME( 1792): getDebugLevel  : 0x4f4c
,I/DBG_DM  ( 2986): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,I/SA      ( 3978): [DBMV2] getEmailID
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
,I/Gmail   ( 3699): getAccountsCursor
,I/DBG_DM  ( 2986): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,E/jxcore-log( 3892): >> samsung-SM-A500FU
E/jxcore-log( 3892): 
,I/jxcore-log( 3892): Total memory 1983791104
I/jxcore-log( 3892): 
,I/jxcore-log( 3892): Free memory 132190208
I/jxcore-log( 3892): 
I/jxcore-log( 3892): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3892): 
I/jxcore-log( 3892): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3892): 
,I/DBG_DM  ( 2986): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 2986): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,I/SA      ( 3978): [DBMV2] getDataV02ForItems
I/SA      ( 3978): [SSP] query invoked
,I/jxcore-log( 3892): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 3892): 
,I/jxcore-log( 3892): Size 720 1280
I/jxcore-log( 3892): 
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.Welcome
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.Mes,sageListXL
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:assistant
I/AMMetaDataParserService( 3663): Resource data:2131165203
I/SA      ( 3978): [SCU] get signed id from samsung account2.0 DB.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
I/jxcore-log( 3892): Screen Brightness 5
I/jxcore-log( 3892): 
E/DBG_DM  ( 2986): [IlIIlIIlIllllIlllIII(226/llIIIIlllllIIllIIllI)] Network Status is not ready. DM Not Initialized
E/jxcore-log( 3892): Dummy Error Log.
E/jxcore-log( 3892): 
W/ResourcesManager( 3663): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
V/Babel   ( 3858): babel boot account: thalitester@gmail.com
I/ActivityManager( 1017): Process com.sec.android.app.sysscope (pid 2527)(adj 0) has died(127,1106)
I/DBG_DM  ( 2986): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
W/Babel   ( 3858): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
W/Babel   ( 3858): java.lang.Exception
W/Babel   ( 3858): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3858): 	at aes.a(SourceFile:145)
W/Babel   ( 3858): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3858): 	at ckh.a(SourceFile:67)
W/Babel   ( 3858): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3858): 	at bhn.a(SourceFile:301)
W/Babel   ( 3858): 	at bhn.a(SourceFile:137)
W/Babel   ( 3858): 	at bhn.a(SourceFile:126)
W/Babel   ( 3858): 	at bhn.a(SourceFile:159)
W/Babel   ( 3858): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3858): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3858): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3858): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3858): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3858): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3858): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3858): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3858): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3858): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3858): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/AMMetaDataParserService( 3663): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3663): getResourceTypeNamexml
,I/SamsungIME( 1792): KeybaordView init() : load resources
,I/SA      ( 3978): [SCU] get signed id from samsung account1.0 DB.
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/SA      ( 3978): [BDC] destroy
,I/ActivityManager( 1017): Killing 3169:com.fmm.dm/1000 (adj 15): empty #31
,I/GFX construct_block_size_descriptor_2d second part( 3663): took 3.025467ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3663): took 10.087083ms for 0*0 texture 0
,I/GFX raster( 3663): took 13.994008ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f768f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9147c90 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,D/GCMRegistrar( 3329): resetting backoff for com.dropbox.android
,V/GCMRegistrar( 3329): Registering app com.dropbox.android of senders 735665981150
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.google.process.gapps
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
I/SamsungIME( 1792): getCurrentKeyboard
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
I/SamsungIME( 1792): getTextKeyboard
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.824219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f66ae0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f66b88 counterpartCT=4 counterpartW=96 counterparth=96
,D/GCM     ( 1630): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,D/SamsungIME( 1792): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3663): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,I/GCM     ( 1630): GCM config loaded
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3169/cgroup.procs: No such file or directory
,E/Zygote  ( 4068): MountEmulatedStorage()
,E/Zygote  ( 4068): v2
I/libpersona( 4068): KNOX_SDCARD checking this for 1000
I/libpersona( 4068): KNOX_SDCARD not a persona
,I/SELinux ( 4068): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4068 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 4068): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4068): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     (  305): Explicit concurrent mark sweep GC freed 8689(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 791us total 25.321ms
,D/TimaKeyStoreProvider( 4068): TimaSignature is unavailable
,D/ActivityThread( 4068): Added TimaKeyStore provider
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.828594ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f66ae0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f943b0 counterpartCT=4 counterpartW=96 counterparth=96
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 747us total 22.337ms
,I/AMMetaDataParserService( 3663): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  283): getCameraInfo: X
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 19.648ms
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  283): getCameraInfo: X
,I/System.out( 1630): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,W/VideoCapabilities( 3858): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 3858): Unsupported mime audio/evrc
,W/AudioCapabilities( 3858): Unsupported mime audio/qcelp
,D/Finsky  ( 4018): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/AudioCapabilities( 3858): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3858): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 3858): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 3858): Unsupported mime audio/x-ima
,W/AudioCapabilities( 3858): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3858): Unsupported mime audio/evrc
,W/VideoCapabilities( 3858): Unsupported mime video/wvc1
,W/VideoCapabilities( 3858): Unsupported mime video/x-ms-wmv
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.800989ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f66ae0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8bfed38 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,W/VideoCapabilities( 3858): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 3858): Unsupported mime video/wvc1
,W/VideoCapabilities( 3858): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 3858): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 3858): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 3858): Unsupported mime video/mp43
,W/VideoCapabilities( 3858): Unsupported mime video/sorenson
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.646353ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f5aee8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f10ae0 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 3858): Unsupported mime video/mp4v-esdp
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3663): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,I/VideoCapabilities( 3858): Unsupported profile 4 for video/mp4v-es
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.622916ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f5aee8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bfed38 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,I/AMMetaDataParserService( 3663): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4094): MountEmulatedStorage(),
E/Zygote  ( 4094): v2,
I/libpersona( 4094): KNOX_SDCARD checking this for 1000,
I/libpersona( 4094): KNOX_SDCARD not a persona,
,I/SELinux ( 4094): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1017): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4094 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 4094): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4094): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 3189:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31,
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/iu.UploadsManager( 1914): End new media; added: 0, uploading: 0, time: 97 ms,
,D/TimaKeyStoreProvider( 4094): TimaSignature is unavailable
,D/ActivityThread( 4094): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
W/ContextImpl( 3663): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3663): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/jxcore-log( 3892): getBuffer is called!!!!
I/jxcore-log( 3892): 
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3663): getResourcePackageName:android.app.default_searchable
,I/AMMetaDataParserService( 3663): getResourcePackageName:assistant
I/AMMetaDataParserService( 3663): Resource data:2131099648
,W/ResourcesManager( 3663): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 3663): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3663): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 3663): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3663): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3663): getResourceTypeNamexml
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.692240ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f8f568 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f63ad8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/libprocessgroup( 1017): failed to open /acct/uid_10060/pid_3189/cgroup.procs: No such file or directory
,D/KnoxSetupWizardDbHelper( 4094): dbMigrationFlag : false
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3663): took 2.334583ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3663): took 8.698282ms for 0*0 texture 0
,I/GFX raster( 3663): took 12.116460ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb948c2f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb948c398 counterpartCT=4 counterpartW=96 counterparth=96
,D/ShortcutReceiver( 4094):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,D/KnoxShortcutUtil( 4094): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4094):  KnoxContainerVersion 2.4.0
,D/ShortcutReceiver( 4094):  shortcut migration not required 
,I/AMMetaDataParserService( 3663): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 3858): (284) automatic index on conversation_participants_view(conversation_id),
,E/Zygote  ( 4121): MountEmulatedStorage()
,E/Zygote  ( 4121): v2
I/libpersona( 4121): KNOX_SDCARD checking this for 1000
I/ActivityManager( 1017): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4121 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/libpersona( 4121): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Killing 3242:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
I/SELinux ( 4121): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4121): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4121): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4121): TimaSignature is unavailable
,D/ActivityThread( 4121): Added TimaKeyStore provider
,E/SQLiteLog( 3858): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 3858): (284) automatic index on conversation_participants_view(conversation_id)
,E/KnoxSetupWizardClient( 4121): isShipMode : 1
,D/ActivityManager( 1017): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,I/KnoxSetupWizardClient( 4121): onReceive : android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.679323ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb94927a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb94928d8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 4018): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3242/cgroup.procs: No such file or directory
,E/Zygote  ( 4143): MountEmulatedStorage()
I/libpersona( 4143): KNOX_SDCARD checking this for 10107
E/Zygote  ( 4143): v2
I/libpersona( 4143): KNOX_SDCARD not a persona
I/SELinux ( 4143): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4143 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 4143): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4143): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 3259:com.fmm.ds/1000 (adj 15): empty #31
,E/SQLiteLog( 3858): (284) automatic index on conversation_participants_view(conversation_id)
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.720261ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb94917b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb94917e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/Settings( 4018): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4018): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/System.err( 4121): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
D/TimaKeyStoreProvider( 4143): TimaSignature is unavailable
W/System.err( 4121): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4121): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4121): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 4121): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
W/System.err( 4121): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4121): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,D/ActivityThread( 4143): Added TimaKeyStore provider
,E/SQLiteLog( 3858): (284) automatic index on conversation_participants_view(conversation_id)
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.628489ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f63d90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f63e38 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3259/cgroup.procs: No such file or directory
,I/ActivityManager( 1017): Killing 3291:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 1.113333ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb9491f18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9491fc0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:assistant
I/AMMetaDataParserService( 3663): Resource data:2131099648
,I/AMMetaDataParserService( 3663): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3663): getResourceTypeNamexml
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.878281ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f8f568 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9492948 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.835937ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb948c2f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb948c038 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.805209ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb94927a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9491fc0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/Volley  ( 4018): [613] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 4018): [606] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager( 1017): Killing 3274:com.google.android.configupdater/u0a86 (adj 15): empty #31
,D/ActivityManager( 1017): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/libprocessgroup( 1017): failed to open /acct/uid_10062/pid_3291/cgroup.procs: No such file or directory
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.677707ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb94917b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9491e48 counterpartCT=4 counterpartW=96 counterparth=96
,D/Finsky  ( 4018): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4018): [1] Libraries$2.run: Finished loading 1 libraries.
,I/AMMetaDataParserService( 3663): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.644843ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f63d90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9491e48 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/SamsungIME( 1792): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/Ads     ( 4018): Skipping gmscore version check
,D/Finsky  ( 4018): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
I/GFX raster( 3663): took 0.732760ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb9491f18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f631a8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1017): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/AMMetaDataParserService( 3663): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:assistant
I/AMMetaDataParserService( 3663): Resource data:2131099648
,I/AMMetaDataParserService( 3663): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3663): getResourceTypeNamexml
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.692552ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f8f568 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f631a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/libprocessgroup( 1017): failed to open /acct/uid_10086/pid_3274/cgroup.procs: No such file or directory
,D/Finsky  ( 4018): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.684168ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb948c2f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb9491e48 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.644792ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb94927a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8f631a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.653854ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb94917b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9491e48 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/StrictMode( 4143): StrictMode policy violation; ~duration=228 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4143): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4143): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4143): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4143): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4143): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4143): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4143): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4143): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4143): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4143): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4143): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4143): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4143): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4143): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4143): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4143): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4143): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4143): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4143): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4143): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4143): StrictMode policy violation; ~duration=219 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4143): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4143): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4143): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4143): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4143): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4143): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4143): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4143): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4143): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4143): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4143): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4143): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4143): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4143): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4143): ,	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4143): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4143): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4143): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4143): StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4143): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4143): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4143): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4143): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4143): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4143): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4143): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4143): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4143): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4143): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4143): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4143): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4143): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4143): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4143): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4143): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4143): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4143): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4143): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4143): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4143): StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4143): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4143): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4143): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4143): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4143): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4143): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4143): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4143): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4143): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4143): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4143): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4143): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4143): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4143): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4143): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4143): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4143): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4143): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4143): StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4143): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4143): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4143): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4143): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4143): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4143): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4143): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4143): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4143): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4143): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4143): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4143): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4143): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4143): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4143): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4143): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4143): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4143): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4143): StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4143): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4143): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4143): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4143): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4143): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4143): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4143): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4143): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4143): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4143): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4143): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4143): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4143): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4143): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4143): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4143): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4143): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4143): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4143): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4143): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4143): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4143): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4143): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4143): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4143): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4143): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4143): StrictMode policy violation; ~duration=160 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4143): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4143): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4143): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4143): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4143): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4143): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4143): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4143): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4143): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4143): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4143): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4143): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4143): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4143): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4143): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4143): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4143): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4143): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4143): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4143): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4143): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4143): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4143): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4143): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4143): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4143): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4143): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4143): StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4143): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4143): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4143): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4143): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4143): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4143): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4143): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 4143): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4143): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4143): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4143): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4143): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4143): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4143): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4143): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4143): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4143): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4143): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4143): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4143): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4143): StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4143): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4143): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4143): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4143): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4143): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4143): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4143): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4143): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4143): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4143): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4143): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4143): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4143): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4143): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4143): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4143): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4143): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3663): took 0.637292ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f63d90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f631a8 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3663): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4173): MountEmulatedStorage()
E/Zygote  ( 4173): v2
I/libpersona( 4173): KNOX_SDCARD checking this for 1000
I/libpersona( 4173): KNOX_SDCARD not a persona
I/SELinux ( 4173): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4173): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4173 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3329:com.dropbox.android/u0a92 (adj 15): empty #31
E/SELinux ( 4173): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/GFX raster( 3663): took 0.868854ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb9491f18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9491e48 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3663): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:assistant
I/AMMetaDataParserService( 3663): Resource data:2131099648
I/AMMetaDataParserService( 3663): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3663): getResourceTypeNamexml
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3663): took 0.765417ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f8f568 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9491e48 counterpartCT=4 counterpartW=96 counterparth=96
D/TimaKeyStoreProvider( 4173): TimaSignature is unavailable
D/ActivityThread( 4173): Added TimaKeyStore provider
I/AMMetaDataParserService( 3663): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.729323ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb948c2f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8f631a8 counterpartCT=4 counterpartW=96 counterparth=96
,W/com.google.a.a.b.d.a( 4143): Application name is not set. Call Builder#setApplicationName.
,I/AMMetaDataParserService( 3663): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/GFX raster( 3663): took 0.619584ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb94927a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8f467d8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3663): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/StatusChecker( 4173): onReceive : android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,I/StatusChecker( 4173): onReceive : net.mt.init : DONE
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.677812ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb94917b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9491e48 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3663): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3663): took 0.621407ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f63d90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f631a8 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4191): MountEmulatedStorage(),
I/AMMetaDataParserService( 3663): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/Zygote  ( 4191): v2
I/libpersona( 4191): KNOX_SDCARD checking this for 10116,
I/libpersona( 4191): KNOX_SDCARD not a persona
,I/SELinux ( 4191): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4191 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3104:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,I/SELinux ( 4191): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4191): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1017): failed to open /acct/uid_10092/pid_3329/cgroup.procs: No such file or directory
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.759218ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb9491f18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f467d8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/TimaKeyStoreProvider( 4191): TimaSignature is unavailable
,D/ActivityThread( 4191): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:assistant
I/AMMetaDataParserService( 3663): Resource data:2131099648
,I/AMMetaDataParserService( 3663): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3663): getResourceTypeNamexml
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.672083ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f8f568 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f631a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.644219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb948c2f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb9491e48 counterpartCT=4 counterpartW=96 counterparth=96
,I/PageBuddyNotiSvc( 4191): Intent received : action=android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3663): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ContextImpl( 4191): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3663): took 0.618646ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb94927a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8f8a108 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1017): failed to open /acct/uid_10009/pid_3104/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/PageBuddyNotiSvc( 4191): onCreate mCpBitFlag=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3663): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4207): MountEmulatedStorage(),
E/Zygote  ( 4207): v2
I/libpersona( 4207): KNOX_SDCARD checking this for 10125,
I/libpersona( 4207): KNOX_SDCARD not a persona
,I/SELinux ( 4207): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4207 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.676302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb94917b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f467d8 counterpartCT=4 counterpartW=96 counterparth=96
I/SELinux ( 4207): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4207): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3663): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.648698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f63d90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f631a8 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4207): TimaSignature is unavailable
,D/ActivityThread( 4207): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3663): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ResourcesManager( 4207): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4207): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4207): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.737656ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb9491f18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9491e48 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3663): Resource data:2131099648
,I/AMMetaDataParserService( 3663): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3663): getResourceTypeNamexml
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.767083ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f8f568 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f467d8 counterpartCT=4 counterpartW=96 counterparth=96
,D/QuickConnect( 4207): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 4207): Util.setSCRunningSetting - [value]0
,D/SettingsProvider( 1017): name = scon_is_running
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 10125
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/AMMetaDataParserService( 3663): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/QuickConnect( 4207): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/QuickConnect( 4207): PeriphStartReceiver.onReceive - no need to start
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3663): took 0.687240ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb948c2f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8f8a108 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/Zygote  ( 4222): MountEmulatedStorage(),
E/Zygote  ( 4222): v2
I/libpersona( 4222): KNOX_SDCARD checking this for 10131
I/libpersona( 4222): KNOX_SDCARD not a persona
,I/SELinux ( 4222): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/ActivityManager( 1017): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4222 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/GFX raster( 3663): took 0.821562ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb94927a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8f87680 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 4222): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Killing 3371:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
E/SELinux ( 4222): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3663): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/TimaKeyStoreProvider( 4222): TimaSignature is unavailable
,D/ActivityThread( 4222): Added TimaKeyStore provider
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.652969ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb94917b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f631a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ResourcesManager( 4222): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4222): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4222): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4222): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.793490ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb8f63d90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9491e48 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.939688ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb9491f18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f467d8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3663): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
W/ContextImpl( 3663): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3663): Resource data:Loop for ,running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3663): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:android.app.default_searchable,
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
D/SBrowserFeatureFlag( 4222): initialized in static block : loadCscFeatureValue() succeed! 
,I/GAV2    ( 3699): Thread[GAThread,5,main]: No campaign data found.
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:assistant
I/AMMetaDataParserService( 3663): Resource data:2131165197
,W/ResourcesManager( 3663): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3663): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3663): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3663): getResourceTypeNamexml
,D/ManifestProvider( 4222): onCreate()
,I/AMMetaDataParserService( 3663): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3663): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,E/NetworkSettingsReceiver( 4222): onReceive: android.intent.action.BOOT_COMPLETED
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3371/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3663): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
E/SMD     (  288): DCD OFF
,E/SBrowserFeatureFlag( 4222): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@2bfc3f93
,D/SBrowserFeatureFlag( 4222): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4222): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4243): MountEmulatedStorage(),
E/Zygote  ( 4243): v2
I/libpersona( 4243): KNOX_SDCARD checking this for 10135
,I/libpersona( 4243): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4243 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 4243): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Killing 3359:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,I/SELinux ( 4243): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4243): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4243): TimaSignature is unavailable
,D/ActivityThread( 4243): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3663): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/CalendarProvider2( 4035): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3663): getResourcePackageName:assistant
I/AMMetaDataParserService( 3663): Resource data:2131165197
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3663): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3663): getResourceTypeNamexml
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/ActivityManager( 1017): Killing 3407:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,I/AMMetaDataParserService( 3663): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/ResourcesManager( 4243): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4243): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4243): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3663): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3663): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3663): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:assistant
I/AMMetaDataParserService( 3663): Resource data:2131165197
,I/AMMetaDataParserService( 3663): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3663): getResourceTypeNamexml
,D/ActivityManager( 1017): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/AMMetaDataParserService( 3663): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3663): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/ActivityManager( 1017): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/libprocessgroup( 1017): failed to open /acct/uid_10014/pid_3359/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10092/pid_3407/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,I/AMMetaDataParserService( 3663): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4266): MountEmulatedStorage(),
E/Zygote  ( 4266): v2
I/libpersona( 4266): KNOX_SDCARD checking this for 10139
,I/libpersona( 4266): KNOX_SDCARD not a persona
,I/SELinux ( 4266): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/AMMetaDataParserService( 3663): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
I/SELinux ( 4266): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1017): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4266 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,E/SELinux ( 4266): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
W/ContextImpl( 3663): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3663): getResourcePackageName:assistant
I/AMMetaDataParserService( 3663): Resource data:2131099648
,W/ResourcesManager( 3663): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3663): getResourceName:com.sec.android.app.camera:xml/assistant
,I/AMMetaDataParserService( 3663): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 4266): TimaSignature is unavailable
,D/ActivityThread( 4266): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3663): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,W/ResourcesManager( 4266): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4266): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4266): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 4266): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4266): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3663): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,W/ContextImpl( 3663): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,I/ActivityManager( 1017): Killing 3083:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4283): MountEmulatedStorage()
I/libpersona( 4283): KNOX_SDCARD checking this for 10145
E/Zygote  ( 4283): v2
I/libpersona( 4283): KNOX_SDCARD not a persona
I/SELinux ( 4283): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4283 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/SELinux ( 4283): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Killing 3396:com.wssnps/1000 (adj 15): empty #31
,E/SELinux ( 4283): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4283): TimaSignature is unavailable
,D/ActivityThread( 4283): Added TimaKeyStore provider
,W/ResourcesManager( 4283): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4283): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4283): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4283): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4283): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:assistant
I/AMMetaDataParserService( 3663): Resource data:2131165220
,W/ResourcesManager( 3663): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3663): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3663): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3663): getResourceTypeNamexml
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.695208ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb96a8928 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb96a8658 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,E/        ( 3663): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3663): took 0.592605ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3663): Bitmap=0xb96a8778 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb96bba68 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3663): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,W/libprocessgroup( 1017): failed to open /acct/uid_10015/pid_3083/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3396/cgroup.procs: No such file or directory
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SubSettings
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  chec,k
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure,
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection,
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity,
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3663): Resource data,:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED,
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.LanguageSettings
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
W/ContextImpl( 3663): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/ActivityManager( 1017): Killing 3449:com.samsung.android.sm/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.CredentialStorage
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.MediaFormat
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Display
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.TestingSettings
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.CryptKeeper
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
D/RCPManagerService( 1017): exchangeData() failure , invalid userId
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.SearchActivity
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3663): getResourcePackageName:android.app.searchable
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.activekey.AppList
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3663): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3663): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3663): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
D/RCPManagerService( 1017): exchangeData() failure , invalid userId
D/RCPManagerService( 1017): exchangeData() failure , invalid userId
D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/Zygote  ( 4305): MountEmulatedStorage()
I/libpersona( 4305): KNOX_SDCARD checking this for 10072
E/Zygote  ( 4305): v2
I/libpersona( 4305): KNOX_SDCARD not a persona
I/SELinux ( 4305): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4305): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4305 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/SELinux ( 4305): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): startService callerProcessName:com.android.email, calleePkgName: com.android.email
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3449/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4305): TimaSignature is unavailable
,D/ActivityThread( 4305): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 8760(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 641us total 24.276ms
,I/splitIntent( 1017): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1017): Killing 3551:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 3526:com.android.managedprovisioning/u0a22 (adj 15): empty #32
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 18.494ms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/BadgeProvider( 4305): onCreate
D/BadgeProvider( 4305): DatabaseHelper
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 17.595ms
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 25302(1577KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/39MB, paused 2.226ms total 135.977ms
,I/splitIntent( 1017): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1017): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1017): other index=3, name=com.google.android.gms com.google.android.gms.photos.InitializePhotosIntentReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BadgeProvider( 4305): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1774): callingUid 10012, callindPid: 1774
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BadgeProvider( 4305): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4305): sendNotify, [notify] : null
D/BadgeProvider( 4305): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4305): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4305): update, [UpdateCount] : 1
,D/Launcher.Model( 1469): reloadBadges entered.
,E/MDM     ( 1774): [193] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1914): Restart initialization of location
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Process ( 4283): Sending signal. PID: 4283 SIG: 9
,D/GCM     ( 1630): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1630): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1017): failed to open /acct/uid_10022/pid_3526/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3551/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1630): Explicit concurrent mark sweep GC freed 10233(635KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 10MB/18MB, paused 1.057ms total 41.528ms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1914): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1774): No location to return for getLastLocation()
,W/FusedLocationProvider( 1630): location=null
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,I/ActivityManager( 1017): Process com.android.email (pid 4283)(adj 9) has died(92,1125)
,D/ActivityManager( 1017): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MTPRx   ( 3569): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedState
D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1017): mCursor = null
,V/MTPRx   ( 3569): sealedState: false
V/MTPRx   ( 3569): sealedUsbMassStorageState: false
E/MTPRx   ( 3569): check value of boot_completed is1
E/MTPRx   ( 3569): check booting is completed_sys.boot_completed
,E/MTPRx   ( 3569): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 3569): Status for mount/Unmount :removed
,E/MTPRx   ( 3569): SDcard is not available
,W/MTPRx   ( 3569): value of connected istrue
W/MTPRx   ( 3569): value of configured istrue
W/MTPRx   ( 3569): value of mtpEnabled istrue
W/MTPRx   ( 3569): value of ptpEnabled isfalse
,E/MTPRx   ( 3569): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 3569): mFirstTime: false
,D/        ( 3569): MTP: reading debug level property
,I/ValidateNoPeople( 1017): mEvictionCount: 0
,E/MTPJNIInterface( 3569): Getting CryptionKey from JAVA
E/MTPRx   ( 3569): currentUserId is 0
,E/MTPRx   ( 3569): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 3569): cannot open file : /sys/class/android_usb/android0/bcdUSB
,E/MTPRx   ( 3569): is_Privatemode is NOT 1
,D/SettingsProvider( 1017): name = boot_time_connected
,E/MTPRx   ( 3569): Sending NORMAL_BOOT to stack
,E/MTPJNIInterface( 3569): noti = 17
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,D/SecContentProvider( 1017): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 3569): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1017): name = mtp_running_status
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,E/MTPRx   ( 3569): else part ... so first time!!!
,E/MTPPlaObsrvr( 3569): inside setContext()
E/MTPPlaObsrvr( 3569):  inside createplafiles
,E/MTPPlaObsrvr( 3569): playlist count is0
E/MTPPlaObsrvr( 3569):  inside try branch createplafiles
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
E/MTPPlaObsrvr( 3569):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 3569): Inside registerContentObserver
,E/MtpAdbObserver( 3569): inside setContext()
,E/MtpAdbObserver( 3569): Inside registerContentObserver
W/Settings( 3569): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,V/MtpMediaDBManager( 3569): inside deleteAllDB
,D/SettingsProvider( 1017): name = mtp_running_status
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,D/ActivityManager( 1017): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MtpService( 3569): onCreate.
,D/MtpService( 1231): updating state; isCurrentUser=true, mMtpLocked=false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,E/MtpService( 3569): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3569): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 3569): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/MtpService( 3569): onStartCommand.
,W/MTPRx   ( 3569): calling native method
E/MTPJNIInterface( 3569): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3569): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1774): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,E/MTPJNIInterface( 3569): < MTP > Registering BroadCast receiver :::::::
,V/MtpMediaDBManager( 3569): inside Thread updateDB
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/MTPJNIInterface( 3569): noti = 10
E/MtpService( 3569): onStartCommand.
W/MTPRx   ( 3569): calling native method
,E/MTPRx   ( 3569): Checking the driver time out
E/MTPJNIInterface( 3569): noti = 2
E/MtpService( 3569): handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
D/        ( 3569): deleting sockets before message queue initialization
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/        ( 3569): event handler thread is created, so set the flag
,E/MTPRx   ( 3569): called native method
E/MTPJNIInterface( 3569): setting Media scanner status0
E/MTPJNIInterface( 3569): After setting Media scanner status0
,E/        ( 3569): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 3569): Getting media scanner status0
,W/MTPRx   ( 3569): notification from stack 1
,E/MTPJNIInterface( 3569): DeviceName is A5-1
,E/MtpMediaDBManager( 3569): count : 27
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1311): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1311): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1311): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1311): [MSC_Daemon]>>> ====================================================================================================================
W/MtpMediaDBManager( 3569): sending db update complete noti to stack
E/MTPJNIInterface( 3569): noti = 29
D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/SQLiteLog( 3569): (5) database is locked
,D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1448730900000
D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1448709358847
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1311): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1311): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/MTPJNIInterface( 3569): Status for mount/Unmount :removed
E/MTPJNIInterface( 3569): SDcard is not available
,E/Zygote  ( 4340): MountEmulatedStorage()
,I/libpersona( 4340): KNOX_SDCARD checking this for 10111
E/Zygote  ( 4340): v2
I/libpersona( 4340): KNOX_SDCARD not a persona
,E/        ( 3569): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,I/SELinux ( 4340): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4340): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/        ( 3569): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] ,
I/ActivityManager( 1017): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=4340 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4340): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/MTPJNIInterface( 3569): Status for mount/Unmount :removed
E/MTPJNIInterface( 3569): SDcard is not available
E/SQLiteLog( 3569): (21) API call with NULL database connection pointer
E/SQLiteLog( 3569): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 3569): (21) API call with NULL database connection pointer
E/SQLiteLog( 3569): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 3569): (21) API call with NULL database connection pointer
E/SQLiteLog( 3569): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 3569): (21) API call with NULL database connection pointer
E/SQLiteLog( 3569): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 3569): notification from stack 2
,D/        ( 3569): [mtp_init_device] Library open with 32 bits.
D/        ( 3569): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 3569): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
,D/        ( 3569): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,E/        ( 3569):  [sua_support_present:1287] returning false 
D/        ( 3569): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,D/TimaKeyStoreProvider( 4340): TimaSignature is unavailable
,D/ActivityThread( 4340): Added TimaKeyStore provider

```
