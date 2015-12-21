#### Test 50650278d1b06e8_thali04_samsung-SM-N910C Logs


```
--------- beginning of main
V/Transcoder(11356): Transcoder(0xafa31560)::constructor
V/Transcoder(11356): addObitRecipient
V/TMI-JNI (11356): Mobile Transcoder JNI version 1.6.0/20131120/4.4
I/SA      (10827): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      (10827): [SUR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      (10827): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10520 extra.user_handle.:0 ]
I/RelayReceiver_PinBoard(10878): onReceive... android.intent.action.PACKAGE_ADDED
I/RelayService_PinBoard(10878): RelayService Started!! : android.intent.action.PACKAGE_ADDED
I/System.out(11400): Inside WakeupProvider
E/DatabaseUtils(11400): Writing exception to parcel
E/DatabaseUtils(11400): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(11400): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(11400): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(11400): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(11400): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(11400): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(11400): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(11400): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(11400): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(11400): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(11400): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(11377): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err(11377): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err(11377): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err(11377): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err(11377): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err(11377): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err(11377): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err(11377): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err(11377): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err(11377): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err(11377): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err(11377): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(11377): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err(11377): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err(11377): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err(11377): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err(11377): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err(11377): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err(11377): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:131)
W/System.err(11377): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:197)
W/System.err(11377): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(11377): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err(11377): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(11377): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(11377): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(11377): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(11377): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(11377): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(11377): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(11377): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(11377): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(11377): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/DatabaseUtils(11400): Writing exception to parcel
E/DatabaseUtils(11400): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(11400): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(11400): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(11400): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(11400): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(11400): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(11400): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(11400): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(11400): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(11400): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(11400): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(11377): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err(11377): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err(11377): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err(11377): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err(11377): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err(11377): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err(11377): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err(11377): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err(11377): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err(11377): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err(11377): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err(11377): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(11377): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err(11377): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err(11377): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err(11377): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err(11377): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:242)
W/System.err(11377): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(11377): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err(11377): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(11377): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(11377): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(11377): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(11377): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(11377): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(11377): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(11377): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(11377): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(11377): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode](11377): [DLApplication]-Init Called!:false
W/[CarMode](11377): [CommonUtil]-=========================================
W/[CarMode](11377): [CommonUtil]-CarMode Version:1.10.38.19768
W/[CarMode](11377): [CommonUtil]-=========================================
E/[CarMode](11377): [DLApplication]-Init Started!:true
I/[CarModeFW](11377): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW](11377): ### com.sec.android.app.automotive.carmode.framework.DriveLinkServiceInterfaceImp::initialize(132)
I/[CarModeFW](11377): ### com.sec.android.automotive.drivelink.DLApplication::init(211)
I/[CarModeFW](11377): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(135)
I/[CarModeFW](11377): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW](11377): ### android.app.ActivityThread::handleBindApplication(5115)
I/[CarModeFW](11377): ### android.app.ActivityThread::access$1600(178)
I/[CarModeFW](11377): ### android.app.ActivityThread$H::handleMessage(1510)
I/[CarModeFW](11377): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW](11377): ### android.os.Looper::loop(145)
I/[CarModeFW](11377): ### android.app.ActivityThread::main(5944)
I/[CarModeFW](11377): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW](11377): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW](11377): ### com.android.internal.os.ZygoteInit::main(1194)
I/VlingoApplication(11400): VlingoApplication appVersion ='11.7.0.1.39589', coreVersion = '2.5.2.15201', ro.csc.sales_code=XEO
I/MessageDataHandler(11377): initialize
D/[CarModeFW](11377): CDH-initiazlieCaches : before sync
D/[CarModeFW](11377): CDH-initiazlieCaches : after sync
D/[CarModeFW](11377): CDH-buildContactCacheWireFrame : cur len =0
I/VlingoAndroidCore(11400): AppName: SamsungTproject, Core: 2.5.2.15201, SDK: 2.0.1657, EDM:15201
D/[CarModeFW](11377): CDH-ContactDataHandler initiazlieCaches time : 12
D/[CarModeFW](11377): CDH-initiazlieCaches : end sync
D/[CarModeFW](11377): DrivingManager-initialize...
D/ResourcesManager( 8813): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SensorService( 3522): Skipped sensor HRMLED IR because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3522): Skipped sensor HRMLED RED because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3522): Skipped sensor MAX86902 because it requires permission 
I/SensorService( 3522): Skipped sensor HRM Sensor because it requires permission 
I/SensorService( 3522): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
D/VlingoApplication(11400): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication(11400): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/DialogFlow(11400): initQueue()
I/MediaPlayer(11377): Need to enable context aware info
V/MediaPlayer-JNI(11377): native_setup
V/MediaPlayer(11377): constructor
V/MediaPlayer(11377): setListener
D/[CarModeFW](11377): MY_TAG-[YANG] MusicButtonReceiver construct MusicButtonReceiver() 
I/[CarModeFW](11377): DriveLinkServiceInterfaceImp-drivelink framework initialize end
D/[CarMode](11377): [DLServiceManager]-getOnDLLocationSuggestionListener..........
D/[CarModeFW](11377): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => start time : 1450655577823
D/[CarMode](11377): [DLServiceManager]-updateLocationList
D/[CarModeFW](11377): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => start time : 1450655577824
D/[CarMode](11377): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW](11377): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1450655577823
D/[CarModeFW](11377): insertNavigationAvailable-sql: select distinct nav_package from tb_location_navigation_available
D/[CarModeFW](11377): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => start time : 1450655577824
D/[CarModeFW](11377): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => start time : 1450655577824
F/DLApplication(11377): DLApplication mListNavitationAvailable: [com.skt.skaf.l001mtm091, com.google.android.apps.maps, kt.navi, com.mnsoft.lgunavi, com.autonavi.xmgd.navigator.samsung, com.here.app.maps]
D/[CarModeFW](11377): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1450655577825
I/[CarMode](11377): [LogNotNull]-Package name is: com.here.app.maps
D/[CarModeFW](11377): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => start time : 1450655577825
E/[CarMode](11377): [DLApplication]-Init End!:true
D/TP/SmsProvider( 3977): query,matched:2, calling pid = 11377
D/TP/SmsProvider( 3977): match 2:Elapsed time : 0.920 ms
D/[CarMode](11377): [TAG]-phone sound mode is: 0
V/[CarMode](11377): [DLApplication]-savePreviousGpsState
D/TP/SmsProvider( 3977): query,matched:2, calling pid = 11377
V/[CarMode](11377): [DLApplication]-savePreviousGpsState: Previous state = 0
D/[CarModeFW](11377): ContactDataHandler-getFavoriteContactList : cur len = 0
D/TP/SmsProvider( 3977): match 2:Elapsed time : 0.807 ms
D/[CarModeFW](11377): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 10
D/[CarModeFW](11377): CalllogDataHandler-getCalllogList : cur len = 0
D/MessageDataHandler(11377):  getInboxList smsCursor : 11
D/[CarModeFW](11377): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => execute time : 14
D/[CarModeFW](11377): ContactDataHandler-getFavoriteContactList : cur len = 0
D/[CarModeFW](11377): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 13
D/TP/MmsProvider( 3977): Query uri=content://mms/inbox, match=2, calling pid = 11377
D/TP/MmsProvider( 3977): Query uri=content://mms, match=0, calling pid = 11377
D/[CarModeFW](11377): LocationDataHandler-No schedules found.
D/[CarMode](11377): [DLApplication]-GooglePlayServices SUCCESS.
E/[CarMode](11377): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
D/[CarModeFW](11377): ContactDataHandler-getFavoriteContactList : cur len = 0
D/[CarModeFW](11377): MyPlaceProvider-Provider uri: content://com.samsung.android.internal.intelligence.useranalysis/place
D/[CarModeFW](11377): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => execute time : 21
D/MessageDataHandler(11377):  getInboxList mmsCursor : 12
I/MessageDataHandler(11377): getUnreadMessageCount :0
D/[CarModeFW](11377): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => execute time : 23
--------- beginning of system
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (11445): MountEmulatedStorage()
E/Zygote  (11445): v2
I/libpersona(11445): KNOX_SDCARD checking this for 10003
I/libpersona(11445): KNOX_SDCARD not a persona
I/SELinux (11445): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=11445 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
I/SELinux (11445): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11445): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/[CarMode](11377): [[DLUncaughtExceptionHandler]]-setDLUncaughtExceptionHandler
E/[CarMode](11377): [[DLUncaughtExceptionHandler]]-DLUncaughtExceptionHandler is created!
D/MessageDataHandler(11377):  getInboxList mms,sms cursor join : 15
D/TP/MmsSmsProvider( 3977): query,matched:0, calling pid = 11377
V/TP/MmsSmsProvider( 3977): getSimpleConversations entered.
I/UpdateManagerReceiver(11377): Intent : android.intent.action.PACKAGE_ADDEDMon Dec 21 00:52:57 GMT+01:00 2015
D/TP/MmsSmsProvider( 3977): match 0:Elapsed time : 1.593 ms
D/DialogFlow(11377): initQueue()
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(11445): TimaSignature is unavailable
D/ActivityThread(11445): Added TimaKeyStore provider
E/Zygote  (11462): MountEmulatedStorage()
E/Zygote  (11462): v2
I/libpersona(11462): KNOX_SDCARD checking this for 1000
I/libpersona(11462): KNOX_SDCARD not a persona
I/SELinux (11462): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11462): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11462): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=11462 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3522): Killing 10792:com.sec.android.soagent/u0a38 (adj 15): bgCount ##31
E/lowmemorykiller( 2827): Error writing /proc/10792/oom_score_adj; errno=22
I/ActivityManager( 3522): Killing 10773:com.sec.android.app.taskmanager/u0a191 (adj 15): bgCount ##32
I/ActivityManager( 3522): Killing 10809:com.samsung.android.scloud.sync/u0a69 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(11462): TimaSignature is unavailable
D/ActivityThread(11462): Added TimaKeyStore provider
D/TP/MmsSmsProvider( 3977): query,matched:13, calling pid = 11377
W/GAV2    (11134): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 3522): Killing 10844:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
I/art     ( 3522): Explicit concurrent mark sweep GC freed 234584(15MB) AllocSpace objects, 3(4MB) LOS objects, 24% free, 49MB/65MB, paused 1.247ms total 96.064ms
D/TP/MmsSmsProvider( 3977): match 13:Elapsed time : 96.764 ms
D/MessageDataHandler(11377):  getInboxList address cursor : 101
D/ResourcesManager(11462): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
D/ResourcesManager(11445): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
D/TP/MmsSmsProvider( 3977): query,matched:0, calling pid = 11377
V/TP/MmsSmsProvider( 3977): getSimpleConversations entered.
D/TP/MmsSmsProvider( 3977): match 0:Elapsed time : 1.398 ms
D/MessageDataHandler(11377):  getInboxList thread cursor : 9
D/MessageDataHandler(11377):  thread, addr result: 6
I/[CarModeFW](11377): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxList() : 190
I/[CarModeFW](11377): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW](11377): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => execute time : 191
W/ContextImpl(11462): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
D/UserAnalysis.PlaceProvider(11445): PlaceProvider onCreate()
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11462): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
E/Zygote  (11481): MountEmulatedStorage()
I/libpersona(11481): KNOX_SDCARD checking this for 10121
E/Zygote  (11481): v2
I/libpersona(11481): KNOX_SDCARD not a persona
I/SELinux (11481): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/AndroidRuntime(11460): 
D/AndroidRuntime(11460): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
E/FilterInstaller(11462): installFilters
D/UserAnalysis.SecureDbManager(11445): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper(11445): SecurePlaceDbHelper() 
I/ActivityManager( 3522): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=11481 uid=10121 gids={50121, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux (11481): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/UserAnalysis.PlaceProvider(11445): Create SecureDbHelper
E/SELinux (11481): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11460): CheckJNI is OFF
E/FilterInstaller(11462): There is no requred permission
D/AndroidRuntime(11460): readGMSProperty: start
D/AndroidRuntime(11460): readGMSProperty: already setted!!
D/AndroidRuntime(11460): readGMSProperty: end
D/AndroidRuntime(11460): addProductProperty: start
D/IntelligenceServiceApplication(11445): onCreate()
I/ActivityManager( 3522): Killing 10860:com.sec.android.app.clockpackage/u0a94 (adj 15): bgCount ##31
D/TimaKeyStoreProvider(11481): TimaSignature is unavailable
D/ActivityThread(11481): Added TimaKeyStore provider
D/ResourcesManager(11481): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
D/[CarModeFW](11377): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW](11377): MyPlaceProvider-=============
D/[CarModeFW](11377): MyPlaceProvider-=============
D/[CarModeFW](11377): MyPlaceProvider-=============
D/[CarModeFW](11377): MyPlaceProvider-=============
D/[CarModeFW](11377): MyPlaceProvider-=============
D/[CarModeFW](11377): MyPlaceProvider-=============
D/[CarModeFW](11377): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW](11377): MyPlaceProvider-==============
D/[CarModeFW](11377): MyPlaceProvider-==============
D/[CarModeFW](11377): MyPlaceProvider-==============
D/[CarModeFW](11377): MyPlaceProvider-==============
D/[CarModeFW](11377): MyPlaceProvider-==============
D/PackageIntentReceiver(11481): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver(11481): Not GearManger package! 
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (11503): MountEmulatedStorage()
I/libpersona(11503): KNOX_SDCARD checking this for 1000
E/Zygote  (11503): v2
I/libpersona(11503): KNOX_SDCARD not a persona
I/SELinux (11503): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11503): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11503): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=11503 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3522): Killing 10893:com.wsomacp/u0a28 (adj 15): bgCount ##31
D/[CarModeFW](11377): DestinationAvailableTableHandler-sql: select dest_name from tb_destination_list_available where ((1450655578094 - dest_date ) / 360000 ) <= 24 ORDER BY dest_date DESC LIMIT 100
E/[CarModeFW](11377): DestinationAvailableTableHandler-insert FAIL!
E/DestinationList(11377): loadLocationDestinationList is null
D/[CarModeFW](11377): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => execute time : 271
D/TimaKeyStoreProvider(11503): TimaSignature is unavailable
D/ActivityThread(11503): Added TimaKeyStore provider
D/ResourcesManager(11503): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
I/System.out(11400): INFO:Resource not found:/Common.properties Using default values
E/AffinityControl(11460): AffinityControl: registerfunction enter
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (11520): MountEmulatedStorage()
I/libpersona(11520): KNOX_SDCARD checking this for 1000
E/Zygote  (11520): v2
I/libpersona(11520): KNOX_SDCARD not a persona
I/SELinux (11520): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/AndroidRuntime(11460): Calling main entry com.android.commands.am.Am
I/SELinux (11520): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11520): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=11520 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3522): Killing 10908:com.sec.esdk.elm/u0a106 (adj 15): bgCount ##31
E/PersonaManagerService( 3522): inState():  stateMachine is null !!
I/PersonaManagerService( 3522): PersonaId don't exist
I/ActivityManager( 3522): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3522): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3522): mDVFSHelper.acquire()
D/TimaKeyStoreProvider(11520): TimaSignature is unavailable
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ActivityThread(11520): Added TimaKeyStore provider
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (11538): MountEmulatedStorage()
I/libpersona(11538): KNOX_SDCARD checking this for 10520
E/Zygote  (11538): v2
I/libpersona(11538): KNOX_SDCARD not a persona
I/SELinux (11538): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11538): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11538): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11538 uid=10520 gids={50520, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime(11460): Shutting down VM
D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11538): TimaSignature is unavailable
D/ActivityThread(11538): Added TimaKeyStore provider
D/ResourcesManager(11520): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
D/ResourcesManager(11538): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2848): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2848): id=11 Removed YUIInstallC (-2/8)
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/AcmsPackageEventListener(11520): Received: android.intent.action.PACKAGE_ADDED
V/ActivityThread( 6271): updateVisibility : ActivityRecord{3c85437b token=android.os.BinderProxy@2dfa192c {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
W/ContextImpl(11520): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
E/Zygote  (11555): MountEmulatedStorage()
I/libpersona(11555): KNOX_SDCARD checking this for 10147
E/Zygote  (11555): v2
I/libpersona(11555): KNOX_SDCARD not a persona
I/SELinux (11555): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=11555 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11555): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Killing 9568:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 15): bgCount ##31
E/SELinux (11555): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/AcmsService(11520): Enter Oncreate
D/AcmsServiceMonitor(11520): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService(11520): creating AcmsCore
D/AcmsCore(11520): AcmsCore.getAcmsCore() - Enter
D/AcmsCore(11520): AcmsCore
I/art     ( 2881): Explicit concurrent mark sweep GC freed 8798(374KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 628us total 11.288ms
D/AcmsCore(11520): init
D/AcmsCore(11520): Looper handler is not null
D/AcmsCore(11520): Post to AcmsCoreHandler
D/TimaKeyStoreProvider(11555): TimaSignature is unavailable
D/ActivityThread(11555): Added TimaKeyStore provider
D/AcmsServiceMonitor(11520): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(11520): Incrementing - Counter value: 1
D/AcmsCore(11520): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService(11520): onStartCommand
D/AcmsService(11520): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor(11520): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor(11520): Incrementing - Counter value: 2
D/AcmsService(11520): Incremented Counter Value : onStartCommand
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 376us total 9.568ms
D/AcmsCertificateMngr(11520): AcmsCertificateMngr
D/ActivityThread(11520): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/AcmsRevocationMngr(11520): AcmsRevocationMngr
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 794us total 10.680ms
I/Icing   ( 6755): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
D/ResourcesManager(11555): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
W/ResourcesManager(11555): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/AcmsService(11520): Inside handle Intent
D/AcmsService(11520): App added - package name: com.test.thalitest
D/AcmsCore(11520): Post to AcmsCoreHandler
D/AcmsServiceMonitor(11520): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(11520): Incrementing - Counter value: 3
D/AcmsCore(11520): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService(11520): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor(11520): Decrementing - Counter value: 2
I/WebViewFactory(11538): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11538): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11538): Loading: webviewchromium
I/LibraryLoader(11538): Time to load native libraries: 3 ms (timestamps 7953-7956)
I/LibraryLoader(11538): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(11538): Binding Chromium to main looper Looper (main, tid 1) {3025f71a}
I/LibraryLoader(11538): Expected native library version number "",actual native library version number ""
I/chromium(11538): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/ResourcesManager( 6755): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/BrowserStartupController(11538): Initializing chromium process, renderers=0
W/art     (11538): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(11538): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(11538): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11538): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
I/Icing   ( 6755): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
,W/chromium(11538): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(11538): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     (11538): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents(11538): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(11538): CordovaWebView is running on device made by: samsung
W/art     (11538): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11538): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity(11538): performCreate Call secproduct feature valuefalse
D/Activity(11538): performCreate Call debug elastic valuetrue
D/OpenGLRenderer(11538): Render dirty regions requested: true
D/ActivityManager( 3522): post active user change for 0
D/KnoxTimeoutHandler( 3522): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3522): handleActiveUserChange for user 0
V/GLSActivity( 4638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 4638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SurfaceFlinger( 2848): id=14 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11538): Initialized EGL, version 1.4
I/OpenGLRenderer(11538): HWUI protection enabled for context ,  &this =0xb3b71a10 ,&mEglDisplay = 1 , &mEglConfig = -1279758064 
D/OpenGLRenderer(11538): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11538): Enabling debug mode 0
D/mali_winsys(11538): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(11538): updateVisibility : ActivityRecord{3fa5aca token=android.os.BinderProxy@10968e09 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/InputMethodManagerService( 3522): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (11637): MountEmulatedStorage()
E/Zygote  (11637): v2
I/libpersona(11637): KNOX_SDCARD checking this for 10160
I/libpersona(11637): KNOX_SDCARD not a persona
I/SELinux (11637): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11637): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11637): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=11637 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
I/Icing   ( 6755): Indexing 5F814D61A0DCF2E8041D271E5054F7C0773240D3 from com.google.android.googlequicksearchbox
D/TimaKeyStoreProvider(11637): TimaSignature is unavailable
D/ActivityThread(11637): Added TimaKeyStore provider
D/ResourcesManager(11637): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/ResourcesManager(11637): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(11637): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11637): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/IInputConnectionWrapper(11538): showStatusIcon on inactive InputConnection
W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/Timeline(11538): Timeline: Activity_idle id: android.os.BinderProxy@10968e09 time:118210
I/Icing   ( 6755): Indexing done 5F814D61A0DCF2E8041D271E5054F7C0773240D3
W/ActivityManager( 3522): mDVFSHelper.release()
I/Timeline( 3522): Timeline: Activity_windows_visible id: ActivityRecord{164516fb u0 com.test.thalitest/.MainActivity t26} time:118230
V/Common  (11637): getScreenSize 1440 2560
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (11667): MountEmulatedStorage()
E/Zygote  (11667): v2
I/libpersona(11667): KNOX_SDCARD checking this for 10160
I/libpersona(11667): KNOX_SDCARD not a persona
I/SELinux (11667): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/JAM     (11637): Load The ApaService JNI
I/JAM     (11637): version: ProfessionalAudio_v1.0.b5
I/JAM     (11637): Try v1.0.b3 ...
D/Spen    (11637): SpenSdk version level = 55
D/Spen    (11637): SpenSdk jar version = 3.0.243
I/SELinux (11667): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=11667 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
E/SELinux (11667): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Spen    (11637): SpenSdk apk version = 3.0.235
D/Spen    (11637): Server UPDATE Check
W/linker  (11637): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
D/SPenError(11637): JNI_OnLoad
D/JNI_Bitmap(11637): Init .. Done
D/SPenSpiDecoder(11637): JNI_OnLoad .. Done
D/SPenError(11637): JNI_OnLoad Success
D/PluginManager(11637): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
D/PluginManager(11637): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
D/Init_SPenSdk_Jni(11637): JNI_OnLoad
D/Init_SPenSdk_Jni(11637): AndroidSDK: 21
D/Init_SPenSdk_Jni(11637): JNI_OnLoad .. Done
D/Model_ObjectBase_Jni(11637): JNI_OnLoad .. Done
D/Model_ObjectStroke_Jni(11637): JNI_OnLoad .. Done
D/Model_ObjectImage_Jni(11637): JNI_OnLoad .. Done
D/Model_ObjectText_Jni(11637): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni(11637): JNI_OnLoad .. Done
D/Model_PageDoc_Jni(11637): JNI_OnLoad .. Done
D/Model_NoteDoc_Jni(11637): check build type eng[0]
D/Model_NoteDoc_Jni(11637): JNI_OnLoad .. Done
D/Model_NoteFile_Jni(11637): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni(11637): JNI_OnLoad .. Done
D/Model   (11637): OnLoad class Done
D/spe_log (11637): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
D/SPen_Library(11637): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(11637): Canvas JNI_OnLoad enter!!
D/SPen_Library(11637): Canvas JNI_OnLoad Success
D/SPen_Library(11637): TextView JNI_OnLoad enter!!
D/SPen_Library(11637): TextView JNI_OnLoad Success
D/SPen_Library(11637): Text JNI_OnLoad enter!!
D/SPen_Library(11637): Text JNI_OnLoad Success
D/SPen_Library(11637): FontManager JNI_OnLoad enter!!
D/SPen_Library(11637): FontManager JNI_OnLoad Success
D/SPen_Library(11637): CapturePage JNI_OnLoad enter!!
D/SPen_Library(11637): CapturePage JNI_OnLoad Success
D/SPen_Library(11637): Multi JNI_OnLoad enter!!
D/SPen_Library(11637): Multi JNI_OnLoad Success
D/SPen_Library(11637): Draw Engine JNI_OnLoad Success
D/SPen_Library(11637): Brush JNI_OnLoad enter!!
D/SPen_Library(11637): Brush JNI_OnLoad Success
D/SPen_Library(11637): ChineseBrush JNI_OnLoad enter!!
D/SPen_Library(11637): ChineseBrush JNI_OnLoad Success
D/SPen_Library(11637): InkPen JNI_OnLoad enter!!
D/SPen_Library(11637): InkPen JNI_OnLoad Success
D/SPen_Library(11637): Marker JNI_OnLoad enter!!
D/SPen_Library(11637): Marker JNI_OnLoad Success
D/JsMessageQueue(11538): Set native->JS mode to OnlineEventsBridgeMode
D/TimaKeyStoreProvider(11667): TimaSignature is unavailable
D/SPen_Library(11637): Pencil JNI_OnLoad enter!!
D/ActivityThread(11667): Added TimaKeyStore provider
D/SPen_Library(11637): Pencil JNI_OnLoad Success
D/SPen_Library(11637): NativePen JNI_OnLoad enter!!
D/SPen_Library(11637): NativePen JNI_OnLoad Success
D/SPen_Library(11637): MontblancFountainPen JNI_OnLoad enter!!
D/SPen_Library(11637): MontblancFountainPen JNI_OnLoad Success
D/SPen_Library(11637): MontblancCalligraphyPen JNI_OnLoad enter!!
D/SPen_Library(11637): MontblancCalligraphyPen JNI_OnLoad Success
D/SPen_Library(11637): MagicPen JNI_OnLoad enter!!
D/SPen_Library(11637): MagicPen JNI_OnLoad Success
D/SPen_Library(11637): ObliquePen JNI_OnLoad enter!!
D/SPen_Library(11637): ObliquePen JNI_OnLoad Success
D/SPen_Library(11637): FountainPen JNI_OnLoad enter!!
D/SPen_Library(11637): FountainPen JNI_OnLoad Success
D/Spen    (11637): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(11637): SPenSdk_init2
D/Init_SPenSdk(11637): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
D/Init_SPenSdk(11637): Total S Pen SDK Directory Size = 0
D/Spen    (11637): initialize complete
W/linker  (11637): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
D/ResourcesManager(11667): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/ResourcesManager(11667): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(11667): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11667): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/ResourcesManager(11637): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
I/chromium(11538): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11538): 
E/Zygote  (11687): MountEmulatedStorage()
I/libpersona(11687): KNOX_SDCARD checking this for 10183
E/Zygote  (11687): v2
I/libpersona(11687): KNOX_SDCARD not a persona
I/SELinux (11687): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11687): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=11687 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
E/SELinux (11687): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Killing 11101:com.samsung.android.app.vrsetupwizardstub/u0a63 (adj 15): bgCount ##31
D/SNoteProvider(11667): onCreate enableSnoteSync = true
D/SNoteProvider(11667): ===query=== 
D/TimaKeyStoreProvider(11687): TimaSignature is unavailable
D/ActivityThread(11687): Added TimaKeyStore provider
V/Common  (11667): getScreenSize 1440 2560
D/jxcore_app_log(11538): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1361619840
D/JX-Cordova(11538): jxcore cordova android initializing
D/ResourcesManager(11687): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
D/SNoteProvider(11667): ===query=== 
E/SQLiteLog(11687): (284) automatic index on shooting_modes(title_id)
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (11706): MountEmulatedStorage()
I/libpersona(11706): KNOX_SDCARD checking this for 10190
E/Zygote  (11706): v2
I/libpersona(11706): KNOX_SDCARD not a persona
I/SELinux (11706): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11706): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11706): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=11706 uid=10190 gids={50190, 9997} abi=armeabi-v7a
I/ActivityManager( 3522): Killing 11144:com.facebook.system/u0a10 (adj 15): bgCount ##31
D/TimaKeyStoreProvider(11706): TimaSignature is unavailable
D/ActivityThread(11706): Added TimaKeyStore provider
D/ResourcesManager(11706): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
I/TapandpayWidget:TanpandpayAppWidgetProvider(11706): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(11706): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
I/TapandpayWidget:Utils(11706): Clear T&P info.
D/TapandpayWidget:TanpandpayAppWidgetProvider(11706): Widget is not attached.
I/splitIntent( 3522): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/ActivityManager( 3522): Killing 10141:com.sec.android.gallery3d/u0a50 (adj 15): bgCount ##31
D/BootupListener( 3977): ACTION_DRIVELINK
D/SettingsProvider( 3522): name = drivelink_navigation
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1001
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
D/BootupListener( 3977): NAVI : com.here.app.maps
D/SettingsProvider( 3522): name = internet_call_settings_visibility
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1001
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
D/BootupListener( 3977): intent.getAction() = com.sec.android.automotive.drivelink.NAVIGATION_PACKAGE_NAME
D/Widget  (11637): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
D/Widget  (11637): onReceive android.appwidget.action.APPWIDGET_UPDATE
D/Widget  (11637): widgetUpdate 5
D/RCPManagerService( 3522): exchangeData() failure , invalid userId
D/AcmsKeyStoreHelper(11520):  getKeyStoreForApplication Enter
I/AcmsKeyStoreHelper(11520): Key Store exist
I/AcmsKeyStoreHelper(11520): Hence loading the keystore file
D/AcmsKeyStoreHelper(11520):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr(11520): getKeyStoreForApplication success 
D/AcmsCore(11520): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor(11520): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(11520): Decrementing - Counter value: 1
D/AcmsCore(11520): AcmsCore: ACMS_APP_INSTALLED
D/AcmsCore(11520): This is NOT a valid MirrorLink app
D/AcmsCore(11520): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor(11520): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(11520): Decrementing - Counter value: 0
D/AcmsServiceMonitor(11520): Counter value is 0: Stopping ACMS service
D/AcmsServiceMonitor(11520): getSvcCounter - Counter value: 0
D/AcmsService(11520): Enter onDestroy
I/AcmsService(11520): cleanUp(): inside service clean up
D/AcmsCore(11520): AcmsCore: inside DeInit
D/AcmsCore(11520): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr(11520): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr(11520): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper(11520): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface(11520): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor(11520): getSvcCounter - Counter value: 0
D/AcmsService(11520): killing acms process
I/Process (11520): Sending signal. PID: 11520 SIG: 9
I/ActivityManager( 3522): Process ACMS.Process (pid 11520)(adj 0) has died(81,1220)
,W/jxcore-log(11538): Initializing JXcore engine
W/jxcore-log(11538): JXcore engine is ready
,W/jxcore-log(11538): Starting JXcore engine
,E/auditd  ( 4615): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3522): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3522): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11538): Platform android
W/jxcore-log(11538): 
W/jxcore-log(11538): Process ARCH arm
W/jxcore-log(11538): 
,I/jxcore-log(11538): JXcore Cordova bridge is ready!
I/jxcore-log(11538): 
W/jxcore-log(11538): JXcore engine is started
,V/AlarmManager( 3522): waitForAlarm result :8
,I/jxcore-log(11538): Toggling radios to true
I/jxcore-log(11538): 
,D/BluetoothAdapter(11538): enable()
,D/BluetoothAdapter(11538): enable(): BT is already enabled..!
,D/WifiService( 3522): New client listening to asynchronous messages
,I/WifiManager(11538): packageName : com.test.thalitest
,D/SecContentProvider( 3522): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3522): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3522): mCursor = null
,D/WifiService( 3522): setWifiEnabled: true pid=11538, uid=10520
E/WifiService( 3522): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3522): Permission Denial: getCurrentUser() from pid=11538, uid=10520 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3522): Failed getting userId using ActivityManagerNative
W/WifiService( 3522): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11538, uid=10520 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3522): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3522): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3522): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3522): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3522): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3522): name = wifi_on
,I/WifiService( 3522): disconnect: pid=11538, uid=10520
,I/wpa_supplicant( 3827): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11538): Radios toggled
I/jxcore-log(11538): 
,I/wpa_supplicant( 3827): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3827): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3827): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3827): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3522): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3827): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3827): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3827): Disconnected - do not scan
I/wpa_supplicant( 3827): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/jxcore-log(11538): Got Device Bluetooth address: E0:DB:10:14:E2:C0
I/jxcore-log(11538): 
E/WifiStateMachine( 3522): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3522): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3522): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3522): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log(11538): Perf Test app loaded loaded
I/jxcore-log(11538): 
,I/jxcore-log(11538): check test folder
I/jxcore-log(11538): 
,I/jxcore-log(11538): found test : ./testFindPeers.js
I/jxcore-log(11538): 
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3522): do suspend true
,D/WifiP2pService( 3522): InactiveState{ what=143375 }
,D/WifiP2pService( 3522): P2pEnabledState{ what=143375 }
,D/CommandListener( 2844): Clearing all IP addresses on wlan0
,E/Netd    ( 2844): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/ConnectivityService( 3522): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine( 3522): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService( 3522): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
I/jxcore-log(11538): found test : ./testSendData.js
I/jxcore-log(11538): 
E/ConnectivityService( 3522): updateNetworkInfo()
E/ConnectivityService( 3522): updateNetworkInfo()
E/WifiConfigStore( 3522): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,E/WifiStateMachine( 3522): Start Disconnecting Watchdog 1
I/Hs20UtilService( 4113): Starting #8
,I/wpa_supplicant( 3827): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3827): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3827): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3827): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3827): First Scan Start
I/Hs20UtilService( 4113): Message received 5007
,I/wpa_supplicant( 3827): Scan requested (ret=0) - scan timeout 30 seconds
D/NearbySettings(11225): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings(11225): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings(11225): MountReceiver.onReceive - Create mPrefHandler
E/WifiStateMachine( 3522): ConnectModeState: Network connection lost 
E/WifiStateMachine( 3522): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3522): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3522): do suspend true
,D/NearbySettings(11225): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings(11225): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(11225): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiP2pService( 3522): InactiveState{ what=143375 }
D/WifiP2pService( 3522): P2pEnabledState{ what=143375 }
,I/jxcore-log(11538): found test : ./testSendData2.js
I/jxcore-log(11538): 
,D/WifiService( 3522): New client listening to asynchronous messages
,I/NearbySettings(11225): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings(11225): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11225): MountReceiver.onReceive - Set preference state off
,E/jxcore  (11538): Error!: unlabeled break must be inside loop or switch
E/jxcore  (11538): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
I/Choreographer(11538): Skipped 46 frames!  The application may be doing too much work on its main thread.
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,V/NearbySettings(11225): MountReceiver.mPrefHandler - 7002
,I/chromium(11538): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/CommandListener( 2844): Clearing all IP addresses on wlan0
I/SignOutReceiver(11637): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 3522): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/EntConnectivity( 3522): Not allowed due to - mEnabled false
E/WifiStateMachine( 3522): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524292
D/WifiStateMachine( 3522): updateConfiguredNetworkExpiration - currTime: 1450655580473
D/WifiStateMachine( 3522): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine( 3522): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3522): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3522): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/chromium(11538): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/WifiStateMachine( 3522): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3522): NetworkAgent: NetworkAgent channel lost
I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling
D/TelephonyNetworkFactory( 3977): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 3522): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3522): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine( 3522): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3522): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,D/ConnectivityManager.CallbackHandler( 6755): CM callback handler got msg 524292
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,D/EntConnectivity( 3522): Not allowed due to - mEnabled false
,D/ConnectivityService( 3522): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
I/Hs20UtilService( 4113): Starting #9
,I/Hs20UtilService( 4113): Message received 5007
,D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering( 3522): MasterInitialState.processMessage what=3
D/SmartBondingService( 3522): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
V/NetworkStats( 3522): updateIfacesLocked()
V/NetworkStats( 3522): performPollLocked(flags=0x1)
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
D/NetworkStatsFactory( 3522): UpdateStatsForKnox
,V/NetworkStats( 3522): performPollLocked() took 3ms
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
V/NetworkStats( 3522): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/SmartBondingService( 3522): getNetworkEnabled : wifi : true mobile : false
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,D/NearbySettings(11225): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings(11225): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(11225): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings(11225): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings(11225): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11225): MountReceiver.onReceive - Set preference state off
V/NearbySettings(11225): MountReceiver.mPrefHandler - 7002
I/SignOutReceiver(11637): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3522): updateDataUsageMap
,I/ApplicationPolicy( 3522): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3522): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3522): getSBEnabled() enabled =false
,D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
,D/SmartBondingService( 3522): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3522): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/SLocation( 3522): No Active Data Connection
,I/DBG_DM  ( 6271): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6271): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/PCWCLIENTTRACE_PushUtil(11207): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11207): sales region : global
I/PCWCLIENTTRACE_PushUtil(11207): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11207): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11207): noConnectivity : true
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11763): MountEmulatedStorage()
E/Zygote  (11763): v2
I/libpersona(11763): KNOX_SDCARD checking this for 10135
I/libpersona(11763): KNOX_SDCARD not a persona
,I/SELinux (11763): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11763): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11763 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (11763): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11763): TimaSignature is unavailable
,D/ActivityThread(11763): Added TimaKeyStore provider
,D/ResourcesManager(11763): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(11763): Database version: 104
,D/ResourcesManager(11763): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11763): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11763): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11763): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11763): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11763): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a3ad2ce: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11763): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11763): GMSCore installation verified
,I/ConfigStore(11763): Config Database version: 1
,I/wpa_supplicant( 3827): nl80211: Received scan results (12 BSSes)
,I/wpa_supplicant( 3827): wlan0: Setting scan request: 8 sec 0 usec
E/WifiStateMachine( 3522): [1,450,655,581,541 ms] noteScanEnd no scan source
I/wpa_supplicant( 3827): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3827): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3827): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3522): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@29c60aef sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3522): setDetailed state send new extra info
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11763): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11763): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11763): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/wpa_supplicant( 3827): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 3827): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3827): Associated with C0.AA.48
,E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine( 3522): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3522): getStreamVolume 3 index 0
,I/MediaRouter(11763): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/wpa_supplicant( 3827): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3827): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
I/wpa_supplicant( 3827): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3827): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3827): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 3827): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3827): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3827): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3827): Blacklist: Clear (temp) 
,I/wpa_supplicant( 3827): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3522): Network connection established
,D/WifiNative-HAL( 3522): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3522): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3522): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3522): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 3522): hsengiv:checkWhatTypeOfNetwork and the value is false
E/WifiStateMachine( 3522): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService( 3522): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine( 3522): L2ConnectedState "NG700" nid=0
E/ConnectivityService( 3522): updateNetworkInfo()
,E/WifiConfigStore( 3522): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3522): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine( 3522): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3522): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3522): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/CommandListener( 2844): Setting iface cfg
,E/WifiStateMachine( 3522): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,E/Zygote  (11802): MountEmulatedStorage()
E/Zygote  (11802): v2
I/libpersona(11802): KNOX_SDCARD checking this for 10002
I/libpersona(11802): KNOX_SDCARD not a persona
,I/SELinux (11802): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11802): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11802 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (11802): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/WifiStateMachine( 3522): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/NetworkMonitor(11763): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider(11802): TimaSignature is unavailable
I/ActivityManager( 3522): Killing 11119:com.google.android.partnersetup/u0a17 (adj 15): bgCount ##31
,D/ActivityThread(11802): Added TimaKeyStore provider
,D/ResourcesManager(11802): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3522): Killing 10720:com.android.mms/u0a52 (adj 15): bgCount ##31
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3522): do suspend false
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
D/WifiP2pService( 3522): InactiveState{ what=143375 }
,D/WifiP2pService( 3522): P2pEnabledState{ what=143375 }
,E/Zygote  (11821): MountEmulatedStorage()
E/Zygote  (11821): v2
I/libpersona(11821): KNOX_SDCARD checking this for 1000
I/libpersona(11821): KNOX_SDCARD not a persona
,I/SELinux (11821): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11821 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (11821): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11821): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CountryDetector( 3522): No listener is left
,D/TimaKeyStoreProvider(11821): TimaSignature is unavailable
,D/ActivityThread(11821): Added TimaKeyStore provider
,D/ResourcesManager(11821): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11821): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(11821): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11821): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11821): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11821): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/dhcpcd  (11837): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11837): version 5.5.6 starting
,E/dhcpcd  (11837): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (11844): MountEmulatedStorage()
E/Zygote  (11844): v2
I/libpersona(11844): KNOX_SDCARD checking this for 10012
I/libpersona(11844): KNOX_SDCARD not a persona
I/dhcpcd  (11837): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11837): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (11837): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (11837): bssid match
I/dhcpcd  (11837): wlan0: rebinding lease of 192.168.1.124
I/ActivityManager( 3522): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11844 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (11844): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11844): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11844): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider(11844): TimaSignature is unavailable
D/ActivityThread(11844): Added TimaKeyStore provider
W/ProcessCpuTracker( 3522): Skipping unknown process pid 11838
W/ProcessCpuTracker( 3522): Skipping unknown process pid 11839
D/ResourcesManager(11844): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
I/ActivityManager( 3522): Killing 11171:com.sec.android.service.health/u0a19 (adj 15): bgCount ##31
E/lowmemorykiller( 2827): Error writing /proc/11171/oom_score_adj; errno=22
I/FOTA_Client(11844): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
I/FOTA_Client(11844): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
I/FOTA_Client(11844): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (11860): MountEmulatedStorage()
E/Zygote  (11860): v2
I/libpersona(11860): KNOX_SDCARD checking this for 10021
I/libpersona(11860): KNOX_SDCARD not a persona
I/SELinux (11860): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11860): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11860 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
E/SELinux (11860): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Killing 11188:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
E/lowmemorykiller( 2827): Error writing /proc/11188/oom_score_adj; errno=22
D/TimaKeyStoreProvider(11860): TimaSignature is unavailable
D/ActivityThread(11860): Added TimaKeyStore provider
D/ResourcesManager(11860): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
I/KLMS-2.4.521: (11860): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Dec 21 00:53:02 GMT+01:00 2015
I/KLMS-2.4.521: (11860): KLMSAbstractReciever(): onReceive().END.
I/KLMS-2.4.521: (11860): KLMSIntentService(): onCreate()
I/KLMS-2.4.521: (11860): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.521: (11860): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (11860): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.4.521: (11860): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
I/KLMS-2.4.521: (11860): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
I/KLMS-2.4.521: (11860): StateImplV2(): networkChangeListener().END
E/Zygote  (11876): MountEmulatedStorage()
E/Zygote  (11876): v2
I/libpersona(11876): KNOX_SDCARD checking this for 10038
I/libpersona(11876): KNOX_SDCARD not a persona
I/SELinux (11876): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11876 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/SELinux (11876): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11876): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.4.521: (11860): KLMSIntentService(): onDestroy()
I/ActivityManager( 3522): Killing 11242:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): bgCount ##31
D/TimaKeyStoreProvider(11876): TimaSignature is unavailable
D/ActivityThread(11876): Added TimaKeyStore provider
D/ResourcesManager(11876): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
I/SO_AGENT(11876): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
E/SPPClientService(11316): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
I/SA      (10827): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      (10827): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (10827): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (10827): [SLFUCHKMGR] constructor called
E/SPPClientService(11316): [[SystemStateMonitorService]] No Active Internet
I/SA      (10827): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (10827): [OR] == isSIMCardReady false ==
I/SA      (10827): [SCU] == networkStateCheck == false
I/SA      (10827): [OR] onReceive END
V/DownloadManager( 5506): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (11894): MountEmulatedStorage()
E/Zygote  (11894): v2
I/libpersona(11894): KNOX_SDCARD checking this for 10067
I/libpersona(11894): KNOX_SDCARD not a persona
I/SELinux (11894): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11894): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11894): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=11894 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 3522): Killing 10282:com.android.vending/u0a31 (adj 15): bgCount ##31
I/art     ( 2881): Explicit concurrent mark sweep GC freed 8713(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 910us total 22.481ms
D/TimaKeyStoreProvider(11894): TimaSignature is unavailable
D/ActivityThread(11894): Added TimaKeyStore provider
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 789us total 18.501ms
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.084ms total 17.818ms
I/art     ( 3522): Explicit concurrent mark sweep GC freed 54361(2MB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 49MB/65MB, paused 1.890ms total 147.918ms
I/GAV2    (11134): Thread[GAThread,5,main]: No campaign data found.
I/ActivityManager( 3522): Killing 9723:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
D/ResourcesManager(11894): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
I/sCloudBackupApp(11894): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(11894): Other Intent
I/ActivityManager( 3522): Killing 11263:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
D/accuweather( 5208): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
D/accuweather( 5208): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5208): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5208): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5208): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 5208): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 5208): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (11915): MountEmulatedStorage()
I/libpersona(11915): KNOX_SDCARD checking this for 1000
E/Zygote  (11915): v2
I/libpersona(11915): KNOX_SDCARD not a persona
I/SELinux (11915): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11915): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=11915 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11915): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11915): TimaSignature is unavailable
,D/ActivityThread(11915): Added TimaKeyStore provider
,D/ResourcesManager(11915): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(11915): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(11915): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(11915): premStatus:2
,I/KnoxUsageLogPro(11915): isEulaShown : false
I/KnoxUsageLogPro(11915): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11930): MountEmulatedStorage()
E/Zygote  (11930): v2
I/libpersona(11930): KNOX_SDCARD checking this for 10090
I/libpersona(11930): KNOX_SDCARD not a persona
,I/SELinux (11930): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11930): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11930): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=11930 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3522): Killing 11288:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11930): TimaSignature is unavailable
,D/ActivityThread(11930): Added TimaKeyStore provider
,D/ResourcesManager(11930): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11946): MountEmulatedStorage()
I/libpersona(11946): KNOX_SDCARD checking this for 10127
E/Zygote  (11946): v2
I/libpersona(11946): KNOX_SDCARD not a persona
,I/SELinux (11946): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11946): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=11946 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11946): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Killing 11333:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11946): TimaSignature is unavailable
,D/ActivityThread(11946): Added TimaKeyStore provider
,D/ResourcesManager(11946): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(11946): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(11946): cancelUpdateCategory
D/KeyguardWallpaperUpdator(11946): stopCheckCategoryVersion
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11962): MountEmulatedStorage()
E/Zygote  (11962): v2
I/libpersona(11962): KNOX_SDCARD checking this for 10136
I/libpersona(11962): KNOX_SDCARD not a persona
,I/SELinux (11962): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11962): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=11962 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (11962): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Killing 11134:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11962): TimaSignature is unavailable
,D/ActivityThread(11962): Added TimaKeyStore provider
,D/ResourcesManager(11962): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11962): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11962): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11962): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11962): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/dhcpcd  (11837): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/GAV2    (11555): Thread[GAThread,5,main]: No campaign data found.
,I/dhcpcd  (11837): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3522): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3522): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/WebViewFactory(11962): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11962): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11962): Loading: webviewchromium
,I/LibraryLoader(11962): Time to load native libraries: 4 ms (timestamps 3198-3202)
I/LibraryLoader(11962): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11962): Binding Chromium to main looper Looper (main, tid 1) {17b54dda}
,I/LibraryLoader(11962): Expected native library version number "",actual native library version number ""
I/chromium(11962): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11962): Initializing chromium process, renderers=0
,W/art     (11962): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11962): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,W/AudioManagerAndroid(11962): Requires BLUETOOTH permission
I/chromium(11962): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(11962): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(11962): Starting up...
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12064): MountEmulatedStorage()
E/Zygote  (12064): v2
I/libpersona(12064): KNOX_SDCARD checking this for 10150
I/libpersona(12064): KNOX_SDCARD not a persona
,I/SELinux (12064): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12064): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12064): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12064 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 11400:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,I/ActivityManager( 3522): Killing 11356:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##32
,D/TimaKeyStoreProvider(12064): TimaSignature is unavailable
,D/ActivityThread(12064): Added TimaKeyStore provider
,D/ResourcesManager(12064): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12064): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12064): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12064): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12064): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12064): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12064): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12079): MountEmulatedStorage()
E/Zygote  (12079): v2
I/libpersona(12079): KNOX_SDCARD checking this for 10178
I/libpersona(12079): KNOX_SDCARD not a persona
,I/SELinux (12079): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12079): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12079 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/SELinux (12079): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Killing 11377:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3522): do suspend true
,D/WifiP2pService( 3522): InactiveState{ what=143375 }
,D/WifiP2pService( 3522): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3522): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3522): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/TimaKeyStoreProvider(12079): TimaSignature is unavailable
E/WifiStateMachine( 3522): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/ActivityThread(12079): Added TimaKeyStore provider
,E/WifiStateMachine( 3522): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3522): Not connected state, yet.
E/WifiStateMachine( 3522): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3522): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3522): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3522): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3522): callSECApiInt - ID [210]
,E/WifiStateMachine( 3522): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService( 3522): updateNetworkInfo()
,D/ConnectivityService( 3522): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3522): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3522): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3522): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3522): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3522): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3522): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/ResourcesManager(12079): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12079): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12079): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(12079): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12079): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/WifiStateMachine( 3522): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine( 3522): Now, connected state.
E/WifiStateMachine( 3522): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3522): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling
,D/ConnectivityService( 3522): Adding Route [fe80::/64 -> :: wlan0] to network 503
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService( 3522): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 3522): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling
E/WifiStateMachine( 3522): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/ConnectivityService( 3522): Unexpected mtu value: 0, wlan0
D/WifiNative-HAL( 3522): callSECApiVoid - ID [212]
V/        ( 2844): QcRouteController
,E/WifiStateMachine( 3522): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3522): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,V/        ( 2844): QcRouteController
,V/        ( 2844): QcRouteController
,V/        ( 2844): QcRouteController
,V/        ( 2844): QcRouteController
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,V/        ( 2844): QcRouteController
,V/        ( 2844): QcRouteController
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,V/        ( 2844): QcRouteController
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/ConnectivityService( 3522): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3522): LTETest block dns file not exists
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,E/Zygote  (12119): MountEmulatedStorage()
E/Zygote  (12119): v2
I/libpersona(12119): KNOX_SDCARD checking this for 10082
I/libpersona(12119): KNOX_SDCARD not a persona
,I/SELinux (12119): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,I/SELinux (12119): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12119): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12119 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/ConnectivityService( 3522): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3522): updateNetworkInfo()
E/ConnectivityService( 3522): updateNetworkInfo()
,D/ConnectivityService( 3522): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3522): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3522): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): Connected
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): Checking http://clients3.google.com/generate_204 on "NG700"
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/TelephonyNetworkFactory( 3977): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 3522):    accepting network in place of null
,E/CSLegacyTypeTracker( 3522): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker( 3522): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/System.out( 3522): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 1000
,E/Zygote  (12131): MountEmulatedStorage()
E/Zygote  (12131): v2
I/libpersona(12131): KNOX_SDCARD checking this for 1000
I/libpersona(12131): KNOX_SDCARD not a persona
I/SELinux (12131): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12131): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12131): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12131 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3522): Killing 10036:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/ConnectivityService( 3522): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/EntConnectivity( 3522): Not allowed due to - mEnabled false
D/ConnectivityService( 3522): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/TimaKeyStoreProvider(12119): TimaSignature is unavailable
,D/ActivityThread(12119): Added TimaKeyStore provider
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
,D/Tethering( 3522): MasterInitialState.processMessage what=3
,D/ConnectivityManager.CallbackHandler( 6755): CM callback handler got msg 524290
D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3522): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
V/NetworkStats( 3522): updateIfacesLocked()
V/NetworkStats( 3522): performPollLocked(flags=0x1)
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 3522): UpdateStatsForKnox
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,D/SmartBondingService( 3522): getNetworkEnabled : wifi : true mobile : false
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,V/NetworkStats( 3522): performPollLocked() took 10ms
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
V/NetworkStats( 3522): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,I/ActivityManager( 3522): Killing 11445:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12131): TimaSignature is unavailable
,D/ActivityThread(12131): Added TimaKeyStore provider
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/ResourcesManager(12119): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager(12131): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,I/System.out( 3522): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/BadgeProvider(12119): onCreate
D/BadgeProvider(12119): DatabaseHelper
,I/ActivityManager( 3522): Killing 11462:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/BadgeProvider(12119): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 20 Dec 2015 23:53:04 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450655584209], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450655584192]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): Validated
D/ConnectivityService( 3522): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3522): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3522): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3522): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 6755): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
,W/ActivityManager( 3522): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/BadgeProvider(12119): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12119): sendNotify, [notify] : null
D/BadgeProvider(12119): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12119): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12119): update, [UpdateCount] : 1
,D/Launcher.Model( 4000): reloadBadges entered.
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12154): MountEmulatedStorage()
I/libpersona(12154): KNOX_SDCARD checking this for 10013
E/Zygote  (12154): v2
I/libpersona(12154): KNOX_SDCARD not a persona
,I/SELinux (12154): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12154 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux (12154): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12154): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12154): TimaSignature is unavailable
,D/ActivityThread(12154): Added TimaKeyStore provider
,D/ResourcesManager(12154): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,V/AlarmManager( 3522): waitForAlarm result :4
,V/AlarmManager( 3522): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 3522): <AppSync3 Whitelist>
V/AlarmManager( 3522): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
,D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3691): *** don't update sliding image ***
,D/WaitQueueForNetworkActivate(12154): notifyNetworkActivated
,D/SSRM:n  ( 3522): SIOP:: AP = 320, PST = 291, CUR = -22
,W/ContextImpl(12154): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3522): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/hcjo    (12154): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12154): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12154): exit::IDLE
D/InitializeManagerStateMachine(12154): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12154): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12154): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12154): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12154): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12154): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12154): entry::SUCCESS
D/hcjo    (12154): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12154): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12154): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12154): exit::SUCCESS
D/InitializeManagerStateMachine(12154): entry::IDLE
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
I/ActivityManager( 3522): Killing 11481:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:-206, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:136
D/BatteryService( 3522): stay LED for fully charged
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/Hs20UtilService( 4113): Starting #10
,I/Hs20UtilService( 4113): Message received 5007
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/NearbySettings(11225): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings(11225): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(11225): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings(11225): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings(11225): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11225): MountReceiver.onReceive - Keep current state
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SignOutReceiver(11637): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4113): Starting #11
,I/Hs20UtilService( 4113): Message received 5007
,D/NearbySettings(11225): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings(11225): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11637): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4113): Starting #12
,I/Hs20UtilService( 4113): Message received 5007
,D/NearbySettings(11225): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings(11225): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(11225): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/NearbySettings(11225): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings(11225): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11225): MountReceiver.onReceive - Keep current state
,D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3522): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3522): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3522): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3522): getSBEnabled() enabled =false
,D/SmartBondingService( 3522): getSBEnabled() enabled =false
,D/SmartBondingService( 3522): getSBEnabled() enabled =false
,D/SmartBondingService( 3522): getNetworkEnabled : wifi : true mobile : false
,I/PowerManagerService( 3522): [PWL] Off : 30s ago
,I/PowerManagerService( 3522): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 3522): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 3522): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=3522, ws=null) (elapsedTime=4157)
I/PowerManagerService( 3522): [PWL]       PARTIAL_WAKE_LOCK              'SyncLoopWakeLock' (uid=1000, pid=3522, ws=null) (elapsedTime=13)
,I/SignOutReceiver(11637): NETWORK_STATE_CHANGED_ACTION
,W/ResourceType( 5375): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5375): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/NetworkMonitor(11763): type=WIFI subType= reason=null isConnected=true
,I/DBG_DM  ( 6271): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6271): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/Hs20UtilService( 4113): Starting #13
,I/Hs20UtilService( 4113): Message received 5007
,D/NearbySettings(11225): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings(11225): MountReceiver.onReceive - Keep current state
,D/GpsLocationProvider( 3522): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/WifiStateMachine( 3522): callSECApi what=220
D/WifiStateMachine( 3522): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(11637): NETWORK_STATE_CHANGED_ACTION
,D/SecContentProvider2( 3522): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3522): mCursor = null
,I/SurfaceFlinger( 2848): id=15 createSurf (1x1),1 flag=4, Uoast
,I/PCWCLIENTTRACE_PushUtil(11207): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11207): sales region : global
I/PCWCLIENTTRACE_PushUtil(11207): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11207): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/PowerManagerService( 3522): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3522
,D/mali_winsys( 3691): new_window_surface returns 0x3000,  [1120x201]-format:1
,I/DIAGMON_AGENT(11821): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11821): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client(11844): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11844): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11844): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (11860): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Dec 21 00:53:04 GMT+01:00 2015
,I/KLMS-2.4.521: (11860): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11860): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11860): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11860): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11860): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11860): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11860): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/SO_AGENT(11876): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (11860): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11860): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (11860): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11860): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (11860): KLMSIntentService(): onDestroy()
,E/SPPClientService(11316): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (10827): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (10827): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (10827): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (10827): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (10827): [OR] == isSIMCardReady false ==
,I/SA      (10827): [SCU] == networkStateCheck == true
,I/SA      (10827): [DM] getCountryCodeFromCSC : PL
I/SA      (10827): isChinaCountryCode : false
I/SA      (10827): [SCU] is ChinestModel Data Restricted   : false
I/SA      (10827): [OR] == networkStateCheck true ==
,I/SA      (10827): [OR] GetMyCountryZoneTask
I/SA      (10827): [OR] onReceive END
,I/SA      (10827): [SRS] prepareGetMyCountryZone
,I/SA      (10827): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (10827): [SSP] query invoked
,V/DownloadManager( 5506): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (10827): [TPMU] GetMccFromDB : null
I/SA      (10827): [SCU] getMccFromPreferece mcc = 260
I/SA      (10827): [TPM] isNoProxy(default) : true
,I/SCloudBackupReceiver(11894): Other Intent
,D/accuweather( 5208): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5208): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5208): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5208): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5208): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5208): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5208): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(11915): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(11915): premStatus:2
,I/KnoxUsageLogPro(11915): isEulaShown : false
I/KnoxUsageLogPro(11915): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(11946): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(11946): cancelUpdateCategory
D/KeyguardWallpaperUpdator(11946): stopCheckCategoryVersion
,D/QuickConnect(12064): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12064): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12064): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/ConnectivityService( 3522): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/hcjo    (12154): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12154): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12154): exit::IDLE
D/InitializeManagerStateMachine(12154): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12154): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12154): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12154): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12154): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12154): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12154): entry::SUCCESS
D/hcjo    (12154): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12154): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12154): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine(12154): exit::SUCCESS
D/InitializeManagerStateMachine(12154): entry::IDLE
,I/SA      (10827): [RC New] Execute method=[GET] start
,I/SA      (10827): [RC New] Security=[true]
,I/System.out(10827): Thread-1456(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(10827): Thread-1456(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(10827): Thread-1456(ApacheHTTPLog):isShipBuild true
I/System.out(10827): Thread-1456(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 10045
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11538): setDiscoveryMode: Mode set to BLE
,I/jxcore-log(11538): BLE supported!!
I/jxcore-log(11538): 
,E/WifiStateMachine( 3522): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService( 3522): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2844): QcRouteController
D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3522): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
,D/SmartBondingService( 3522): getSBEnabled() enabled =false
,V/        ( 2844): QcRouteController
,W/NetworkManagementService( 3522): route cmd failed: 
W/NetworkManagementService( 3522): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3522): '
W/NetworkManagementService( 3522): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3522): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3522): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3522): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3522): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3522): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3522): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3522): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3522): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ConnectivityService( 3522): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524295
,D/ConnectivityService( 3522): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 6755): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6755): CM callback handler got msg 524295
,I/SA      (10827): [RC New] [v2liruge] api execute + 714
,I/SA      (10827): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(10827): AsyncTask #1 calls detatch()
,I/SA      (10827): [TPMU] getNetworkMcc : 
,I/SA      (10827): [SCU] saveMccToPreferece Start
,I/SA      (10827): [SCU] RegionMCC : 260
,I/SA      (10827): [SSP] query invoked
,I/SA      (10827): [TPMU] GetMccFromDB : null
,I/SA      (10827): [SCU] getMccFromPreferece mcc = 260
,I/SA      (10827): [SCU] saveMccToPreferece End
,I/SA      (10827): [RC New] executeRequest [v2liruge] end. 780
,I/SA      (10827): [RC New] Execute end
,I/SA      (10827): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      (10827): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  (11837): wlan0: sending IPv6 Router Solicitation
,D/WearableService( 4638): callingUid 10014, callindPid: 4638
,D/ResourcesManager(11763): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11763): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11763): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11763): Using the GMSCore's GoogleHttpClient
,D/WearableClient(11763): WearableClientImpl.onPostInitHandler: done
,I/MusicLeanback(11763): Conditions not met for autocaching.
I/MusicLeanback(11763): Stop autocaching.
,D/WearableClient(11763): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11763): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11763): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11763): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11763): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11763): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@1fefda8 that was originally bound here
E/ActivityThread(11763): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@1fefda8 that was originally bound here
E/ActivityThread(11763): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11763): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11763): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11763): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11763): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11763): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11763): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11763): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11763): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11763): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11763): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11763): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11763): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11763): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11763): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11763): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11763): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11763): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11763): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11763): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11763): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11763): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11763): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11763): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/PackageManager( 3522): [MSG] MCS_UNBIND
,I/WifiStateMachine( 3522): REQUEST_POWER_SAVE_ON
,I/ActivityManager( 3522): Killing 11503:com.samsung.helphub/1000 (adj 13): bgCount ##31
,E/WifiStateMachine( 3522): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PackageManager( 3522): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/SurfaceFlinger( 2848): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2848): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3522): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3522) eventTime = 127874
,D/PowerManagerService( 3522): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3522 (0x0)
,D/PowerManagerService( 3522): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3522, ws=WorkSource{10060}) (elapsedTime=3494)
,I/GAV4    (11962): Thread[GAThread,5,main]: No campaign data found.
,W/ProcessCpuTracker( 3522): Skipping unknown process pid 12253
,I/PCWCLIENTTRACE_SYSTEMReceiver(11207): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11207): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11207): ================================================
,I/CSTORAGE(11207):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11207): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11207): [GetString-S]
,E/art     (11207): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(11207): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11207): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11207): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(11207): sales region : global
I/PCWCLIENTTRACE_PushUtil(11207): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler(11207): [ensureRegistration] - No Samsung account
,I/dhcpcd  (11837): wlan0: sending IPv6 Router Solicitation
,V/AlarmManager( 3522): waitForAlarm result :4
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12271): MountEmulatedStorage()
E/Zygote  (12271): v2
I/libpersona(12271): KNOX_SDCARD checking this for 10031
I/libpersona(12271): KNOX_SDCARD not a persona
,I/SELinux (12271): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12271): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=12271 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12271): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12271): TimaSignature is unavailable
,D/ActivityThread(12271): Added TimaKeyStore provider
,I/EventLogService( 6755): Aggregate from 1450653788381 (log), 1450653788381 (data)
,D/ResourcesManager(12271): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/Finsky  (12271): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  (12271): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings(12271): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings(12271): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  (12271): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  (12271): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     (12271): Skipping gmscore version check
,D/Finsky  (12271): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager( 3522): Waited long enough for: ServiceRecord{318d2bcc u0 com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayService}
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 50858(2MB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 49MB/65MB, paused 2.493ms total 145.862ms
,D/Finsky  (12271): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/Watchdog( 3522): !@Sync 4
,D/Finsky  (12271): [1725] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  (12271): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager( 3522): Killing 11667:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,I/dhcpcd  (11837): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (11837): wlan0: no IPv6 Routers available
,D/SSRM:n  ( 3522): SIOP:: AP = 290, PST = 285, CUR = -206
,D/PreloadUpdateManagerStateMachine(12154): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12154): exit::IDLE
,D/PreloadUpdateManagerStateMachine(12154): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12154): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12154): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12154): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12154): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine(12154): entry::IDLE
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:-21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:111
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PreloadUpdateManagerStateMachine(12154): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12154): exit::IDLE
D/PreloadUpdateManagerStateMachine(12154): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12154): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12154): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12154): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12154): entry::IDLE
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 270, PST = 285, CUR = -21
,I/PowerManagerService( 3522): [PWL] Off : 50s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:75
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 270, PST = 281, CUR = 43
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:63, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:61
,D/BatteryService( 3522): stay LED for fully charged
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 5
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 280, CUR = 63
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:65, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:58
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3522): [PWL] Off : 75s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 279, CUR = 65
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:63, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3522): waitForAlarm result :8
,I/ClearcutLoggerApiImpl( 4638): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 278, CUR = 63
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:60, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3522): !@Sync 6
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 276, CUR = 60
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3522): [PWL] Off : 105s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 275, CUR = 57
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:54, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 274, CUR = 54
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 7
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 270, CUR = 52
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 267, CUR = 49
,I/PowerManagerService( 3522): [PWL] Off : 140s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3522): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
,D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3691): *** don't update sliding image ***
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager( 3522): waitForAlarm result :8
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 265, CUR = 47
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3522): !@Sync 8
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 264, CUR = 46
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:66
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 262, CUR = 45
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 260, CUR = 43
,I/PowerManagerService( 3522): [PWL] Off : 180s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 9
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 258, CUR = 41
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 256, CUR = 42
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 256, CUR = 41
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3522): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3522): initializing...
,I/TLC_TIMA_PKM_initialize( 3522): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3522): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3522): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 3522): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 3522): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3522): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3522): aligned max_sendmsg_size = 262208,
I/TZ: mc_tlc_communication( 3522): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3522): device_id = 0x0
I/TZ: mc_tlc_communication( 3522): tlc_open() was called
I/TZ: mc_tlc_communication( 3522): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3522): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3522): Opening the session
,I/TZ: mc_tlc_communication( 3522): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3522): Trustlet response is completed
,E/Watchdog( 3522): !@Sync 10,
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 255, CUR = 40
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3522): [PWL] Off : 225s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 253, CUR = 39
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 252, CUR = 37
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 11
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 251, CUR = 36
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 250, CUR = 35
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3522): stay LED for fully charged
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 249, CUR = 35
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
D/BatteryService( 3522): stay LED for fully charged
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3522): [PWL] Off : 275s ago
,E/Watchdog( 3522): !@Sync 12
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 248, CUR = 36
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 248, CUR = 35
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 247, CUR = 35
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 13
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 246, CUR = 34
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 246, CUR = 34
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3522): waitForAlarm result :8
,I/PowerManagerService( 3522): [PWL] Off : 330s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 245, CUR = 33
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3522): !@Sync 14
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 245, CUR = 33
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3522): stay LED for fully charged
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 245, CUR = 32
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 244, CUR = 30
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3522): stay LED for fully charged
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 15
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 244, CUR = 28
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 244, CUR = 29
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 3522): [PWL] Off : 390s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 243, CUR = 29
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3522): stay LED for fully charged
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3522): !@Sync 16
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 243, CUR = 28
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 243, CUR = 29
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 242, CUR = 29
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 17
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 242, CUR = 28
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 242, CUR = 27
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 241, CUR = 27,
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 455s ago
,E/Watchdog( 3522): !@Sync 18
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 241, CUR = 25
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 241, CUR = 26
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 28
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 19
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 27
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 25
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 25,
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3522): TimaServiceHandler.handleMessage what =1,
,E/Watchdog( 3522): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 25
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 525s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 24
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 25
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 21
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 25
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 25,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 25
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 22
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 24
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 24
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 600s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 24
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 23
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 23
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 22
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 22
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 24
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 239, CUR = 22
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 239, CUR = 20
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 239, CUR = 21
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3522): !@Sync 25
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 238, CUR = 21
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 680s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 238, CUR = 20
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 238, CUR = 20
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 26
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 237, CUR = 19
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 237, CUR = 21
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 237, CUR = 19
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 27
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 236, CUR = 20
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 236, CUR = 18
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 236, CUR = 19
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 28
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 235, CUR = 18
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3522): [PWL] Off : 765s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 235, CUR = 18
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 235, CUR = 19
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 29
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 234, CUR = 18
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 234, CUR = 15
,V/AlarmManager( 3522): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
,D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3691): *** don't update sliding image ***
,D/LightsService( 3522): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3522): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3522): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/Sensors ( 3522): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/LightsService( 3522): [SvcLED]  onSensorChanged::light value = 0
,I/Sensors ( 3522): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3522): unregisterListener ::   
,D/LightsService( 3522): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 234, CUR = 18
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3522): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 30
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 233, CUR = 17
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 233, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 233, CUR = 16
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 31
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 232, CUR = 16
,I/PowerManagerService( 3522): [PWL] Off : 855s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 232, CUR = 17
,V/AlarmManager( 3522): waitForAlarm result :8
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 232, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 32
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 231, CUR = 15
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 231, CUR = 15
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 231, CUR = 16
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 33
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 34
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 14
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 950s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 35
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3522): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
,D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3691): *** don't update sliding image ***
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 15
,V/AlarmManager( 3522): waitForAlarm result :8
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 16
,E/Watchdog( 3522): !@Sync 36
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-9
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 15
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 15
,E/Watchdog( 3522): !@Sync 37
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 1050s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 14
,E/Watchdog( 3522): !@Sync 38
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
D/BatteryService( 3522): stay LED for fully charged
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 14
,E/Watchdog( 3522): !@Sync 39
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3,
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-14
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 13
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3522): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 3522): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3522): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3522): Updating Usage Statistics in DB @ 1450656671806
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$Cu,rsorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3522): Done Updating Usage Statistics in DB @ 1450656671903
,E/Watchdog( 3522): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-11
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,E/Watchdog( 3522): !@Sync 41
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,I/PowerManagerService( 3522): [PWL] Off : 1155s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 13
,E/Watchdog( 3522): !@Sync 42
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-6
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,E/Watchdog( 3522): !@Sync 43
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,E/Watchdog( 3522): !@Sync 44
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12,
,I/PowerManagerService( 3522): [PWL] Off : 1265s ago
,E/Watchdog( 3522): !@Sync 45
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,E/Watchdog( 3522): !@Sync 46
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,I/art     ( 3522): Background sticky concurrent mark sweep GC freed 88285(9MB) AllocSpace objects, 385(6MB) LOS objects, 13% free, 49MB/57MB, paused 3.143ms total 119.107ms
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 13
,E/Watchdog( 3522): !@Sync 47
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 14,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,E/Watchdog( 3522): !@Sync 48
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11
,I/PowerManagerService( 3522): [PWL] Off : 1380s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-13
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11
,E/Watchdog( 3522): !@Sync 49
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3522): TimaServiceHandler.handleMessage what =1,
,E/Watchdog( 3522): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3522): stay LED for fully charged
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 51
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12,
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 52
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 3522): [PWL] Off : 1500s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 53
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 54
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 55
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11,
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 56
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 1625s ago
,E/Watchdog( 3522): !@Sync 57
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 58
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 59
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 7,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3522): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
,D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3691): *** don't update sliding image ***
,W/ProcessCpuTracker( 3522): Skipping unknown process pid 13291
,D/NetworkStatsFactory( 3522): UpdateStatsForKnox
,V/AlarmManager( 3522): OOI=Alarm{14f09322 type 0 when 1450659060355 com.google.android.gms}
,V/AlarmManager( 3522): waitForAlarm result :8
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged,
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3522): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 3522): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-16
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 61
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 5
,I/PowerManagerService( 3522): [PWL] Off : 1755s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 7
,V/AlarmManager( 3522): waitForAlarm result :8
,D/LightsService( 3522): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3522): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3522): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,I/ProcessStatsService( 3522): Prepared write state in 16ms
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
,D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3691): *** don't update sliding image ***
,I/ProcessStatsService( 3522): Pruning old procstats: /data/system/procstats/state-2015-12-20-03-40-08.bin
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/Sensors ( 3522): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/LightsService( 3522): [SvcLED]  onSensorChanged::light value = 0
,I/Sensors ( 3522): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3522): unregisterListener ::   
,D/LightsService( 3522): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-8
,D/BatteryService( 3522): stay LED for fully charged
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 3522): Skipping unknown process pid 13360
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 62
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-16
D/BatteryService( 3522): stay LED for fully charged
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-18
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 63
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 7
,V/AlarmManager( 3522): waitForAlarm result :8
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1800000ms),E/Watchdog( 3522): !@Sync 64
I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 5
D/AndroidRuntime(13399): 
D/AndroidRuntime(13399): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13399): CheckJNI is OFF
D/AndroidRuntime(13399): readGMSProperty: start
D/AndroidRuntime(13399): readGMSProperty: already setted!!
D/AndroidRuntime(13399): readGMSProperty: end
D/AndroidRuntime(13399): addProductProperty: start
E/AffinityControl(13399): AffinityControl: registerfunction enter
D/AndroidRuntime(13399): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 3522): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3522): START PACKAGE DELETE: observer{573095790}
D/PackageManager( 3522): pkg{<packageName>}
D/PackageManager( 3522): user{0}
D/PackageManager( 3522): caller{2000}
D/PackageManager( 3522): flags{3}
D/PersonaManagerService( 3522): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 3522): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 3522): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3522): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3522): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3522): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3522): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3522): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3522): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3522): !@killApplicatoin: 10520, uninstall pkg
I/ActivityManager( 3522): Force stopping com.test.thalitest appid=10520 user=-1: uninstall pkg
I/ActivityManager( 3522): Killing 11538:com.test.thalitest/u0a520 (adj 0): stop com.test.thalitest
I/ActivityManager( 3522): Killing 11894:com.samsung.android.scloud.backup/u0a67 (adj 13): empty for 1813s
I/ActivityManager( 3522): Killing 10827:com.osp.app.signin/u0a45 (adj 13): empty for 1813s
I/ActivityManager( 3522): Killing 11278:com.policydm/1000 (adj 13): empty for 1813s
I/ActivityManager( 3522): Killing 11876:com.sec.android.soagent/u0a38 (adj 13): empty for 1813s
I/ActivityManager( 3522): Killing 11860:com.samsung.klmsagent/u0a21 (adj 13): empty for 1813s
I/ActivityManager( 3522): Killing 11844:com.sec.android.fotaclient/u0a12 (adj 13): empty for 1813s
I/ActivityManager( 3522): Killing 11821:com.sec.android.diagmonagent/1000 (adj 13): empty for 1813s
I/ActivityManager( 3522): Killing 11802:com.sec.android.cloudagent/u0a2 (adj 13): empty for 1813s
I/ActivityManager( 3522): Killing 11207:com.sec.pcw.device/1000 (adj 15): empty for 1813s
I/ActivityManager( 3522): Killing 10239:com.facebook.appmanager/u0a110 (adj 15): empty for 1813s
I/ActivityManager( 3522): Killing 11637:com.samsung.android.snote/u0a160 (adj 15): empty for 1813s
I/ActivityManager( 3522): Killing 11225:com.android.settings/1000 (adj 15): empty for 1813s
I/ActivityManager( 3522): Killing 12119:com.sec.android.provider.badge/u0a82 (adj 15): empty for 1814s
I/ActivityManager( 3522): Killing 11706:com.sec.android.widgetapp.tapandpay/u0a190 (adj 15): empty for 1819s
I/ActivityManager( 3522): Killing 11687:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 15): empty for 1819s
I/ActivityManager( 3522):   Force finishing activity ActivityRecord{164516fb u0 com.test.thalitest/.MainActivity t26}
W/ActivityManager( 3522): mDVFSHelper.acquire()
W/PackageSettings( 3522): Skipping PackageSetting{14c888c3 com.example.hello/10500} due to missing metadata
D/WifiService( 3522): Client connection lost with reason: 4
E/JavaBinder( 3522): !!! FAILED BINDER TRANSACTION !!!
D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
I/WindowState( 3522): WIN DEATH: Window{39b9848c u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 2848): id=14 Removed NainActivit (5/8)
D/WifiService( 3522): Client connection lost with reason: 4
I/SurfaceFlinger( 2848): id=14 Removed NainActivit (-2/8)
I/SurfaceFlinger( 2848): id=14 Removed NainActivit (-2/8)
I/ActivityManager( 3522): Force stopping com.test.thalitest appid=10520 user=0: pkg removed
I/ActivityManager( 3522):   Force finishing activity ActivityRecord{164516fb u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3522): Duplicate finish request for ActivityRecord{164516fb u0 com.test.thalitest/.MainActivity t26 f}
I/art     ( 8813): Explicit concurrent mark sweep GC freed 31651(1743KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.140ms total 33.529ms
I/art     ( 4037): Explicit concurrent mark sweep GC freed 33123(2030KB) AllocSpace objects, 1(39KB) LOS objects, 21% free, 28MB/36MB, paused 1.307ms total 46.612ms
I/art     ( 6755): Explicit concurrent mark sweep GC freed 31020(1783KB) AllocSpace objects, 5(80KB) LOS objects, 20% free, 31MB/39MB, paused 2.068ms total 65.423ms
W/libprocessgroup( 3522): failed to open /acct/uid_10012/pid_11844/cgroup.procs: No such file or directory
W/libprocessgroup( 3522): failed to open /acct/uid_10021/pid_11860/cgroup.procs: No such file or directory
W/libprocessgroup( 3522): failed to open /acct/uid_10190/pid_11706/cgroup.procs: No such file or directory
W/libprocessgroup( 3522): failed to open /acct/uid_1000/pid_11278/cgroup.procs: No such file or directory
W/libprocessgroup( 3522): failed to open /acct/uid_10067/pid_11894/cgroup.procs: No such file or directory
W/libprocessgroup( 3522): failed to open /acct/uid_10038/pid_11876/cgroup.procs: No such file or directory
W/libprocessgroup( 3522): failed to open /acct/uid_10002/pid_11802/cgroup.procs: No such file or directory
W/libprocessgroup( 3522): failed to open /acct/uid_10045/pid_10827/cgroup.procs: No such file or directory
W/libprocessgroup( 3522): failed to open /acct/uid_10160/pid_11637/cgroup.procs: No such file or directory
W/libprocessgroup( 3522): failed to open /acct/uid_10082/pid_12119/cgroup.procs: No such file or directory
W/libprocessgroup( 3522): failed to open /acct/uid_1000/pid_11207/cgroup.procs: No such file or directory
W/libprocessgroup( 3522): failed to open /acct/uid_1000/pid_11821/cgroup.procs: No such file or directory
W/libprocessgroup( 3522): failed to open /acct/uid_1000/pid_11225/cgroup.procs: No such file or directory
I/DBG_DM  ( 6271): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
W/libprocessgroup( 3522): failed to open /acct/uid_10110/pid_10239/cgroup.procs: No such file or directory
W/libprocessgroup( 3522): failed to open /acct/uid_10183/pid_11687/cgroup.procs: No such file or directory
I/DBG_DM  ( 6271): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 8
I/DBG_DM  ( 6271): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/DBG_DM  ( 6271): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/DBG_DM  ( 6271): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 8
I/InputReader( 3522): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 4502): mOCRHelper is null
W/GeofencerStateMachine( 4638): Ignoring removeGeofence because network location is disabled.
I/DBG_DM  ( 6271): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
I/DBG_DM  ( 6271): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (13421): MountEmulatedStorage()
E/Zygote  (13421): v2
I/libpersona(13421): KNOX_SDCARD checking this for 10063
I/libpersona(13421): KNOX_SDCARD not a persona
I/SELinux (13421): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=13421 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (13421): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13421): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 6271): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
W/ResourceType( 5375): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5375): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
I/art     ( 2881): Explicit concurrent mark sweep GC freed 8735(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.004ms total 22.961ms
D/SecContentProvider2( 3522): uri = 14 selection = getSealedState
D/SecContentProvider2( 3522): mCursor = null
D/ApplicationPolicy( 3522): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/TimaKeyStoreProvider(13421): TimaSignature is unavailable
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 842us total 19.238ms
D/ActivityThread(13421): Added TimaKeyStore provider
I/DBG_DM  ( 6271): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 8
I/DBG_DM  ( 6271): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 356us total 11.399ms
I/DBG_DM  ( 6271): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6271): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 6271): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 6271): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
I/DBG_DM  ( 6271): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
I/art     ( 3522): Explicit concurrent mark sweep GC freed 53059(5MB) AllocSpace objects, 171(2MB) LOS objects, 24% free, 49MB/65MB, paused 4ms total 202.951ms
I/art     ( 3522): WaitForGcToComplete blocked for 130.906ms for cause Explicit
D/ActivityManager( 3522): post active user change for 0
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/KnoxTimeoutHandler( 3522): postActiveUserChange for user 0
I/DBG_DM  ( 6271): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
I/UsageStatsService( 3522): User[0] Rolling over usage stats
I/UsageStatsService( 3522): User[0] Flushing usage stats to disk
I/SurfaceFlinger( 2848): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 6271): updateVisibility : ActivityRecord{3c85437b token=android.os.BinderProxy@2dfa192c {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
I/UsageStatsService( 3522): User[0] Rollover scheduled @ 2015-12-22 01:00:00(1450742400000)
I/UsageStatsService( 3522): User[0] Flushing usage stats to disk
D/ResourcesManager(13421): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/UsageStatsService( 3522): User[0] Rolling over usage stats complete. Took 64 milliseconds
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/VRSetupWizardStub/PackageIntentReceiver(13421): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(13421): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(13421): packagename:com.test.thalitest
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
E/Zygote  (13438): MountEmulatedStorage()
E/Zygote  (13438): v2
I/libpersona(13438): KNOX_SDCARD checking this for 10021
I/libpersona(13438): KNOX_SDCARD not a persona
I/SELinux (13438): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13438): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
E/SELinux (13438): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=13438 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
D/InputMethodManagerService( 3522): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/talkback/talkback.apk
I/ActivityManager( 3522): Killing 11915:com.sec.knox.bridge/1000 (adj 15): empty for 1813s
W/InputMethodManagerService( 3522): Got RemoteException sending setActive(false) notification to pid 11538 uid 10520
I/Timeline( 6271): Timeline: Activity_idle id: android.os.BinderProxy@2dfa192c time:1938371
W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3522): mDVFSHelper.release()
I/Timeline( 3522): Timeline: Activity_windows_visible id: ActivityRecord{2ef7a839 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:1938374
D/TimaKeyStoreProvider(13438): TimaSignature is unavailable
D/ActivityThread(13438): Added TimaKeyStore provider
D/ResourcesManager(13438): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/SecContentProvider2( 3522): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3522): mCursor = null
I/KLMS-2.4.521: (13438): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Dec 21 01:23:18 GMT+01:00 2015
I/art     ( 3522): Explicit concurrent mark sweep GC freed 11053(707KB) AllocSpace objects, 9(144KB) LOS objects, 24% free, 48MB/64MB, paused 7.380ms total 188.819ms
I/art     ( 3522): WaitForGcToComplete blocked for 240.372ms for cause Background
I/KLMS-2.4.521: (13438): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 3522): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3522): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
I/KLMS-2.4.521: (13438): KLMSIntentService(): onCreate()
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (13438): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.521: (13438): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.4.521: (13438): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.4.521: (13438): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.4.521: (13438): KLMSIntentService(): listeningToPackageRemoved().START
E/Zygote  (13456): MountEmulatedStorage()
E/Zygote  (13456): v2
I/libpersona(13456): KNOX_SDCARD checking this for 10106
I/libpersona(13456): KNOX_SDCARD not a persona
I/SELinux (13456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
I/KLMS-2.4.521: (13438): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
I/SELinux (13456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13456): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=13456 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
W/libprocessgroup( 3522): failed to open /acct/uid_1000/pid_11915/cgroup.procs: No such file or directory
D/RegisteredServicesCache( 3967): empty dynamic service
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/PackageManager( 3522): delete codoeFile: 
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
I/AASAUninstall( 3522):  com.test.thalitest not target!
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/PackageManager( 3522): result of delete: 1{573095790}
D/EnterpriseDeviceManagerService( 3522): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3522): Admin package name: com.google.android.gms
D/AndroidRuntime(13399): Shutting down VM
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/TimaKeyStoreProvider(13456): TimaSignature is unavailable
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ActivityThread(13456): Added TimaKeyStore provider
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
E/Zygote  (13471): MountEmulatedStorage()
E/Zygote  (13471): v2
I/libpersona(13471): KNOX_SDCARD checking this for 1000
I/libpersona(13471): KNOX_SDCARD not a persona
I/SELinux (13471): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13471): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=13471 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Books/Books.apk
E/SELinux (13471): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
E/Zygote  (13483): MountEmulatedStorage()
I/libpersona(13483): KNOX_SDCARD checking this for 10160
E/Zygote  (13483): v2
I/libpersona(13483): KNOX_SDCARD not a persona
I/SELinux (13483): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13483): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13483): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=13483 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(13471): TimaSignature is unavailable
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ActivityThread(13471): Added TimaKeyStore provider
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/TimaKeyStoreProvider(13483): TimaSignature is unavailable
E/Zygote  (13501): MountEmulatedStorage()
E/Zygote  (13501): v2
I/libpersona(13501): KNOX_SDCARD checking this for 10050
I/libpersona(13501): KNOX_SDCARD not a persona
I/SELinux (13501): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ActivityThread(13483): Added TimaKeyStore provider
I/SELinux (13501): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13501): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=13501 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/KLMS-2.4.521: (13438): KLMSIntentService(): listeningToPackageRemoved().END
D/ResourcesManager(13456): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager(13471): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
W/ResourcesManager(13471): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/KLMS-2.4.521: (13438): KLMSIntentService(): onDestroy()
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/TimaKeyStoreProvider(13501): TimaSignature is unavailable
D/ActivityThread(13501): Added TimaKeyStore provider
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
I/ActivityManager( 3522): Killing 11930:com.android.chrome/u0a90 (adj 15): empty for 1813s
D/elm:14491(13456): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/elm:14491(13456): ELMEngine.ELMEngine( context ).
D/elm:14491(13456): MDMBridge.setEnterpriseBridge()
D/ResourcesManager(13483): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/RCPManager(13471):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3522):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3522): queryAllProviders():  providerCallBack is not register for 0
D/elm:14491(13456): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
W/ResourcesManager(13483): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(13483): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13483): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/elm:14491(13456): ElmAgentService : onCreate()
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/elm:14491(13456): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491(13456): MainReceiver.listeningToPackageRemoved()
D/elm:14491(13456): MDMBridge.getInstance()
D/elm:14491(13456): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491(13456): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(13501): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
W/ResourcesManager(13501): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13501): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13501): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13501): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13501): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(13501): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(13501): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(13501): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/Zygote  (13518): MountEmulatedStorage()
E/Zygote  (13518): v2
I/libpersona(13518): KNOX_SDCARD checking this for 10101
I/libpersona(13518): KNOX_SDCARD not a persona
I/SELinux (13518): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13518): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=13518 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (13518): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/elm:14491(13456): ElmAgentService : onDestroy().
I/ActivityManager( 3522): Killing 11946:com.samsung.android.keyguardwallpaperupdator/u0a127 (adj 15): empty for 1813s
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
W/ResourceType( 3522): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/TimaKeyStoreProvider(13518): TimaSignature is unavailable
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityThread(13518): Added TimaKeyStore provider
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
E/Zygote  (13535): MountEmulatedStorage()
E/Zygote  (13535): v2
I/libpersona(13535): KNOX_SDCARD checking this for 10019
I/libpersona(13535): KNOX_SDCARD not a persona
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (13535): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 3522): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3522): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
I/ActivityManager( 3522): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=13535 uid=10019 gids={50019, 9997} abi=armeabi-v7a
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
I/SELinux (13535): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13535): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
V/Common  (13483): getScreenSize 1440 2560
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/libprocessgroup( 3522): failed to open /acct/uid_10090/pid_11930/cgroup.procs: No such file or directory
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}

```
