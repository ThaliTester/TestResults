#### Test 6012434797f7ca7_thali04_samsung-SM-N910C Logs


```
--------- beginning of main
V/DexLibLoader(10846): read status:9 check:faceb007faceb00e
V/DexLibLoader(10846): read saved dep file /data/data/com.facebook.katana/dex/deps (176 bytes)
V/DexLibLoader(10846): verified deps file
I/DexLibLoader(10846): current scheme: com.facebook.common.dextricks.OdexSchemeNoop next step: LA_LOAD_EXISTING
V/MultiDexClassLoader(10846): installing MultiDexClassLoader before application classloader
D/MultiDexClassLoader(10846): primary dex name: /data/app/com.facebook.katana-2/base.apk
D/MultiDexClassLoader(10846): Found system/other dex /system/framework/com.google.android.maps.jar
D/MultiDexClassLoader(10846): Found primary dex /data/app/com.facebook.katana-2/base.apk
D/MultiDexClassLoader(10846): Setup multi dex took 1 ms.
V/DexLibLoader(10846): optimization needed: no
D/MemoryReductionHack(10846): Marked as initialized entry corresponding to path /data/app/com.facebook.katana-2/base.apk
E/[CarMode](10935): [DLApplication]-onCreate: Applicatino Started!
D/SampleAppCoreManager(10935): SampleAppCoreManager VACVersion '2.2.0.11867'
D/SampleAppCoreManager(10935): mContext is not null
I/VlingoAndroidCore(10935): AppName: SamsungCCTproject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
I/SL_DEBUG(10913): isLoggable:: isProductShip = 1
--------- beginning of system
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
I/SL_DEBUG(10913): isLoggable:: SL_DEBUG_EXIST = false
E/Zygote  (10963): MountEmulatedStorage()
E/Zygote  (10963): v2
I/SELinux (10963): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10963): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10963): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/libpersona(10963): KNOX_SDCARD checking this for 10034
I/libpersona(10963): KNOX_SDCARD not a persona
I/ActivityManager( 3523): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=10963 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
D/TimaKeyStoreProvider(10963): TimaSignature is unavailable
D/ActivityThread(10963): Added TimaKeyStore provider
D/ResourcesManager(10963): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,I/GMPM    (10846): App measurement is starting up
E/GMPM    (10846): getGoogleAppId failed with status: 10
E/GMPM    (10846): Uploading is not possible. App measurement disabled
I/System.out(10963): Inside WakeupProvider
E/DatabaseUtils(10963): Writing exception to parcel
E/DatabaseUtils(10963): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(10963): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(10963): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(10963): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(10963): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(10963): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(10963): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(10963): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(10963): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(10963): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(10963): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(10935): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err(10935): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err(10935): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err(10935): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err(10935): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err(10935): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err(10935): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err(10935): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err(10935): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err(10935): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err(10935): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err(10935): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(10935): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err(10935): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err(10935): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err(10935): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err(10935): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err(10935): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err(10935): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:131)
W/System.err(10935): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:197)
W/System.err(10935): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(10935): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err(10935): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(10935): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(10935): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(10935): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(10935): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(10935): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(10935): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(10935): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(10935): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(10935): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/DatabaseUtils(10963): Writing exception to parcel
E/DatabaseUtils(10963): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(10963): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(10963): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(10963): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(10963): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(10963): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(10963): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(10963): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(10963): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(10963): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(10963): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(10935): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err(10935): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err(10935): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err(10935): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err(10935): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err(10935): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err(10935): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err(10935): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err(10935): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err(10935): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err(10935): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err(10935): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(10935): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err(10935): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err(10935): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err(10935): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err(10935): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:242)
W/System.err(10935): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(10935): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err(10935): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(10935): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(10935): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(10935): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(10935): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(10935): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(10935): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(10935): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(10935): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(10935): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode](10935): [DLApplication]-Init Called!:false
W/[CarMode](10935): [CommonUtil]-=========================================
W/[CarMode](10935): [CommonUtil]-CarMode Version:1.10.38.19768
W/[CarMode](10935): [CommonUtil]-=========================================
E/[CarMode](10935): [DLApplication]-Init Started!:true
I/[CarModeFW](10935): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW](10935): ### com.sec.android.app.automotive.carmode.framework.DriveLinkServiceInterfaceImp::initialize(132)
I/[CarModeFW](10935): ### com.sec.android.automotive.drivelink.DLApplication::init(211)
I/[CarModeFW](10935): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(135)
I/[CarModeFW](10935): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW](10935): ### android.app.ActivityThread::handleBindApplication(5115)
I/[CarModeFW](10935): ### android.app.ActivityThread::access$1600(178)
I/[CarModeFW](10935): ### android.app.ActivityThread$H::handleMessage(1510)
I/[CarModeFW](10935): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW](10935): ### android.os.Looper::loop(145)
I/[CarModeFW](10935): ### android.app.ActivityThread::main(5944)
I/[CarModeFW](10935): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW](10935): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW](10935): ### com.android.internal.os.ZygoteInit::main(1194)
D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
I/VlingoApplication(10963): VlingoApplication appVersion ='11.7.0.1.39589', coreVersion = '2.5.2.15201', ro.csc.sales_code=XEO
W/ContextImpl(10913): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(10913): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
I/MessageDataHandler(10935): initialize
D/[CarModeFW](10935): CDH-initiazlieCaches : before sync
D/[CarModeFW](10935): CDH-initiazlieCaches : after sync
V/Transcoder(10913): Transcoder(0xaecee560)::constructor
V/Transcoder(10913): addObitRecipient
V/TMI-JNI (10913): Mobile Transcoder JNI version 1.6.0/20131120/4.4
D/[CarModeFW](10935): CDH-buildContactCacheWireFrame : cur len =0
I/VlingoAndroidCore(10963): AppName: SamsungTproject, Core: 2.5.2.15201, SDK: 2.0.1657, EDM:15201
D/[CarModeFW](10935): CDH-ContactDataHandler initiazlieCaches time : 11
D/[CarModeFW](10935): CDH-initiazlieCaches : end sync
D/ResourcesManager( 8863): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/Zygote  (11009): MountEmulatedStorage()
E/Zygote  (11009): v2
I/libpersona(11009): KNOX_SDCARD checking this for 10045
I/libpersona(11009): KNOX_SDCARD not a persona
I/SELinux (11009): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11009): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11009): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=11009 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/[CarModeFW](10935): DrivingManager-initialize...
I/SensorService( 3523): Skipped sensor HRMLED IR because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3523): Skipped sensor HRMLED RED because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3523): Skipped sensor MAX86902 because it requires permission 
I/SensorService( 3523): Skipped sensor HRM Sensor because it requires permission 
I/SensorService( 3523): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
D/TimaKeyStoreProvider(11009): TimaSignature is unavailable
D/ActivityThread(11009): Added TimaKeyStore provider
W/StaticBindingVerifier(10846): Verify
I/ActivityManager( 3523): Killing 10245:com.sec.knox.bridge/1000 (adj 13): bgCount ##31
D/ResourcesManager(11009): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
I/MediaPlayer(10935): Need to enable context aware info
V/MediaPlayer-JNI(10935): native_setup
V/MediaPlayer(10935): constructor
D/VlingoApplication(10963): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication(10963): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
V/MediaPlayer(10935): setListener
W/SQLiteConnectionPool( 4820): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/DialogFlow(10963): initQueue()
W/LightSharedPreferencesImpl(10846): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(10846): java.io.FileNotFoundException: /data/data/com.facebook.katana/app_light_prefs/com.facebook.katana/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(10846): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(10846): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(10846): 	at com.facebook.crudolib.prefs.LightSharedPreferencesStorage.a(update_current:56)
W/LightSharedPreferencesImpl(10846): 	at com.facebook.crudolib.prefs.LightSharedPreferencesImpl$1.run(update_favorite_contacts:61)
W/LightSharedPreferencesImpl(10846): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(10846): 	at com.facebook.common.executors.WrappingExecutorService$1.run(video_home:77)
W/LightSharedPreferencesImpl(10846): 	at com.facebook.common.executors.DefaultConstrainedListeningExecutorService$Worker.run(video_sleep_timeout_ms:327)
W/LightSharedPreferencesImpl(10846): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(10846): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(10846): 	at com.facebook.common.executors.NamedThreadFactory$1.run(video_story:42)
W/LightSharedPreferencesImpl(10846): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(10846): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(10846): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(10846): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(10846): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(10846): 	... 10 more
D/[CarModeFW](10935): MY_TAG-[YANG] MusicButtonReceiver construct MusicButtonReceiver() 
I/[CarModeFW](10935): DriveLinkServiceInterfaceImp-drivelink framework initialize end
D/[CarMode](10935): [DLServiceManager]-getOnDLLocationSuggestionListener..........
D/[CarModeFW](10935): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => start time : 1457378974883
D/[CarModeFW](10935): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1457378974885
I/SA      (11009): [SSP] onCreated
D/[CarModeFW](10935): ContactDataHandler-getFavoriteContactList : cur len = 0
D/[CarModeFW](10935): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 3
D/[CarMode](10935): [DLServiceManager]-updateLocationList
D/[CarMode](10935): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW](10935): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => start time : 1457378974889
D/[CarModeFW](10935): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => start time : 1457378974889
D/[CarModeFW](10935): insertNavigationAvailable-sql: select distinct nav_package from tb_location_navigation_available
D/[CarModeFW](10935): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => start time : 1457378974889
F/DLApplication(10935): DLApplication mListNavitationAvailable: [com.skt.skaf.l001mtm091, com.google.android.apps.maps, kt.navi, com.mnsoft.lgunavi, com.autonavi.xmgd.navigator.samsung, com.here.app.maps]
I/[CarMode](10935): [LogNotNull]-Package name is: com.here.app.maps
D/[CarModeFW](10935): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => start time : 1457378974890
D/[CarModeFW](10935): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1457378974891
E/[CarMode](10935): [DLApplication]-Init End!:true
D/[CarMode](10935): [TAG]-phone sound mode is: 0
V/[CarMode](10935): [DLApplication]-savePreviousGpsState
D/TP/SmsProvider( 3981): query,matched:2, calling pid = 10935
D/[CarModeFW](10935): CalllogDataHandler-getCalllogList : cur len = 0
I/SA      (11009): [TPM] There is no property file
D/TP/SmsProvider( 3981): match 2:Elapsed time : 2.956 ms
V/[CarMode](10935): [DLApplication]-savePreviousGpsState: Previous state = 0
I/SA      (11009): [SCU] isHaveSA() - false
D/TP/SmsProvider( 3981): query,matched:2, calling pid = 10935
I/SA      (11009): [TPM] getModelProperty : null
I/SA      (11009): [TPM] getCSCProperty : null
D/[CarModeFW](10935): ContactDataHandler-getFavoriteContactList : cur len = 0
D/[CarModeFW](10935): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => execute time : 23
D/[CarModeFW](10935): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => execute time : 16
D/TP/SmsProvider( 3981): match 2:Elapsed time : 4.267 ms
D/[CarMode](10935): [DLApplication]-GooglePlayServices SUCCESS.
E/[CarMode](10935): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
D/[CarModeFW](10935): ContactDataHandler-getFavoriteContactList : cur len = 0
D/[CarModeFW](10935): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 19
D/MessageDataHandler(10935):  getInboxList smsCursor : 24
D/[CarModeFW](10935): LocationDataHandler-No schedules found.
I/[CarMode](10935): [[DLUncaughtExceptionHandler]]-setDLUncaughtExceptionHandler
E/[CarMode](10935): [[DLUncaughtExceptionHandler]]-DLUncaughtExceptionHandler is created!
D/[CarModeFW](10935): MyPlaceProvider-Provider uri: content://com.samsung.android.internal.intelligence.useranalysis/place
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/TP/MmsProvider( 3981): Query uri=content://mms/inbox, match=2, calling pid = 10935
D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/Zygote  (11037): MountEmulatedStorage()
I/libpersona(11037): KNOX_SDCARD checking this for 10003
E/Zygote  (11037): v2
I/libpersona(11037): KNOX_SDCARD not a persona
I/SELinux (11037): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11037): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11037): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=11037 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
I/SA      (11009): [PMR] Received action : android.intent.action.PACKAGE_ADDED
D/TP/MmsProvider( 3981): Query uri=content://mms, match=0, calling pid = 10935
W/GAV2    (10723): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/AndroidRuntime(11003): 
D/AndroidRuntime(11003): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/SA      (11009): [DM] init START
I/UpdateManagerReceiver(10935): Intent : android.intent.action.PACKAGE_ADDEDMon Mar 07 20:29:34 GMT+01:00 2016
D/AndroidRuntime(11003): CheckJNI is OFF
D/AndroidRuntime(11003): readGMSProperty: start
D/AndroidRuntime(11003): readGMSProperty: already setted!!
D/DialogFlow(10935): initQueue()
D/MessageDataHandler(10935):  getInboxList mmsCursor : 33
D/AndroidRuntime(11003): readGMSProperty: end
D/AndroidRuntime(11003): addProductProperty: start
I/SA      (11009): [DM] This device is not a Vodafone
I/ActivityManager( 3523): Killing 10260:com.sec.knox.knoxsetupwizardclient/1000 (adj 13): bgCount ##31
I/SA      (11009): checkReactivationActive for LOLLIPOP
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
I/SA      (11009): checkReactivationActive for reactiveActive
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
I/SA      (11009): setSupportRL : true
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
I/MessageDataHandler(10935): getUnreadMessageCount :0
D/[CarModeFW](10935): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => execute time : 68
D/TimaKeyStoreProvider(11037): TimaSignature is unavailable
I/SA      (11009): [SCU] isHaveSA() - false
I/SA      (11009): support phone number id : false
I/SA      (11009): [DM] init END
I/SA      (11009): [SUR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
D/ActivityThread(11037): Added TimaKeyStore provider
I/SA      (11009): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10680 extra.user_handle.:0 ]
E/Zygote  (11058): MountEmulatedStorage()
I/libpersona(11058): KNOX_SDCARD checking this for 1000
E/Zygote  (11058): v2
I/libpersona(11058): KNOX_SDCARD not a persona
I/SELinux (11058): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3523): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=11058 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (11058): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11058): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Killing 10382:com.sec.providers.settingsearch/u0a181 (adj 13): bgCount ##31
I/ActivityManager( 3523): Killing 10280:com.google.android.apps.plus/u0a147 (adj 15): bgCount ##32
D/TimaKeyStoreProvider(11058): TimaSignature is unavailable
I/ActivityManager( 3523): Killing 9601:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
D/ActivityThread(11058): Added TimaKeyStore provider
E/AffinityControl(11003): AffinityControl: registerfunction enter
D/AndroidRuntime(11003): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3523): inState():  stateMachine is null !!
I/PersonaManagerService( 3523): PersonaId don't exist
I/ActivityManager( 3523): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3523): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService( 3523): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3523  pkgName : ACTIVITY_RESUME_BOOSTER@2
I/art     ( 3523): Explicit concurrent mark sweep GC freed 218517(14MB) AllocSpace objects, 3(3MB) LOS objects, 24% free, 48MB/64MB, paused 1.694ms total 109.363ms
D/WifiService( 3523): New client listening to asynchronous messages
W/ActivityManager( 3523): mDVFSHelper.acquire()
D/ResourcesManager(11037): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
D/UserAnalysis.PlaceProvider(11037): PlaceProvider onCreate()
I/SurfaceFlinger( 2850): id=13 createSurf (1x1),1 flag=404, uhalitest
D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/DBG_DM  ( 6250): [com.wssyncmldm.ui.XUIInstallConfirmActivity(394/onUserLeaveHint)] 
D/UserAnalysis.SecureDbManager(11037): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper(11037): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(11037): Create SecureDbHelper
I/DBG_DM  ( 6250): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 18
I/DBG_DM  ( 6250): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/AndroidRuntime(11003): Shutting down VM
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 6250): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6250): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 6250): [com.wssyncmldm.ui.XUIInstallConfirmActivity(399/onUserLeaveHint)] Home Key!!
I/DBG_DM  ( 6250): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
I/DBG_DM  ( 6250): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
E/Zygote  (11088): MountEmulatedStorage()
E/Zygote  (11088): v2
I/libpersona(11088): KNOX_SDCARD checking this for 10046
I/libpersona(11088): KNOX_SDCARD not a persona
I/SELinux (11088): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11088): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11088): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.samsung.android.app.pinboard:sync for broadcast com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayReceiver: pid=11088 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 9617:com.android.calendar/u0a164 (adj 15): bgCount ##31
D/MessageDataHandler(10935):  getInboxList mms,sms cursor join : 214
D/IntelligenceServiceApplication(11037): onCreate()
W/fb4a(:<default>):UserScope(10846): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11088): TimaSignature is unavailable
D/TP/MmsSmsProvider( 3981): query,matched:0, calling pid = 10935
D/ActivityThread(11088): Added TimaKeyStore provider
V/TP/MmsSmsProvider( 3981): getSimpleConversations entered.
D/TP/MmsSmsProvider( 3981): match 0:Elapsed time : 1.452 ms
D/ResourcesManager(11058): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
I/DBG_DM  ( 6250): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
W/fb4a(:<default>):UserScope(10846): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/DBG_DM  ( 6250): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
D/LightsService( 3523): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3523) 
D/TP/MmsSmsProvider( 3981): query,matched:13, calling pid = 10935
D/LightsService( 3523): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 3523): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 3523): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/TP/MmsSmsProvider( 3981): match 13:Elapsed time : 1.344 ms
D/PersonaManager( 3693): isKioskContainerExistOnDevice
D/PersonaManager( 3693): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3693): Icon Only
D/SecContentProvider2( 3523): uri = 14 selection = getSealedState
D/SecContentProvider2( 3523): mCursor = null
D/ResourcesManager(11088): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
W/ResourcesManager(11088): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11088): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(11088): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ApplicationPolicy( 3523): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/WindowManager( 3523): showStatusBarByNotification() mOpenByNotification=false
I/DBG_DM  ( 6250): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
I/StatusBar( 3693): Icon Only
D/PanelView( 3693): There is/are notification(s) 
I/DBG_DM  ( 6250): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
I/DBG_DM  ( 6250): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
W/ContextImpl(11058): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
D/PanelView( 3693): There is/are notification(s) 
I/System.out(10963): INFO:Resource not found:/Common.properties Using default values
D/PersonaManager( 3693): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3693): Icon Only
I/StatusBar( 3693): Icon Only
D/PanelView( 3693): There is/are notification(s) 
D/MessageDataHandler(10935):  getInboxList address cursor : 28
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11058): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/fb4a(:<default>):UserScope(10846): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
E/FilterInstaller(11058): installFilters
E/Minikin (11088): addFont failed to create font /system/fonts/SamsungSans-light.ttf
E/Zygote  (11112): MountEmulatedStorage()
E/Zygote  (11112): v2
I/libpersona(11112): KNOX_SDCARD checking this for 10121
I/libpersona(11112): KNOX_SDCARD not a persona
I/SELinux (11112): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11112): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11112): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/FilterInstaller(11058): There is no requred permission
I/ActivityManager( 3523): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=11112 uid=10121 gids={50121, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/DBG_DM  ( 6250): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
I/RelayReceiver_PinBoard(11088): onReceive... android.intent.action.PACKAGE_ADDED
E/Zygote  (11126): MountEmulatedStorage()
E/Zygote  (11126): v2
I/libpersona(11126): KNOX_SDCARD checking this for 10680
I/WifiStateMachine( 3523): CMD_RSSI_POLL : calculateWifiScore in!
I/libpersona(11126): KNOX_SDCARD not a persona
D/TimaKeyStoreProvider(11112): TimaSignature is unavailable
I/WifiStateMachine( 3523): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3523): CMD_RSSI_POLL : out!
I/SELinux (11126): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ActivityThread(11112): Added TimaKeyStore provider
I/SELinux (11126): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3523): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11126 uid=10680 gids={50680, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (11126): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/KnoxNotification( 3693): ----- inflateViews : modified publicViewLocal -----
I/Icing   ( 4820): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
I/ActivityManager( 3523): Killing 10496:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##31
D/[CarModeFW](10935): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW](10935): MyPlaceProvider-=============
D/[CarModeFW](10935): MyPlaceProvider-=============
D/[CarModeFW](10935): MyPlaceProvider-=============
D/[CarModeFW](10935): MyPlaceProvider-=============
D/[CarModeFW](10935): MyPlaceProvider-=============
D/[CarModeFW](10935): MyPlaceProvider-=============
D/[CarModeFW](10935): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW](10935): MyPlaceProvider-==============
D/[CarModeFW](10935): MyPlaceProvider-==============
D/[CarModeFW](10935): MyPlaceProvider-==============
D/[CarModeFW](10935): MyPlaceProvider-==============
D/[CarModeFW](10935): MyPlaceProvider-==============
D/KnoxNotification( 3693): ----- inflateViews : modified KnoxViewLocal -----
D/TP/MmsSmsProvider( 3981): query,matched:0, calling pid = 10935
V/TP/MmsSmsProvider( 3981): getSimpleConversations entered.
D/PersonaManager( 3693): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 3693): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@268a68d4
D/PersonaManager( 3693): isKioskContainerExistOnDevice
D/PersonaManager( 3693): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3693): Icon Only
D/TP/MmsSmsProvider( 3981): match 0:Elapsed time : 2.381 ms
I/RelayService_PinBoard(11088): RelayService Started!! : android.intent.action.PACKAGE_ADDED
D/TimaKeyStoreProvider(11126): TimaSignature is unavailable
D/ActivityThread(11126): Added TimaKeyStore provider
D/[CarModeFW](10935): DestinationAvailableTableHandler-sql: select dest_name from tb_destination_list_available where ((1457378975273 - dest_date ) / 360000 ) <= 24 ORDER BY dest_date DESC LIMIT 100
V/ActivityManager( 3523): Display changed displayId=0
E/[CarModeFW](10935): DestinationAvailableTableHandler-insert FAIL!
E/DestinationList(10935): loadLocationDestinationList is null
D/[CarModeFW](10935): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => execute time : 386
E/JavaBinder( 3523): !!! FAILED BINDER TRANSACTION !!!
D/ResourcesManager(11112): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
W/DisplayManagerService( 3523): Failed to notify process 10496 that displays changed, assuming it died.
W/DisplayManagerService( 3523): android.os.TransactionTooLargeException
W/DisplayManagerService( 3523): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService( 3523): 	at android.os.BinderProxy.transact(Binder.java:496)
W/DisplayManagerService( 3523): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService( 3523): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1329)
W/DisplayManagerService( 3523): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1132)
W/DisplayManagerService( 3523): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:138)
W/DisplayManagerService( 3523): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1262)
W/DisplayManagerService( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/DisplayManagerService( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService( 3523): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/StatusBar( 3693): Icon Only
D/PanelView( 3693): There is/are notification(s) 
D/PanelView( 3693): There is/are notification(s) 
D/PersonaManager( 3693): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3693): Icon Only
I/StatusBar( 3693): Icon Only
D/PanelView( 3693): There is/are notification(s) 
D/MessageDataHandler(10935):  getInboxList thread cursor : 93
D/PanelView( 3693): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
D/PackageIntentReceiver(11112): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver(11112): Not GearManger package! 
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
V/xAnalytics(10846): java/com/facebook/xanalytics/jni/XAnalyticsNative.cpp - jint JNI_OnLoad(JavaVM*, void*)
V/xAnalytics(10846): JNI_OnLoad XAnalyticsNative entered
V/xAnalytics(10846): JNI_OnLoad XAnalyticsNative complete
V/xAnalytics(10846): tigon: 0x0 - xanalytics: 0xffffffff93714220
D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
V/xAnalytics(10846): xplat/fbacore/fbacore/FbaBeaconLogger.cpp - void facebook::xanalytics::FbaBeaconLogger::init(const string&, const string&, uint32_t) 0 0
V/xAnalytics(10846): xplat/fbacore/fbacore/FbaBeaconLogger.cpp - void facebook::xanalytics::FbaBeaconLogger::init(const string&, const string&, uint32_t) 0 0
W/art     (10846): Attempt to remove local handle scope entry from IRT, ignoring
D/ResourcesManager(11126): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
E/Zygote  (11149): MountEmulatedStorage()
E/Zygote  (11149): v2
I/libpersona(11149): KNOX_SDCARD checking this for 1000
I/libpersona(11149): KNOX_SDCARD not a persona
I/SELinux (11149): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3523): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=11149 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ResourcesManager( 4820): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SELinux (11149): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11149): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Killing 10534:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##31
D/MessageDataHandler(10935):  thread, addr result: 33
D/hwcutils( 2850): MppFactory::MppFactory()
D/        ( 2850): virtual LibMpp* MppFactory::CreateMpp(int, int, int, int) dev(4) mode(0) drm(0), 
I/[CarModeFW](10935): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxList() : 447
I/[CarModeFW](10935): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW](10935): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => execute time : 447
,D/libexynosgscaler( 2850): LibMpp::LibMpp()
,I/Icing   ( 4820): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
,D/TimaKeyStoreProvider(11149): TimaSignature is unavailable
D/ActivityThread(11149): Added TimaKeyStore provider
,D/ResourcesManager(11149): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/PanelView( 3693): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/WebViewFactory(11126): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11126): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,E/Zygote  (11166): MountEmulatedStorage()
E/Zygote  (11166): v2
I/libpersona(11166): KNOX_SDCARD checking this for 1000
I/libpersona(11166): KNOX_SDCARD not a persona
,I/SELinux (11166): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11166): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11166): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=11166 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 9217:com.sec.android.widgetapp.locationwidget/u0a22 (adj 15): bgCount ##31
,I/LibraryLoader(11126): Loading: webviewchromium
,I/LibraryLoader(11126): Time to load native libraries: 3 ms (timestamps 12-15)
I/LibraryLoader(11126): Expected native library version number "",actual native library version number ""
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8779(373KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 735us total 14.038ms
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(11166): TimaSignature is unavailable
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 265us total 10.040ms
,D/ActivityThread(11166): Added TimaKeyStore provider
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 568us total 9.324ms
,I/Icing   ( 4820): Indexing 5F814D61A0DCF2E8041D271E5054F7C0773240D3 from com.google.android.googlequicksearchbox
,E/Zygote  (11184): MountEmulatedStorage()
E/Zygote  (11184): v2
I/libpersona(11184): KNOX_SDCARD checking this for 10110
I/libpersona(11184): KNOX_SDCARD not a persona
,I/SELinux (11184): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11184): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.oxygen.appmanager.common.packages.PackageReceiver: pid=11184 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11184): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Killing 10395:com.google.android.gm/u0a122 (adj 15): bgCount ##31
,D/ResourcesManager(11166): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/WebViewChromiumFactoryProvider(11126): Binding Chromium to main looper Looper (main, tid 1) {3d8b68b1}
,I/LibraryLoader(11126): Expected native library version number "",actual native library version number ""
I/chromium(11126): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/TimaKeyStoreProvider(11184): TimaSignature is unavailable
,D/ActivityThread(11184): Added TimaKeyStore provider
,I/BrowserStartupController(11126): Initializing chromium process, renderers=0
,W/art     (11126): Attempt to remove local handle scope entry from IRT, ignoring
,D/AppStateLogger(10846): Successfully dumped app state to log file
,D/ResourcesManager(11184): creating new AssetManager and set to /data/app/com.facebook.appmanager-1/base.apk
,D/AcmsPackageEventListener(11166): Received: android.intent.action.PACKAGE_ADDED
,W/chromium(11126): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11126): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11126): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/ContextImpl(11166): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11226): MountEmulatedStorage()
E/Zygote  (11226): v2
I/libpersona(11226): KNOX_SDCARD checking this for 10147
I/libpersona(11226): KNOX_SDCARD not a persona
,I/SELinux (11226): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11226): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11226): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=11226 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 10449:com.google.android.music:main/u0a135 (adj 15): bgCount ##31
E/lowmemorykiller( 2827): Error writing /proc/10449/oom_score_adj; errno=22
D/AcmsService(11166): Enter Oncreate
D/AcmsServiceMonitor(11166): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService(11166): creating AcmsCore
D/AcmsCore(11166): AcmsCore.getAcmsCore() - Enter
D/AcmsCore(11166): AcmsCore
D/AcmsCore(11166): init
D/AcmsCore(11166): Looper handler is not null
D/AcmsCore(11166): Post to AcmsCoreHandler
D/AcmsServiceMonitor(11166): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(11166): Incrementing - Counter value: 1
D/AcmsCore(11166): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService(11166): onStartCommand
D/AcmsService(11166): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor(11166): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor(11166): Incrementing - Counter value: 2
D/AcmsService(11166): Incremented Counter Value : onStartCommand
D/AcmsCertificateMngr(11166): AcmsCertificateMngr
D/AcmsRevocationMngr(11166): AcmsRevocationMngr
D/ActivityThread(11166): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/TimaKeyStoreProvider(11226): TimaSignature is unavailable
D/ActivityThread(11226): Added TimaKeyStore provider
,I/Icing   ( 4820): Indexing done 5F814D61A0DCF2E8041D271E5054F7C0773240D3
,W/chromium(11126): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,D/ResourcesManager(11226): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/chromium(11126): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/ResourcesManager(11226): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AcmsService(11166): Inside handle Intent
D/AcmsService(11166): App added - package name: com.test.thalitest
D/AcmsCore(11166): Post to AcmsCoreHandler
D/AcmsServiceMonitor(11166): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(11166): Incrementing - Counter value: 3
D/AcmsCore(11166): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService(11166): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor(11166): Decrementing - Counter value: 2
,W/art     (11126): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11126): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11126): CordovaWebView is running on device made by: samsung
W/art     (11126): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11126): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11126): performCreate Call secproduct feature valuefalse
D/Activity(11126): performCreate Call debug elastic valuetrue
,V/fb-UnpackingSoSource(11184): locked dso store /data/data/com.facebook.appmanager/lib-main
,I/fb-UnpackingSoSource(11184): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-main
V/fb-UnpackingSoSource(11184): releasing dso store lock for /data/data/com.facebook.appmanager/lib-main
V/fb-UnpackingSoSource(11184): locked dso store /data/data/com.facebook.appmanager/lib-assets
I/fb-UnpackingSoSource(11184): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-assets
V/fb-UnpackingSoSource(11184): releasing dso store lock for /data/data/com.facebook.appmanager/lib-assets
,V/fb-UnpackingSoSource(11184): locked dso store /data/data/com.facebook.appmanager/lib-xzs
I/fb-UnpackingSoSource(11184): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-xzs
V/fb-UnpackingSoSource(11184): releasing dso store lock for /data/data/com.facebook.appmanager/lib-xzs
,D/ACRA    (11184): ACRA is enabled for com.facebook.appmanager, intializing...
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/DexLibLoader(11184): DLL.loadAll betaBuild:true flags:0x00000001
,V/dalvik-internals(11184): hooked _ZN3art12FaultManager35EnsureArtActionInFrontOfSignalChainEv using jump ()
V/dalvik-internals(11184): hooked signal using trap ()
V/dalvik-internals(11184): hooked sysv_signal using trap ()
V/dalvik-internals(11184): hooked bsd_signal using trap ()
V/dalvik-internals(11184): hooked sigaction using jump ()
,V/DexLibLoader(11184): opening dex store /data/data/com.facebook.appmanager/dex
,V/DexLibLoader(11184): Secondary program dex metadata: [classes2.dex 810147d6f366c39a471d8dcf6e02fd5ad5c640fa secondary.dex01.Canary]
,V/DexLibLoader(11184): read status:9 check:faceb007faceb00e
V/DexLibLoader(11184): read saved dep file /data/data/com.facebook.appmanager/dex/deps (176 bytes)
V/DexLibLoader(11184): verified deps file
I/DexLibLoader(11184): current scheme: com.facebook.common.dextricks.OdexSchemeNoop next step: LA_LOAD_EXISTING
,V/MultiDexClassLoader(11184): installing MultiDexClassLoader before application classloader
,D/MultiDexClassLoader(11184): Found primary dex /data/app/com.facebook.appmanager-1/base.apk
D/MultiDexClassLoader(11184): Setup multi dex took 0 ms.
V/DexLibLoader(11184): optimization needed: no
,D/OpenGLRenderer(11126): Render dirty regions requested: true
,D/ActivityManager( 3523): post active user change for 0
D/KnoxTimeoutHandler( 3523): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3523): handleActiveUserChange for user 0
,I/GMPM    (11184): App measurement is starting up
,W/cn      (11184): Verify
E/GMPM    (11184): getGoogleAppId failed with status: 10
,E/GMPM    (11184): Uploading is not possible. App measurement disabled
,I/SurfaceFlinger( 2850): id=14 createSurf (1x1),1 flag=404, NainActivit
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/OpenGLRenderer(11126): Initialized EGL, version 1.4
,I/OpenGLRenderer(11126): HWUI protection enabled for context ,  &this =0xaf945060 ,&mEglDisplay = 1 , &mEglConfig = -1279827696 
,D/OpenGLRenderer(11126): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11126): Enabling debug mode 0
,D/mali_winsys(11126): new_window_surface returns 0x3000,  [1440x2560]-format:1
,E/Zygote  (11282): MountEmulatedStorage()
E/Zygote  (11282): v2
I/libpersona(11282): KNOX_SDCARD checking this for 10013
I/libpersona(11282): KNOX_SDCARD not a persona
,I/SELinux (11282): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11282): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11282): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=11282 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/appmanager(:<default>):LightSharedPreferencesImpl(11184): Failed to load preference file from Disk!
W/appmanager(:<default>):LightSharedPreferencesImpl(11184): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/appmanager(:<default>):LightSharedPreferencesImpl(11184): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/appmanager(:<default>):LightSharedPreferencesImpl(11184): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/appmanager(:<default>):LightSharedPreferencesImpl(11184): 	at com.facebook.crudolib.d.k.a(LightSharedPreferencesStorage.java:56)
W/appmanager(:<default>):LightSharedPreferencesImpl(11184): 	at com.facebook.crudolib.d.g.run(LightSharedPreferencesImpl.java:61)
W/appmanager(:<default>):LightSharedPreferencesImpl(11184): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/appmanager(:<default>):LightSharedPreferencesImpl(11184): 	at com.facebook.common.executors.dt.run(WrappingExecutorService.java:77)
W/appmanager(:<default>):LightSharedPreferencesImpl(11184): 	at com.facebook.common.executors.aa.run(DefaultConstrainedListeningExecutorService.java:327)
W/appmanager(:<default>):LightSharedPreferencesImpl(11184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/appmanager(:<default>):LightSharedPreferencesImpl(11184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/appmanager(:<default>):LightSharedPreferencesImpl(11184): 	at com.facebook.common.executors.cs.run(NamedThreadFactory.java:42)
W/appmanager(:<default>):LightSharedPreferencesImpl(11184): 	at java.lang.Thread.run(Thread.java:818)
W/appmanager(:<default>):LightSharedPreferencesImpl(11184): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/appmanager(:<default>):LightSharedPreferencesImpl(11184): 	at libcore.io.Posix.open(Native Method)
W/appmanager(:<default>):LightSharedPreferencesImpl(11184): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/appmanager(:<default>):LightSharedPreferencesImpl(11184): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/appmanager(:<default>):LightSharedPreferencesImpl(11184): 	... 10 more
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
,W/appmanager(:<default>):b(11184): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(11184): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(11282): TimaSignature is unavailable
,D/ActivityThread(11282): Added TimaKeyStore provider
,D/libexynosgscaler( 2850): virtual CGscaler::~CGscaler()
D/libexynosgscaler( 2850): virtual LibMpp::~LibMpp()
D/        ( 2850): virtual MppFactory::~MppFactory()
,D/ResourcesManager(11282): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/InputMethodManagerService( 3523): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,V/GLSActivity( 4638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/GLSActivity( 4638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/appmanager(:<default>):QuickExperimentControllerImpl(11184): Exposure of experiment com.facebook.http.g.c@384d71c0 occurred when no user was logged in
,I/ActivityManager( 3523): Displayed com.test.thalitest/.MainActivity: +668ms
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/art     (11184): Rejecting re-init on previously-failed class java.lang.Class<com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper>
,I/art     (11184): Rejecting re-init on previously-failed class java.lang.Class<com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper>
,E/Zygote  (11320): MountEmulatedStorage()
E/Zygote  (11320): v2
I/libpersona(11320): KNOX_SDCARD checking this for 10160
I/libpersona(11320): KNOX_SDCARD not a persona
,I/SELinux (11320): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/Timeline(11126): Timeline: Activity_idle id: android.os.BinderProxy@2af60d1f time:70485
,I/SELinux (11320): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11320): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=11320 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,I/System.out(11184): Thread-1572(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11184): Thread-1572(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11184): Thread-1572(ApacheHTTPLog):isShipBuild true
I/System.out(11184): Thread-1572(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 10110
,D/TimaKeyStoreProvider(11320): TimaSignature is unavailable
,D/ActivityThread(11320): Added TimaKeyStore provider
,D/ResourcesManager(11320): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager(11320): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(11320): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11320): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/JsMessageQueue(11126): Set native->JS mode to OnlineEventsBridgeMode
,V/Common  (11320): getScreenSize 1440 2560
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/chromium(11126): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11126): 
,E/Zygote  (11348): MountEmulatedStorage()
E/Zygote  (11348): v2
I/libpersona(11348): KNOX_SDCARD checking this for 10160
I/libpersona(11348): KNOX_SDCARD not a persona
,I/SELinux (11348): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11348): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3523): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=11348 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,E/SELinux (11348): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SurfaceFlinger( 2850): id=11 Removed YUIInstallC (4/9)
I/SurfaceFlinger( 2850): id=11 Removed YUIInstallC (-2/9)
I/JAM     (11320): Load The ApaService JNI
I/JAM     (11320): version: ProfessionalAudio_v1.0.b5
I/JAM     (11320): Try v1.0.b3 ...
D/Spen    (11320): SpenSdk version level = 55
D/Spen    (11320): SpenSdk jar version = 3.0.243
,D/Spen    (11320): SpenSdk apk version = 3.0.235
D/CustomFrequencyManagerService( 3523): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3523  tag : ACTIVITY_RESUME_BOOSTER@2
D/Spen    (11320): Server UPDATE Check
W/ActivityManager( 3523): mDVFSHelper.release()
W/linker  (11320): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
I/Timeline( 3523): Timeline: Activity_windows_visible id: ActivityRecord{2d736df1 u0 com.test.thalitest/.MainActivity t28} time:70607
D/SPenError(11320): JNI_OnLoad
,D/JNI_Bitmap(11320): Init .. Done
D/SPenSpiDecoder(11320): JNI_OnLoad .. Done
D/SPenError(11320): JNI_OnLoad Success
D/PluginManager(11320): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
D/PluginManager(11320): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
D/Init_SPenSdk_Jni(11320): JNI_OnLoad
,D/Init_SPenSdk_Jni(11320): AndroidSDK: 21
D/Init_SPenSdk_Jni(11320): JNI_OnLoad .. Done
,D/CustomFrequencyManagerService( 3523): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3523  pkgName : ACTIVITY_RESUME_BOOSTER@6
,D/Model_ObjectBase_Jni(11320): JNI_OnLoad .. Done
,D/Model_ObjectStroke_Jni(11320): JNI_OnLoad .. Done
D/Model_ObjectImage_Jni(11320): JNI_OnLoad .. Done
D/Model_ObjectText_Jni(11320): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni(11320): JNI_OnLoad .. Done
,D/Model_PageDoc_Jni(11320): JNI_OnLoad .. Done
,D/Model_NoteDoc_Jni(11320): check build type eng[0]
,D/Model_NoteDoc_Jni(11320): JNI_OnLoad .. Done
D/Model_NoteFile_Jni(11320): JNI_OnLoad .. Done
D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/Model_ObjectUtil_Jni(11320): JNI_OnLoad .. Done
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/Model   (11320): OnLoad class Done
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/TimaKeyStoreProvider(11348): TimaSignature is unavailable
,D/ActivityThread(11348): Added TimaKeyStore provider
,D/spe_log (11320): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
,D/SPen_Library(11320): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(11320): Canvas JNI_OnLoad enter!!
,D/SPen_Library(11320): Canvas JNI_OnLoad Success
D/SPen_Library(11320): TextView JNI_OnLoad enter!!
,D/SPen_Library(11320): TextView JNI_OnLoad Success
D/SPen_Library(11320): Text JNI_OnLoad enter!!
D/SPen_Library(11320): Text JNI_OnLoad Success
D/SPen_Library(11320): FontManager JNI_OnLoad enter!!
D/SPen_Library(11320): FontManager JNI_OnLoad Success
D/SPen_Library(11320): CapturePage JNI_OnLoad enter!!
D/SPen_Library(11320): CapturePage JNI_OnLoad Success
D/SPen_Library(11320): Multi JNI_OnLoad enter!!
,D/SPen_Library(11320): Multi JNI_OnLoad Success
D/SPen_Library(11320): Draw Engine JNI_OnLoad Success
D/ResourcesManager(11348): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/SPen_Library(11320): Brush JNI_OnLoad enter!!
,D/SPen_Library(11320): Brush JNI_OnLoad Success
,W/ResourcesManager(11348): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(11348): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11348): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/SPen_Library(11320): ChineseBrush JNI_OnLoad enter!!
,D/SPen_Library(11320): ChineseBrush JNI_OnLoad Success
,D/SPen_Library(11320): InkPen JNI_OnLoad enter!!
,D/SPen_Library(11320): InkPen JNI_OnLoad Success
,D/SPen_Library(11320): Marker JNI_OnLoad enter!!
,D/SPen_Library(11320): Marker JNI_OnLoad Success
,D/SPen_Library(11320): Pencil JNI_OnLoad enter!!
,D/SPen_Library(11320): Pencil JNI_OnLoad Success
,D/SPen_Library(11320): NativePen JNI_OnLoad enter!!
D/SPen_Library(11320): NativePen JNI_OnLoad Success
,I/SurfaceFlinger( 2850): id=13 Removed uhalitest (6/8)
I/SurfaceFlinger( 2850): id=13 Removed uhalitest (-2/8)
,D/SPen_Library(11320): MontblancFountainPen JNI_OnLoad enter!!
,D/SPen_Library(11320): MontblancFountainPen JNI_OnLoad Success
,D/SPen_Library(11320): MontblancCalligraphyPen JNI_OnLoad enter!!
,D/SPen_Library(11320): MontblancCalligraphyPen JNI_OnLoad Success
,D/SPen_Library(11320): MagicPen JNI_OnLoad enter!!
,D/SPen_Library(11320): MagicPen JNI_OnLoad Success
,D/jxcore_app_log(11126): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1362667136
,D/SPen_Library(11320): ObliquePen JNI_OnLoad enter!!
,D/SPen_Library(11320): ObliquePen JNI_OnLoad Success
,D/SPen_Library(11320): FountainPen JNI_OnLoad enter!!
,D/SPen_Library(11320): FountainPen JNI_OnLoad Success
D/Spen    (11320): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(11320): SPenSdk_init2
D/Init_SPenSdk(11320): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11126): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11126):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11126):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11126):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11126):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11126): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195857cd added. We now have 1 listener(s)
D/Init_SPenSdk(11320): Total S Pen SDK Directory Size = 0
D/Spen    (11320): initialize complete
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11126): setBluetoothMacAddress: E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11126): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"E0:DB:10:14:E2:C0"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11126): setIdentityString: {"name":"<no peer name>","address":"E0:DB:10:14:E2:C0"}
W/linker  (11320): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11126): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11126): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11126): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11126):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11126):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11126):     - Bluetooth MAC address: E0:DB:10:14:E2:C0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11126):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11126):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11126):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11126):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11126):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11126):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11126): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@120dc7d0 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel(11126): addListener: New listener added - the number of listeners is now 1
,D/WifiService( 3523): New client listening to asynchronous messages
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11126): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11126): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11126): setAdvertiseMode: 1 -> 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11126): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11126): setScanMode: 1 -> 2
,D/SNoteProvider(11348): onCreate enableSnoteSync = true
,D/ResourcesManager(11320): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/SNoteProvider(11348): ===query=== 
,V/Common  (11348): getScreenSize 1440 2560
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11376): MountEmulatedStorage()
E/Zygote  (11376): v2
I/libpersona(11376): KNOX_SDCARD checking this for 10183
I/libpersona(11376): KNOX_SDCARD not a persona
,I/SELinux (11376): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11376): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3523): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=11376 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,E/SELinux (11376): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Killing 10689:com.samsung.android.app.vrsetupwizardstub/u0a63 (adj 15): bgCount ##31
I/ActivityManager( 3523): Killing 10581:com.google.android.gms:car/u0a14 (adj 15): bgCount ##32
,D/TimaKeyStoreProvider(11376): TimaSignature is unavailable
,D/ActivityThread(11376): Added TimaKeyStore provider
,D/SNoteProvider(11348): ===query=== 
,D/ResourcesManager(11376): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,I/chromium(11126): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/SQLiteLog(11376): (284) automatic index on shooting_modes(title_id)
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11397): MountEmulatedStorage()
I/libpersona(11397): KNOX_SDCARD checking this for 10190
E/Zygote  (11397): v2
I/libpersona(11397): KNOX_SDCARD not a persona
,I/SELinux (11397): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11397): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=11397 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,E/SELinux (11397): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Killing 10738:com.facebook.system/u0a10 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11397): TimaSignature is unavailable
,D/ActivityThread(11397): Added TimaKeyStore provider
,D/ResourcesManager(11397): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,I/TapandpayWidget:TanpandpayAppWidgetProvider(11397): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(11397): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,I/TapandpayWidget:Utils(11397): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(11397): Widget is not attached.
,I/splitIntent( 3523): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 3523): Killing 10205:com.sec.android.gallery3d/u0a50 (adj 15): bgCount ##31
,D/BootupListener( 3981): ACTION_DRIVELINK
,D/SettingsProvider( 3523): name = drivelink_navigation
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1001
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
D/BootupListener( 3981): NAVI : com.here.app.maps
,D/SettingsProvider( 3523): name = internet_call_settings_visibility
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1001
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/BootupListener( 3981): intent.getAction() = com.sec.android.automotive.drivelink.NAVIGATION_PACKAGE_NAME
,D/Widget  (11320): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
,D/Widget  (11320): onReceive android.appwidget.action.APPWIDGET_UPDATE
,D/Widget  (11320): widgetUpdate 5
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/CustomFrequencyManagerService( 3523): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3523  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityThread(11184): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out(11184): P[5]_NetworkDispatch1 calls detatch()
,I/ActivityManager( 3523): Killing 9482:com.android.mms/u0a52 (adj 15): bgCount ##31
,D/CountryDetector( 3523): No listener is left
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 22685(1353KB) AllocSpace objects, 0(0B) LOS objects, 23% free, 53MB/69MB, paused 1.311ms total 85.168ms
,W/BroadcastQueue( 3523): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{185b327e u0 ReceiverList{30da3c39 11184 com.facebook.appmanager/10110/u0 remote:1b0abc00}}
,W/BroadcastQueue( 3523): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{185b327e u0 ReceiverList{30da3c39 11184 com.facebook.appmanager/10110/u0 remote:1b0abc00}}
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/BroadcastQueue( 3523): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{2f440b18 u0 ReceiverList{2cd70efb 11184 com.facebook.appmanager/10110/u0 remote:573f88a}}
,W/jxcore-log(11126): Initializing JXcore engine
W/jxcore-log(11126): JXcore engine is ready
,E/auditd  ( 4629): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3523): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3523): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11126): Starting JXcore engine
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11184): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11184): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,W/jxcore-log(11126): Platform android
W/jxcore-log(11126): 
W/jxcore-log(11126): Process ARCH arm
W/jxcore-log(11126): 
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log(11126): JXcore Cordova bridge is ready!
I/jxcore-log(11126): 
,W/jxcore-log(11126): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions(11126): execute: REQUEST_ACCESS_COARSE_LOCATION
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AcmsKeyStoreHelper(11166):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper(11166): Key Store exist
I/AcmsKeyStoreHelper(11166): Hence loading the keystore file
,D/AcmsKeyStoreHelper(11166):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr(11166): getKeyStoreForApplication success 
D/AcmsCore(11166): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor(11166): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(11166): Decrementing - Counter value: 1
D/AcmsCore(11166): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore(11166): This is NOT a valid MirrorLink app
D/AcmsCore(11166): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor(11166): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(11166): Decrementing - Counter value: 0
D/AcmsServiceMonitor(11166): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor(11166): getSvcCounter - Counter value: 0
D/AcmsService(11166): Enter onDestroy
I/AcmsService(11166): cleanUp(): inside service clean up
D/AcmsCore(11166): AcmsCore: inside DeInit
D/AcmsCore(11166): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr(11166): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr(11166): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper(11166): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface(11166): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor(11166): getSvcCounter - Counter value: 0
D/AcmsService(11166): killing acms process
I/Process (11166): Sending signal. PID: 11166 SIG: 9
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3523): Process ACMS.Process (pid 11166)(adj 0) has died(78,1114)
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
V/AlarmManager( 3523): waitForAlarm result :8
D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
I/WifiStateMachine( 3523): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine( 3523): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3523): CMD_RSSI_POLL : out!
E/Watchdog( 3523): !@Sync 2
D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/libencoder( 3523): width= 768, height = 768, colot_type= 6, bit_depth= 8
D/TaskPersister( 3523): removeObsoleteFile: deleting file=27_task_thumbnail.png
D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PersonaManager( 3693): isKioskContainerExistOnDevice
D/PersonaManager( 3693): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3693): Icon Only
I/StatusBar( 3693): Icon Only
D/PanelView( 3693): There is/are notification(s) 
D/PanelView( 3693): There is/are notification(s) 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4301, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:-622, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-772
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PanelView( 3693): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SSRM:n  ( 3523): SIOP:: AP = 360, PST = 330, CUR = -622
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,I/GAV2    (10723): Thread[GAThread,5,main]: No campaign data found.
,W/fb4a(:<default>):UserScope(10846): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,I/art     (10846): Thread[1,tid=10846,WaitingForJniOnLoad,Thread*=0xb4d08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/data/com.facebook.katana/lib-xzs/libomnistore.so"
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/art     (10846): JNI RegisterNativeMethods: attempt to register 0 native methods for com.facebook.compactdisk.DiskCache
,W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching, sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/BroadcastQueue( 3523): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{1afd4451 u0 ReceiverList{ca2f578 10846 com.facebook.katana/10114/u0 remote:3cfa6db}}
,W/BroadcastQueue( 3523): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{1afd4451 u0 ReceiverList{ca2f578 10846 com.facebook.katana/10114/u0 remote:3cfa6db}}
,W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,D/GcOptimizer(10846): Configure for next cold start: disable
,W/BroadcastQueue( 3523): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{d4a1653 u0 ReceiverList{92ba642 10846 com.facebook.katana/10114/u0 remote:2e00d48d}}
,W/fb4a(:<default>):UserScope(10846): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QuickExperimentControllerImpl(10846): Exposure of experiment com.facebook.placetips.gpscore.abtest.GeneratedPlaceTipsGpsMainExperiment@37fab14c occurred when no user was logged in
W/fb4a(:<default>):QuickExperimentControllerImpl(10846): Exposure of experiment com.facebook.placetips.gpscore.abtest.GeneratedPlaceTipsGpsPassiveListenerExperiment@248ad595 occurred when no user was logged in
,W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):QuickExperimentControllerImpl(10846): Exposure of experiment com.facebook.inject.init.GeneratedFbInjectorWeakrefExperiment@f00c5ac occurred when no user was logged in
,W/fb4a(:<default>):UserScope(10846): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):QeInternalImpl(10846): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11499): MountEmulatedStorage()
E/Zygote  (11499): v2
I/libpersona(11499): KNOX_SDCARD checking this for 10082
I/libpersona(11499): KNOX_SDCARD not a persona
,I/SELinux (11499): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11499): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11499): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=11499 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11499): TimaSignature is unavailable
,D/ActivityThread(11499): Added TimaKeyStore provider
,D/ResourcesManager(11499): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider(11499): onCreate
D/BadgeProvider(11499): DatabaseHelper
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.katana/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10846): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.katana/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.katana/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,D/BadgeProvider(11499): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider(11499): sendNotify, [notify] : null
D/BadgeProvider(11499): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider(11499): update, [BadgeCount] : badgecount=0
D/BadgeProvider(11499): update, [UpdateCount] : 1
W/ContextImpl(10846): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.katana/files
,D/Launcher.Model( 3999): reloadBadges entered.
,W/fb4a(:<default>):UserScope(10846): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
V/io.jxcore.node.JXcoreExtension(11126): isBleMultipleAdvertisementSupported: SUPPORTED
I/jxcore-log(11126): BLE multiple advertisement supported
I/jxcore-log(11126): 
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02055d/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,I/jxcore-log(11126): My device name is: samsung-SM-N910C
I/jxcore-log(11126): 
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10846): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,I/System.out(11184): P[5]_NetworkDispatch2 calls detatch()
,I/ActivityManager( 3523): Killing 10708:com.google.android.partnersetup/u0a17 (adj 15): bgCount ##31
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out(11184): P[5]_NetworkDispatch3 calls detatch()
,I/GAV2    (11226): Thread[GAThread,5,main]: No campaign data found.
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3523): Killing 10761:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,I/WifiStateMachine( 3523): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3523): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3523): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:4/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log(11126): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
I/jxcore-log(11126): 
,I/jxcore-log(11126): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11126): 
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log(11126): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11126): 
,I/jxcore-log(11126): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11126): 
,I/jxcore-log(11126): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log(11126): 
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log(11126): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log(11126): 
,I/jxcore-log(11126): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log(11126): 
,I/io.jxcore.node.ConnectivityInfo(11126): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo(11126):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo(11126):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo(11126):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo(11126):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo(11126):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo(11126):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo(11126):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo(11126):     - force notify: true
D/io.jxcore.node.JXcoreExtension(11126): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,I/jxcore-log(11126): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log(11126): 
,I/jxcore-log(11126): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log(11126): 
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PackageManager( 3523): [MSG] MCS_UNBIND
,I/ActivityManager( 3523): Killing 10777:com.sec.android.service.health/u0a19 (adj 15): bgCount ##31
,I/WifiStateMachine( 3523): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3523): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3523): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/PackageManager( 3523): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3523): waitForAlarm result :4
,E/ActivityThread( 4820): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 3523): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 52649, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager( 3523): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 144411, reason: UserStart
,W/ResourceType( 5159): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5159): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log(11126): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log(11126): 
,D/SecContentProvider2( 3523): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3523): mCursor = null
,I/jxcore-log(11126): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log(11126): 
,I/jxcore-log(11126): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log(11126): 
,I/jxcore-log(11126): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log(11126): 
,I/jxcore-log(11126): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log(11126): 
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log(11126): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log(11126): 
,I/jxcore-log(11126): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log(11126): 
,I/jxcore-log(11126): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log(11126): 
,I/jxcore-log(11126): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
I/jxcore-log(11126): 
,I/jxcore-log(11126): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11126): 
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log(11126): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
I/jxcore-log(11126): 
,I/jxcore-log(11126): Unit Test app is loaded
I/jxcore-log(11126): 
,I/jxcore-log(11126): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"on","blueTooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log(11126): 
,I/chromium(11126): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,I/WifiStateMachine( 3523): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3523): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3523): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3523): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10060 pid=3693 (0x0)
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:-445, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:169
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,V/AlarmManager( 3523): waitForAlarm result :4
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SSRM:n  ( 3523): SIOP:: AP = 360, PST = 333, CUR = -445
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3523): Waited long enough for: ServiceRecord{321468c2 u0 com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayService}
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/Finsky  (10331): [1410] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  (10331): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/WifiStateMachine( 3523): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3523): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3523): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3523): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3523): [s] UserActivityState : 1 -> 2
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3523): [s] DisplayPowerCallbacks : onStateChanged()
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3523): lcd : 6 +
,D/lights  ( 3523): lcd : 6 -
,D/lights  ( 3523): lcd : 1 +
,D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3523): lcd : 1 -
,D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3523): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3523): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine( 3523): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3693): applyOpen
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness(),
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,I/WifiStateMachine( 3523): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3523): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine( 3523): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3693): applyOpen
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3523): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3523): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3523): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 3523): !@[ps] Screen__Off - 1 : timeout (0x4) (2)
I/PowerManagerService( 3523): Going to sleep due to screen timeout (uid 1000)...
D/InputManager-JNI( 3523): setDeviceInteractive: 0
D/PowerManagerService( 3523): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 3523): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService( 3523): handleSandman : startDream()
,D/InputManager-JNI( 3523): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/InputManager-JNI( 3523): sysfs_write +: /sys/class/input/event3/device/enabled: 0
E/PowerManagerService( 3523): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 3523): Sleeping (uid 1000)...
D/PowerManagerService( 3523): [s] UserActivityState : 4 -> 0
D/PowerManagerService( 3523): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService( 3523): [input device light] handleInputDeviceLightOff
,D/InputManager-JNI( 3523): sysfs_write -: /sys/class/input/event3/device/enabled: 0
I/SurfaceFlinger( 2850): id=15 createSurf (1440x2560),2 flag=404, DolorFade
,D/InputManager-JNI( 3523): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI( 3523): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI( 3523): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService( 3523): 	.unregisterCallback : 1, client=
D/SContextService( 3523): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@2a3e8a0d, Service = Auto Rotation, used = 1
,W/CAE     ( 3523): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     ( 3523): stop(ContextProvider.java:149)
,V/CAE     ( 3523): clear(AutoRotationRunner.java:182)
,V/CAE     ( 3523): disable(AutoRotationRunner.java:171)
,D/PowerManagerService( 3523): Excessive delay in ColorFade : createSurface: 17ms
I/CAE     ( 3523): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager( 3523): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs( 2868): sendContextData: -78, 7, 0, 0
,D/mali_winsys( 3523): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/CAE     ( 3523): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     ( 3523): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/PowerManagerService( 3523): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 37ms
,D/CAE     ( 3523): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     ( 3523): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     ( 3523): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     ( 3523): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService( 3523): removeSContextService() : service = Auto Rotation
D/SContextService( 3523): ===== SContext Service List =====
D/SContextManager( 3523):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@3d590dd0, service=Auto Rotation
,D/KeyguardViewMediator( 3693): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 3693): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 3693): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 3693): notifyScreenOffLocked
,D/KeyguardViewMediator( 3693): timeout : 5000
,D/PowerManagerService( 3523): Excessive delay in ColorFade : initGLShaders: 40ms
,V/ActivityThread(11126): updateVisibility : ActivityRecord{2fa63c6c token=android.os.BinderProxy@2af60d1f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PowerManagerService( 3523): Excessive delay in ColorFade : draw: 16ms
,D/KeyguardViewMediator( 3693): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 3693): handleNotifyScreenOff
,D/PowerManagerService( 3523): Excessive delay in ColorFade : draw: 12ms
,D/PowerManagerService( 3523): Excessive delay in ColorFade : draw: 15ms
D/PowerManagerService( 3523): Excessive delay in ColorFade prepare: 146ms
D/DisplayPowerController( 3523): ColorFade: onAnimationStart
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3523): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3523): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3523): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3523): lcd : 0 +
,D/lights  ( 3523): lcd : 0 -
,D/LightsService( 3523): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3523) 
D/LightsService( 3523): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService( 3523): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 3523): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager( 3523): unregisterListener ::   
D/lights  ( 3523): led_pattern : 5 +
D/BatteryService( 3523): turn on LED for fully charged
,I/CAE     ( 3523): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     ( 3523): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
D/lights  ( 3523): led_pattern : 5 -
D/LightsService( 3523): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     ( 3523): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager( 3523): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs( 2868): sendContextData: -76, 13, -46, 0
,I/CAE     ( 3523): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 19, 29, 59,
D/SensorHubManager( 3523): SendSensorHubData: send data = -63, 14, 19, 29, 59
D/Sensorhubs( 2868): sendContextData: -63, 14, 19, 29, 59
,D/MotionRecognitionService( 3523):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 3523):  handler : SCREEN_OFF end 
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,D/WifiStateMachine( 3523): backgroundScan enabled=false startBackgroundScanIfNeeded:false
D/NotificationService( 3523): ACTION_SCREEN_OFF
E/WifiStateMachine( 3523): handleScreenStateChanged Exit: false
D/LightsService( 3523): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3523) 
D/LightsService( 3523): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 3523): [SvcLED]  onSensorChanged::light value = 0
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
,D/SensorManager( 3523): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
E/native  ( 3523): do suspend true
,D/SensorManager( 3523): unregisterListener ::   
D/LightsService( 3523): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/AudioHardwareTinyALSA( 2857): setParameters(screen_state=off)
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:-85, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:64
D/BatteryService( 3523): stay LED for fully charged
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/SecExternalDisplayIntents_Java( 3523): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/AutomaticBrightnessController( 3523): mCallbacks.updateBrightness()
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 320, PST = 331, CUR = -85
,D/IpRemoteDisplayController( 3523): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 3523): Bridge Server is not available
,D/DisplayPowerController( 3523): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3523): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/VolumePanel( 3693): registerReceiver: onReceive start 
D/VolumePanel( 3693): registerReceiver ACTION_SCREEN_OFF start
D/VolumePanel( 3693): registerReceiver ACTION_SCREEN_OFF end
D/VolumePanel( 3693): registerReceiver: onReceive end 
,D/VolumePanel( 3693): mCoverBroadcastReceiver: onReceive() start : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
D/VolumePanel( 3693): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 3693): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 3693): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 3693): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/GpsLocationProvider( 3523): receive broadcast intent, action: android.intent.action.SCREEN_OFF
E/GpsLocationProvider( 3523): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:0 ++
E/GpsLocationProvider( 3523): sExerciseIterface is not available
,D/PersonaManagerService( 3523): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 3523): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 3967): call the applyRouting
,D/STATUSBAR-PhoneStatusBar( 3693):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 3693): onReceive : Intent.ACTION_SCREEN_OFF
,D/accuweather( 5318): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 5318): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5318): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/SSRM:n  ( 3523): SIOP:: AP = 320, PST = 330, CUR = -85
,D/DisplayPowerState( 3523): !@ ColorFade entry
D/DisplayPowerController( 3523): ColorFade: onAnimationEnd
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5318): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5318): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5318): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5318): [KK AccuPhone]>>> UIM:311 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/AutomaticBrightnessController( 3523): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,D/AutomaticBrightnessController( 3523): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/AutomaticBrightnessController( 3523): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/Sensors ( 3523): Light old sensor_state 513, new sensor_state : 1 en : 0
,I/AutomaticBrightnessController( 3523): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
I/AutomaticBrightnessController( 3523): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,D/DisplayPowerController( 3523): getFinalBrightness : 0 -> 0
,D/SensorManager( 3523): unregisterListener ::   
I/Sensors ( 3523): Acc old sensor_state 1, new sensor_state : 0 en : 0
D/DisplayPowerController( 3523): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 3523): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3523): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3523): [PWL] sb release: PowerManagerService.Broadcasts
D/DisplayPowerController( 3523): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3523): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 3523): [s] DisplayPowerCallbacks : onStateChanged()
D/SurfaceFlinger( 2850): Set power mode=0, type=0 flinger=0xb6962000
D/PowerManagerService( 3523): [PWL] sb release: PowerManagerService.Display
,I/DisplayManagerService( 3523): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 59.0 fps, supportedRefreshRates [59.0], density 640, 515.154 x 520.192 dpi, appVsyncOff 0, presDeadline 17949152, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager( 3523): Display changed displayId=0
I/hwcomposer( 2850): int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(1)
,D/SensorManager( 3523): unregisterListener ::   
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 5318): [KK AccuPhone]>>> UIM:157 [0:0] make widget 4x1 view!!! 
,D/accuweather( 5318): [KK AccuPhone]>>> UIM:159 [0:0] make widget 4x2 view!!! 
,D/accuweather( 5318): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
,D/accuweather( 5318): [KK AccuPhone]>>> UIM:184 [0:0] get widget 4x2 view!!! wid = 2
,D/accuweather( 5318): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 5318): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 5318): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/SurfaceControl( 3523): Excessive delay in setPowerMode(): 218ms
D/PowerManagerService( 3523): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL( 3523): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 3523): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/PowerManagerService( 3523): [PWL] Off : 0s ago
D/PowerManagerService( 3523): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 220ms
,V/AlarmManager( 3523): waitForAlarm result :8
,W/IdleConnectionHandler(11184): Removing a connection that never existed!
,V/AlarmManager( 3523): waitForAlarm result :4
,V/AlarmManager( 3523): ___SyncScheduler (v3) ACTIVATED___
,D/KeyguardViewMediator( 3693): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 3693): doKeyguard: not showing because lockscreen is off
,V/AlarmManager( 3523): <AppSync3 Whitelist>
,V/AlarmManager( 3523): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PowerManagerService( 3523): [PWL] Off : 5s ago
,V/AlarmManager( 3523): waitForAlarm result :4
,V/GLSActivity( 4638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 4638): Vacuum at: now=1457379004994 tag=VacuumService
,V/xAnalytics(10846): xplat/fbacore/fbacore/XAnalytics.cpp - virtual void facebook::xanalytics::XAnalytics::resumeUploadFromStorage(const string&)
,I/PhenotypeConfigurator( 4638): Scheduling Phenotype for one-off execution 415 seconds from now (1457379005385)
,I/PhenotypeFlagCommitter( 4638): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 4638): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 3523): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 4638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4638): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4638): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4638): Tagging socket 82 with tag 1000040100000000{268436481,0} uid 10014, pid: 4638, getuid(): 10014
,I/qtaguid ( 4638): Tagging socket 85 with tag 1000040100000000{268436481,0} uid 10014, pid: 4638, getuid(): 10014
,I/System.out( 4638): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4638): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4638): Tagging socket 86 with tag 1000120100000000{268440065,0} uid -1, pid: 4638, getuid(): 10014
,I/qtaguid ( 4638): Tagging socket 89 with tag 1000120100000000{268440065,0} uid -1, pid: 4638, getuid(): 10014
,D/LocationManagerService( 3523): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4638): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4638): Tagging socket 86 with tag 1000120100000000{268440065,0} uid -1, pid: 4638, getuid(): 10014
,D/LocationManagerService( 3523): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4638): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4638): Tagging socket 86 with tag 1000120100000000{268440065,0} uid -1, pid: 4638, getuid(): 10014
,D/LocationManagerService( 3523): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4638): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4638): Tagging socket 86 with tag 1000120100000000{268440065,0} uid -1, pid: 4638, getuid(): 10014
,E/Watchdog( 3523): !@Sync 3
,V/AlarmManager( 3523): waitForAlarm result :4
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:132
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 300, PST = 328, CUR = 44
,D/FactoryTest(10149): Not factory mode
,D/FactoryTest(10149): Not factory mode. isFactoryMode() returend false
,D/MTPRx   (10149): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   (10149): still no open session command from host, so toast
,W/ContextImpl(10149): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 android.os.Handler.dispatchMessage:102 
,W/ContextImpl(10149): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1608 android.app.ContextImpl.startActivity:1597 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 
,I/Timeline(10149): Timeline: Activity_launch_request id:com.android.settings time:105222
,E/PersonaManagerService( 3523): inState():  stateMachine is null !!
I/PersonaManagerService( 3523): PersonaId don't exist
,I/ActivityManager( 3523): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager( 3523): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager( 3523): mDVFSHelper.acquire()
,V/ActivityManager( 3523): Display changed displayId=0
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
,D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
,E/MTPRx   (10149): started activity for popup
,D/ResourcesManager(10149): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(10149): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager(10149): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(10149): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(10149): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10149): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10149): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10149): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity(10149): PREF_DONT_ASK_AGAIN : true
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
,D/InputMethodManagerService( 3523): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 3523): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1d3c9eb0 attribute=android.view.inputmethod.EditorInfo@17496129, token = android.os.BinderProxy@48f99a5
,D/SettingsReceiverActivity(10149): dev.kiessupport is : TRUE
,D/Activity(10149): performCreate Call secproduct feature valuefalse
D/Activity(10149): performCreate Call debug elastic valuetrue
,D/ActivityManager( 3523): post active user change for 0
D/KnoxTimeoutHandler( 3523): postActiveUserChange for user 0
,D/KnoxTimeoutHandler( 3523): handleActiveUserChange for user 0
,V/ActivityThread(11126): updateVisibility : ActivityRecord{2fa63c6c token=android.os.BinderProxy@2af60d1f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline(11126): Timeline: Activity_idle id: android.os.BinderProxy@2af60d1f time:105580
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3523): mDVFSHelper.release()
,I/PowerManagerService( 3523): [PWL] Off : 15s ago
,V/AlarmManager( 3523): waitForAlarm result :4
,D/SSRM:n  ( 3523): SIOP:: AP = 290, PST = 323, CUR = 85
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:85, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:98
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3523): waitForAlarm result :4
,D/SSRM:n  ( 3523): SIOP:: AP = 290, PST = 317, CUR = 85
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:92, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:80
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3523): [PWL] Off : 30s ago
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3523): !@Sync 4
,D/SSRM:n  ( 3523): SIOP:: AP = 280, PST = 313, CUR = 92,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:85, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:90
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3523): SIOP:: AP = 280, PST = 310, CUR = 85
,I/PowerManagerService( 3523): [PWL] Off : 50s ago
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:77, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:79
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3523): SIOP:: AP = 280, PST = 304, CUR = 77
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:70, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:60
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3523): waitForAlarm result :8
,E/Watchdog( 3523): !@Sync 5
,D/SSRM:n  ( 3523): SIOP:: AP = 270, PST = 301, CUR = 70
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:63, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3523): [PWL] Off : 75s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 270, PST = 298, CUR = 63
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:58, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:53
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4638): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3523): SIOP:: AP = 270, PST = 292, CUR = 58
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:54, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3523): !@Sync 6
,D/SSRM:n  ( 3523): SIOP:: AP = 270, PST = 283, CUR = 54
,V/AlarmManager( 3523): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager( 3523): waitForAlarm result :4
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:56
D/BatteryService( 3523): stay LED for fully charged
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3523): [PWL] Off : 105s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 270, PST = 280, CUR = 52
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3523): SIOP:: AP = 270, PST = 277, CUR = 49
,V/AlarmManager( 3523): waitForAlarm result :8
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:61
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 7
,D/SSRM:n  ( 3523): SIOP:: AP = 270, PST = 275, CUR = 45
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3523): [PWL] Off : 140s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 270, PST = 273, CUR = 44
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 270, PST = 272, CUR = 42,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3523): !@Sync 8
,D/SSRM:n  ( 3523): SIOP:: AP = 270, PST = 272, CUR = 40
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,D/BatteryService( 3523): stay LED for fully charged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 271, CUR = 39
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3523): [PWL] Off : 180s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 269, CUR = 38
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 9
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 268, CUR = 36,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 267, CUR = 36
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 266, CUR = 36
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3523): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3523): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3523): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3523): initializing...
,I/TLC_TIMA_PKM_initialize( 3523): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 3523): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3523): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 3523): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 3523): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3523): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3523): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 3523): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 3523): device_id = 0x0
,I/TZ: mc_tlc_communication( 3523): tlc_open() was called
I/TZ: mc_tlc_communication( 3523): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3523): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3523): Opening the session
,I/TZ: mc_tlc_communication( 3523): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3523): Trustlet response is completed
,E/Watchdog( 3523): !@Sync 10
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 265, CUR = 36
,I/TLC_TIMA_PKM_measure_kernel( 3523): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3523): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3523): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3523): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3523): [PWL] Off : 225s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 265, CUR = 34
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 264, CUR = 33
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 11
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 264, CUR = 34
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 263, CUR = 34
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 262, CUR = 32
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3523): [PWL] Off : 275s ago
,E/Watchdog( 3523): !@Sync 12
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 262, CUR = 31
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 262, CUR = 30
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3523): waitForAlarm result :8
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 261, CUR = 29
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 13
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 261, CUR = 27,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 27
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3523): [PWL] Off : 330s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 28
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3523): !@Sync 14
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 28
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 27,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 27
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 15
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 26
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 27
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3523): [PWL] Off : 390s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 26
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 16
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 26
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 23
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 23
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 17
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 25
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 24
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 22
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3523): [PWL] Off : 455s ago
,E/Watchdog( 3523): !@Sync 18
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 24
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 22
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 22
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 19
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 23
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 23
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 22
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3523): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 3523): TimaServiceHandler.handleMessage what =1,
,D/TimaService( 3523): TIMA: checkEvent, operation: 50000 subject: 10000,
,E/Watchdog( 3523): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3523): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3523): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3523): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3523): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 21
,W/ProcessCpuTracker( 3523): Skipping unknown process pid 12029
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3523): [PWL] Off : 525s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 20
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3523): Killing 10798:com.sec.pcw.device/1000 (adj 15): bgCount ##31
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 21
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 21
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 20
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 19
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 19
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 22
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 260, CUR = 19
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 259, CUR = 19
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 3523): [PWL] Off : 600s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 259, CUR = 19
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 23
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 259, CUR = 20
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 258, CUR = 18
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 258, CUR = 19
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 24
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 258, CUR = 18
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): setPowerConnected  = true,
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 257, CUR = 18
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 257, CUR = 18
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 25
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 256, CUR = 18,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3523): [PWL] Off : 680s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 256, CUR = 19
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 256, CUR = 17
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3523): !@Sync 26
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 255, CUR = 17
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 255, CUR = 16
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 255, CUR = 17
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 27
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 254, CUR = 16
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 254, CUR = 17
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 254, CUR = 15
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 28
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 253, CUR = 15
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3523): [PWL] Off : 765s ago
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 253, CUR = 16
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 253, CUR = 15
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 29
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 252, CUR = 17
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 252, CUR = 15
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 252, CUR = 14
,D/TimaService( 3523): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3523): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3523): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 3523): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3523): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3523): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3523): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 251, CUR = 13
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 251, CUR = 15,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 251, CUR = 15
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 31
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 14
,I/PowerManagerService( 3523): [PWL] Off : 855s ago
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 32
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 13
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3523): stay LED for fully charged
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 33
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 34
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3523): [PWL] Off : 950s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,E/Watchdog( 3523): !@Sync 35
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 11
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3523): stay LED for fully charged
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 13
,E/Watchdog( 3523): !@Sync 36
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 ,
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 12
,E/Watchdog( 3523): !@Sync 37
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 11
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-15
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 9
,I/art     ( 3523): Background sticky concurrent mark sweep GC freed 112937(10MB) AllocSpace objects, 328(5MB) LOS objects, 12% free, 53MB/61MB, paused 3.664ms total 118.982ms
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3523): [PWL] Off : 1050s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 12
,E/Watchdog( 3523): !@Sync 38
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 11
,F/libc    (11126): Fatal signal 11 (SIGSEGV), code 1, fault addr 0x0 in tid 11372 (Thread-1557)
,I/DEBUG   ( 2847): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
,I/DEBUG   ( 2847): Build fingerprint: 'samsung/treltexx/trelte:5.0.1/LRX22C/N910CXXU1BOE3:user/release-keys'
I/DEBUG   ( 2847): Revision: '21'
I/DEBUG   ( 2847): ABI: 'arm'
,I/DEBUG   ( 2847): pid: 11126, tid: 11372, name: Thread-1557  >>> com.test.thalitest <<<
,I/DEBUG   ( 2847): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
,I/DEBUG   ( 2847):     r0 00000000  r1 939f2464  r2 00000002  r3 00000000
,I/DEBUG   ( 2847):     r4 af87f900  r5 00000000  r6 af87f190  r7 91563000
I/DEBUG   ( 2847):     r8 af8be67c  r9 af87f900  sl af87f168  fp 939f245c
,I/DEBUG   ( 2847):     ip ffffffff  sp 939f244c  lr 94ccdb30  pc 94ccda34  cpsr 60000010
I/DEBUG   ( 2847): 
I/DEBUG   ( 2847): backtrace:
,I/DEBUG   ( 2847):     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
I/DEBUG   ( 2847):     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
I/DEBUG   ( 2847):     #02 pc e5943000  <unknown>
,I/DEBUG   ( 2847): 
I/DEBUG   ( 2847): Tombstone written to: /data/tombstones/tombstone_09
E/        ( 2847): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 11126
,I/BootReceiver( 3523): Copying /data/tombstones/tombstone_09 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 3523): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,W/ActivityManager( 3523):   Force finishing activity com.test.thalitest/.MainActivity
,I/dumpstate(12448): begin
D/FocusedStackFrame( 3523): Set to : 0
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 3523): Killing 8668:com.android.settings/1000 (adj 15): bgCount ##31
,D/CrashAnrDetector( 3523): Build: samsung/treltexx/trelte:5.0.1/LRX22C/N910CXXU1BOE3:user/release-keys
D/CrashAnrDetector( 3523): Hardware: universal5433
D/CrashAnrDetector( 3523): Revision: 21
D/CrashAnrDetector( 3523): Bootloader: N910CXXU1BOE3
D/CrashAnrDetector( 3523): Radio: unknown
D/CrashAnrDetector( 3523): Kernel: Linux version 3.10.9-4915571 (dpi@SWDD6116) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 15 10:42:13 KST 2015
D/CrashAnrDetector( 3523): 
D/CrashAnrDetector( 3523): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 3523): Build fingerprint: 'samsung/treltexx/trelte:5.0.1/LRX22C/N910CXXU1BOE3:user/release-keys'
D/CrashAnrDetector( 3523): Revision: '21'
D/CrashAnrDetector( 3523): ABI: 'arm'
D/CrashAnrDetector( 3523): pid: 11126, tid: 11372, name: Thread-1557  >>> com.test.thalitest <<<
D/CrashAnrDetector( 3523): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
D/CrashAnrDetector( 3523):     r0 00000000  r1 939f2464  r2 00000002  r3 00000000
D/CrashAnrDetector( 3523):     r4 af87f900  r5 00000000  r6 af87f190  r7 91563000
D/CrashAnrDetector( 3523):     r8 af8be67c  r9 af87f900  sl af87f168  fp 939f245c
D/CrashAnrDetector( 3523):     ip ffffffff  sp 939f244c  lr 94ccdb30  pc 94ccda34  cpsr 60000010
D/CrashAnrDetector( 3523):     d0  0000000000000000  d1  0000000000000000
D/CrashAnrDetector( 3523):     d2  0000000000000000  d3  0000000000000000
D/CrashAnrDetector( 3523):     d4  0000000000001614  d5  0000000000000000
D/CrashAnrDetector( 3523):     d6  000000000000002c  d7  0000000000007b45
D/CrashAnrDetector( 3523):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 3523):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 3523):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 3523):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 3523):     d16 000029b8000029b8  d17 000029b800000000
D/CrashAnrDetector( 3523):     d18 0000000000000a1e  d19 000000000000002c
D/CrashAnrDetector( 3523):     d20 0000000000000a4a  d21 0000000000000000
D/CrashAnrDetector( 3523):     d22 ffff000000000000  d23 ffffffffffffffff
D/CrashAnrDetector( 3523):     d24 0080008000800080  d25 0080008000800080
D/CrashAnrDetector( 3523):     d26 0001000000000000  d27 0001000100010001
D/CrashAnrDetector( 3523):     d28 0800080008000800  d29 0800080008000800
D/CrashAnrDetector( 3523):     d30 ffff000000000000  d31 ffffffffffffffff
D/CrashAnrDetector( 3523):     scr 30000011
D/CrashAnrDetector( 3523): 
D/CrashAnrDetector( 3523): backtrace:
D/CrashAnrDetector( 3523):     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
D/CrashAnrDetector( 3523):     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
D/CrashAnrDetector( 3523):     #02 pc e5943000  <unknown>
D/CrashAnrDetector( 3523): 
D/CrashAnrDetector( 3523): stack:
D/CrashAnrDetector( 3523):          939f23cc  00000000  
D/CrashAnrDetector( 3523):          939f23d0  931173e0  
D/CrashAnrDetector( 3523):          939f23d4  af87f900  
D/CrashAnrDetector( 3523):          939f23d8  0000000b  
D/CrashAnrDetector( 3523):          939f23dc  94170480  
D/CrashAnrDetector( 3523):          939f23e0  939f23fc  [stack:11372]
D/CrashAnrDetector( 3523):          939f23e4  94d41904  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::jit::BaselineScript::trace(JSTracer*)+120)
D/CrashAnrDetector( 3523):          939f23e8  00000001  
D/CrashAnrDetector( 3523):          939f23ec  00000000  
D/CrashAnrDetector( 3523):          939f23f0  af880430  
D/CrashAnrDetector( 3523):          939f23f4  00000000  
D/CrashAnrDetector( 3523):          939f23f8  00000000  
D/CrashAnrDetector( 3523):          939f23fc  af87f900  
D/CrashAnrDetector( 3523):          939f2400  af880430  
D/CrashAnrDetector( 3523):          939f2404  95359b60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
D/CrashAnrDetector( 3523):          939f2408  939f2474  [stack:11372]
D/Cr,ashAnrDetector( 3523):          939f240c  94cd4514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
D/CrashAnrDetector( 3523):          939f2410  af87f900  
D/CrashAnrDetector( 3523):          939f2414  af87f168  
D/CrashAnrDetector( 3523):          939f2418  939f8000  /dev/ashmem (deleted)
D/CrashAnrDetector( 3523):          939f241c  939f2440  [stack:11372]
D/CrashAnrDetector( 3523):          939f2420  939f2438  [stack:11372]
D/CrashAnrDetector( 3523):          939f2424  939f2444  [stack:11372]
D/CrashAnrDetector( 3523):          939f2428  952806d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
D/CrashAnrDetector( 3523):          939f242c  939f2448  [stack:11372]
D/CrashAnrDetector( 3523):          939f2430  00000004  
D/CrashAnrDetector( 3523):          939f2434  00000000  
D/CrashAnrDetector( 3523):          939f2438  00000001  
D/CrashAnrDetector( 3523):          939f243c  af87f900  
D/CrashAnrDetector( 3523):          939f2440  8f5d1d60  
D/CrashAnrDetector( 3523):          939f2444  af87f190  
D/CrashAnrDetector( 3523):          939f2448  939f245c  [stack:11372]
D/CrashAnrDetector( 3523):     #00  939f244c  939f245c  [stack:11372]
D/CrashAnrDetector( 3523):          939f2450  939f7808  [stack:11372]
D/CrashAnrDetector( 3523):          939f2454  9155e2a8  
D/CrashAnrDetector( 3523):          939f2458  939f2474  [stack:11372]
D/CrashAnrDetector( 3523):          939f245c  94cd106c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
D/CrashAnrDetector( 3523):     #01  939f2460  af8be67c  
D/CrashAnrDetector( 3523):          939f2464  00000000  
D/CrashAnrDetector( 3523):          939f2468  af87f18c  
D/CrashAnrDetector( 3523):          939f246c  95201cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
D/CrashAnrDetector( 3523):          939f2470  939f24cc  [stack:11372]
D/CrashAnrDetector( 3523):          939f2474  94cd5dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1452)
D/CrashAnrDetector( 3523):          939f2478  00000000  
D/CrashAnrDetector( 3523):          939f247c  939f2494  [stack:11372]
D/CrashAnrDetector( 3523):          939f2480  939
D/CrashAnrDetector( 3523): processName:com.test.thalitest
D/CrashAnrDetector( 3523): broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1713 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,E/Watchdog( 3523): !@Sync 39,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
D/BatteryService( 3523): stay LED for fully charged
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 250, CUR = 4
,W/ActivityManager( 3523): Activity destroy timeout for ActivityRecord{2d736df1 u0 com.test.thalitest/.MainActivity t28 f}
,I/SurfaceFlinger( 2850): id=14 Removed NainActivit (5/8)
,I/dumpstate(12448): waiting for zip started
,I/dumpstate(12448): waiting for zip end
I/dumpstate(12448): done
,I/ActivityManager( 3523): Process com.test.thalitest (pid 11126)(adj 9) has died(214,1114)
,D/WifiService( 3523): Client connection lost with reason: 4
,I/Zygote  ( 2881): Process 11126 exited due to signal (11)
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 10
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/BatteryService( 3523): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 12
,D/TimaService( 3523): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3523): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3523): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 3523): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3523): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3523): Updating Usage Statistics in DB @ 1457380116845
,I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3523): 	at com.android.server,.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.Application,Usage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
,W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
,W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
,W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
,W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	,at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
,W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	,at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
,W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3523): Done Updating Usage Statistics in DB @ 1457380116895
,E/Watchdog( 3523): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3523): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3523): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3523): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3523): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 11
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29,
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 11
,E/Watchdog( 3523): !@Sync 41
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 12,
,I/PowerManagerService( 3523): [PWL] Off : 1155s ago
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 9
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 10
,E/Watchdog( 3523): !@Sync 42
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5579): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 13
,TIME-OUT KILL (timeout was 1200000ms),D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3523): stay LED for fully charged
I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5579): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5579): Disconnected process message: 10
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(12696): 
D/AndroidRuntime(12696): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(12696): CheckJNI is OFF
D/AndroidRuntime(12696): readGMSProperty: start
D/AndroidRuntime(12696): readGMSProperty: already setted!!
D/AndroidRuntime(12696): readGMSProperty: end
D/AndroidRuntime(12696): addProductProperty: start
E/AffinityControl(12696): AffinityControl: registerfunction enter
D/AndroidRuntime(12696): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 3523): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3523): START PACKAGE DELETE: observer{773428168}
D/PackageManager( 3523): pkg{<packageName>}
D/PackageManager( 3523): user{0}
D/PackageManager( 3523): caller{2000}
D/PackageManager( 3523): flags{3}
D/PersonaManagerService( 3523): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 3523): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 3523): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3523): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3523): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3523): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3523): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3523): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3523): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3523): !@killApplicatoin: 10680, uninstall pkg
I/ActivityManager( 3523): Force stopping com.test.thalitest appid=10680 user=-1: uninstall pkg
W/PackageSettings( 3523): Skipping PackageSetting{2eedb99c com.example.hello/10678} due to missing metadata
I/ActivityManager( 3523): Force stopping com.test.thalitest appid=10680 user=0: pkg removed
I/art     ( 4038): Explicit concurrent mark sweep GC freed 30714(1903KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 28MB/44MB, paused 1.260ms total 41.764ms
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader( 3523): Reconfiguring input devices.  changes=0x00000010
I/art     ( 8863): Explicit concurrent mark sweep GC freed 24942(1452KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.078ms total 41.283ms
E/SamsungIME( 4466): mOCRHelper is null
I/art     ( 4820): Explicit concurrent mark sweep GC freed 17399(1009KB) AllocSpace objects, 1(16KB) LOS objects, 20% free, 31MB/39MB, paused 1.089ms total 77.111ms
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/Zygote  (12714): MountEmulatedStorage()
I/libpersona(12714): KNOX_SDCARD checking this for 10063
E/Zygote  (12714): v2
I/libpersona(12714): KNOX_SDCARD not a persona
I/SELinux (12714): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3523): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12714 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12714): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12714): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourceType( 5159): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5159): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
D/TimaKeyStoreProvider(12714): TimaSignature is unavailable
D/ActivityThread(12714): Added TimaKeyStore provider
I/art     ( 3523): Explicit concurrent mark sweep GC freed 42534(3MB) AllocSpace objects, 68(2MB) LOS objects, 23% free, 53MB/69MB, paused 1.719ms total 168.432ms
D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     ( 3523): WaitForGcToComplete blocked for 163.402ms for cause Explicit
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/SecContentProvider2( 3523): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3523): mCursor = null
D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
D/ResourcesManager(12714): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
D/RegisteredServicesCache( 3967): empty dynamic service
D/VRSetupWizardStub/PackageIntentReceiver(12714): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12714): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12714): packagename:com.test.thalitest
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/Zygote  (12730): MountEmulatedStorage()
E/Zygote  (12730): v2
I/libpersona(12730): KNOX_SDCARD checking this for 10021
I/libpersona(12730): KNOX_SDCARD not a persona
I/SELinux (12730): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12730): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3523): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12730 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
E/SELinux (12730): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider(12730): TimaSignature is unavailable
D/ActivityThread(12730): Added TimaKeyStore provider
D/ResourcesManager(12730): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
I/art     ( 3523): Explicit concurrent mark sweep GC freed 6126(347KB) AllocSpace objects, 0(0B) LOS objects, 23% free, 53MB/69MB, paused 1.966ms total 133.705ms
I/KLMS-2.4.521: (12730): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 07 20:49:51 GMT+01:00 2016
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
I/KLMS-2.4.521: (12730): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 3523): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3523): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (12730): KLMSIntentService(): onCreate()
I/KLMS-2.4.521: (12730): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/KLMS-2.4.521: (12730): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.4.521: (12730): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/PackageManager( 3523): delete codoeFile: 
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
I/libpersona(12746): KNOX_SDCARD checking this for 10106
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/talkback/talkback.apk
I/libpersona(12746): KNOX_SDCARD not a persona
E/Zygote  (12746): MountEmulatedStorage()
E/Zygote  (12746): v2
I/SELinux (12746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
I/AASAUninstall( 3523):  com.test.thalitest not target!
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
I/ActivityManager( 3523): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12746 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
I/SELinux (12746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Books/Books.apk
E/SELinux (12746): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PackageManager( 3523): result of delete: 1{773428168}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/AndroidRuntime(12696): Shutting down VM
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/KLMS-2.4.521: (12730): KLMSIntentService(): PACKAGE_REMOVED
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (12730): KLMSIntentService(): listeningToPackageRemoved().START
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/KLMS-2.4.521: (12730): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/art     ( 2881): Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 897us total 25.229ms
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/EnterpriseDeviceManagerService( 3523): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3523): Admin package name: com.google.android.gms
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/TimaKeyStoreProvider(12746): TimaSignature is unavailable
D/ActivityThread(12746): Added TimaKeyStore provider
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 453us total 18.135ms
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Videos/Videos.apk
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 452us total 12.559ms
E/Zygote  (12761): MountEmulatedStorage()
E/Zygote  (12761): v2
I/libpersona(12761): KNOX_SDCARD checking this for 1000
I/libpersona(12761): KNOX_SDCARD not a persona
I/SELinux (12761): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3523): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=12761 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (12761): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12761): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.4.521: (12730): KLMSIntentService(): listeningToPackageRemoved().END
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(12746): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
E/Zygote  (12776): MountEmulatedStorage()
E/Zygote  (12776): v2
I/libpersona(12776): KNOX_SDCARD checking this for 10050
I/libpersona(12776): KNOX_SDCARD not a persona
I/SELinux (12776): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/RCPManagerService( 3523): PackageReceiver onReceive()
I/HarmonyEASService( 3523): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/SELinux (12776): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/KnoxMUMContainerPolicy( 3523): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
E/SELinux (12776): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12776 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/BackupManagerService( 3523): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3523): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3523): uID is 10680
V/EnterpriseBillingPolicy( 3523): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3523): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3523): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3523): getBillingProfileForVpnEngine - start - com.test.thalitest
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
V/EnterpriseBillingPolicyStorage( 3523): getBillingProfileForVpnEngine - end - null
D/TimaKeyStoreProvider(12761): TimaSignature is unavailable
D/ActivityThread(12761): Added TimaKeyStore provider
I/KLMS-2.4.521: (12730): KLMSIntentService(): onDestroy()
D/TaskPersister( 3523): removeObsoleteFile: deleting file=28_task.xml
D/elm:14491(12746): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491(12746): ELMEngine.ELMEngine( context ).
D/elm:14491(12746): MDMBridge.setEnterpriseBridge()
D/TimaKeyStoreProvider(12776): TimaSignature is unavailable
D/ActivityThread(12776): Added TimaKeyStore provider
D/ResourcesManager(12761): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
W/ResourcesManager(12761): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/elm:14491(12746): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14491(12746): ElmAgentService : onCreate()
D/elm:14491(12746): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/RCPManager(12761):  in createShortcut() for packageName: com.test.thalitest userId0
D/elm:14491(12746): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12746): MDMBridge.getInstance()
D/elm:14491(12746): MDMBridge.getAllLicenseInfoFromSDK()
D/RCPManagerService( 3523):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3523): queryAllProviders():  providerCallBack is not register for 0
D/elm:14491(12746): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(12776): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
W/ResourcesManager(12776): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12776): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12776): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12776): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12776): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12776): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12776): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12776): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/Zygote  (12794): MountEmulatedStorage()
E/Zygote  (12794): v2
I/libpersona(12794): KNOX_SDCARD checking this for 10019
I/libpersona(12794): KNOX_SDCARD not a persona
I/SELinux (12794): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12794): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12794): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12794 uid=10019 gids={50019, 9997} abi=armeabi-v7a
D/elm:14491(12746): ElmAgentService : onDestroy().
I/TapandpayWidget:TanpandpayAppWidgetProvider(11397): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(11397): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils(11397): Clear T&P info.
D/TapandpayWidget:TanpandpayAppWidgetProvider(11397): Widget is not attached.
D/TimaKeyStoreProvider(12794): TimaSignature is unavailable
W/ResourceType( 3523): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
I/ActivityManager( 3523): Killing 10187:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): bgCount ##31
D/ActivityThread(12794): Added TimaKeyStore provider
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 3523): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
D/ResourcesManager(12794): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
W/ContextImpl(11058): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
I/ActivityManager( 3523): Killing 9751:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 3523): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3523): onPackageRemoved : com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12794): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12794): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12794): onReceive() : package name is not s health. Return !!!
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/Zygote  (12811): MountEmulatedStorage()
I/libpersona(12811): KNOX_SDCARD checking this for 10116
E/Zygote  (12811): v2
I/libpersona(12811): KNOX_SDCARD not a persona
I/SELinux (12811): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12811): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12811): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=12811 uid=10116 gids={50116, 9997, 1023} abi=armeabi-v7a
D/PackageManager( 3523): findPreferredActivity: No PreferredActivities set
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(12811): TimaSignature is unavailable
D/ActivityThread(12811): Added TimaKeyStore provider
E/Zygote  (12829): MountEmulatedStorage()
E/Zygote  (12829): v2
I/libpersona(12829): KNOX_SDCARD checking this for 10022
I/libpersona(12829): KNOX_SDCARD not a persona
I/SELinux (12829): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12829): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12829): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12829 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
W/GeofencerStateMachine( 4638): Ignoring removeGeofence because network location is disabled.
D/TimaKeyStoreProvider(12829): TimaSignature is unavailable
E/Zygote  (12845): MountEmulatedStorage()
E/Zygote  (12845): v2
I/libpersona(12845): KNOX_SDCARD checking this for 1000
D/ActivityThread(12829): Added TimaKeyStore provider
I/libpersona(12845): KNOX_SDCARD not a persona
I/SELinux (12845): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3523): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=12845 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (12845): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3523): Killing 10816:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
E/SELinux (12845): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/NearbySource(12776): Nearby Source Create!
D/NearbyContext(12776): Nearby Context Create!
D/PackageBroadcastService( 4820): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4820): Clearing selected account for com.test.thalitest
D/TimaKeyStoreProvider(12845): TimaSignature is unavailable
D/ActivityThread(12845): Added TimaKeyStore provider
D/ResourcesManager(12829): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
D/ResourcesManager(12811): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
W/ResourcesManager(12829): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12829): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12829): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12776): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(12776): Samsung link source created
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3523): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3523): displayNotification : [0ah,00h,00h]
D/ResourcesManager(12845): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3523): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3523): displayNotification : [0ah,00h,01h]
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3523): usbDeviceRemoved : /dev/bus/usb/001/003
D/UsbHostManager( 3523): displayNotification : [09h,00h,00h]
D/ChimeraCfgMgr( 4820): Loading module com.google.android.gms.games from APK com.google.android.play.games
E/UsbHostManager( 3523): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
I/LocationSettingsChecker( 4820): Removing dialog suppression flag for package com.test.thalitest
D/UsbSettingsManager( 3523): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
D/ChimeraModuleLdr( 4820): Module APK com.google.android.play.games already loaded
E/SQLiteLog(12776): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
I/LocationWidgetApplication(12829): onCreate() : start
E/SQLiteLog( 4820): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4820): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/LocationWidgetApplication(12829): countryCode = POLAND
E/SQLiteLog(12811): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
W/ContextImpl(12845): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2994 
E/SQLiteDatabase(12811): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase(12811): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12811): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12811): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12811): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12811): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12811): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12811): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12811): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12811): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12811): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12811): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteDatabase(12811): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(12811): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(12811): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(12811): 	at android.os.Binder.execTransact(Binder.java:446)
D/UsbHostManager( 3523): usbDeviceRemoved : /dev/bus/usb/001/001
E/SQLiteOpenHelper(12811): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper(12811): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12811): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12811): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12811): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12811): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12811): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12811): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12811): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12811): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12811): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12811): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteOpenHelper(12811): 	at android.content.ContentProvider.query(ContentPro
```
