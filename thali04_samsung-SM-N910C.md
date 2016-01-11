#### Test 5497026186051be_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
--------- beginning of main
E/Zygote  (11343): MountEmulatedStorage()
E/Zygote  (11343): v2
I/SELinux (11343): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11343): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11343): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/libpersona(11343): KNOX_SDCARD checking this for 10045
I/libpersona(11343): KNOX_SDCARD not a persona
I/ActivityManager( 3508): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=11343 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/System.out(11321): Inside WakeupProvider
D/TimaKeyStoreProvider(11343): TimaSignature is unavailable
E/DatabaseUtils(11321): Writing exception to parcel
E/DatabaseUtils(11321): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(11321): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(11321): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(11321): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(11321): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(11321): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(11321): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(11321): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(11321): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(11321): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(11321): 	at android.os.Binder.execTransact(Binder.java:446)
D/ActivityThread(11343): Added TimaKeyStore provider
W/System.err(11291): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err(11291): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err(11291): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err(11291): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err(11291): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err(11291): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err(11291): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err(11291): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err(11291): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err(11291): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err(11291): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err(11291): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(11291): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err(11291): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err(11291): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err(11291): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err(11291): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err(11291): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err(11291): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:131)
W/System.err(11291): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:197)
W/System.err(11291): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(11291): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err(11291): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(11291): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(11291): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(11291): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(11291): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(11291): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(11291): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(11291): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(11291): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(11291): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/ActivityManager( 3508): Killing 9674:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
D/ResourcesManager(11343): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
E/DatabaseUtils(11321): Writing exception to parcel
E/DatabaseUtils(11321): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(11321): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(11321): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(11321): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(11321): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(11321): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(11321): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(11321): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(11321): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(11321): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(11321): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(11291): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err(11291): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err(11291): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err(11291): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err(11291): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err(11291): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err(11291): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err(11291): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err(11291): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err(11291): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err(11291): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err(11291): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(11291): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err(11291): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err(11291): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err(11291): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err(11291): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:242)
W/System.err(11291): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(11291): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err(11291): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(11291): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(11291): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(11291): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(11291): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(11291): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(11291): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(11291): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(11291): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(11291): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode](11291): [DLApplication]-Init Called!:false
W/[CarMode](11291): [CommonUtil]-=========================================
W/[CarMode](11291): [CommonUtil]-CarMode Version:1.10.38.19768
W/[CarMode](11291): [CommonUtil]-=========================================
E/[CarMode](11291): [DLApplication]-Init Started!:true
I/[CarModeFW](11291): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW](11291): ### com.sec.android.app.automotive.carmode.framework.DriveLinkServiceInterfaceImp::initialize(132)
I/[CarModeFW](11291): ### com.sec.android.automotive.drivelink.DLApplication::init(211)
I/[CarModeFW](11291): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(135)
I/[CarModeFW](11291): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW](11291): ### android.app.ActivityThread::handleBindApplication(5115)
I/[CarModeFW](11291): ### android.app.ActivityThread::access$1600(178)
I/[CarModeFW](11291): ### android.app.ActivityThread$H::handleMessage(1510)
I/[CarModeFW](11291): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW](11291): ### android.os.Looper::loop(145)
I/[CarModeFW](11291): ### android.app.ActivityThread::main(5944)
I/[CarModeFW](11291): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW](11291): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW](11291): ### com.android.internal.os.ZygoteInit::main(1194)
I/VlingoApplication(11321): VlingoApplication appVersion ='11.7.0.1.39589', coreVersion = '2.5.2.15201', ro.csc.sales_code=XEO
D/ResourcesManager( 8937): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/MessageDataHandler(11291): initialize
D/[CarModeFW](11291): CDH-initiazlieCaches : before sync
D/[CarModeFW](11291): CDH-initiazlieCaches : after sync
I/VlingoAndroidCore(11321): AppName: SamsungTproject, Core: 2.5.2.15201, SDK: 2.0.1657, EDM:15201
D/[CarModeFW](11291): CDH-buildContactCacheWireFrame : cur len =0
I/SA      (11343): [SSP] onCreated
D/[CarModeFW](11291): CDH-ContactDataHandler initiazlieCaches time : 16
D/[CarModeFW](11291): CDH-initiazlieCaches : end sync
D/[CarModeFW](11291): DrivingManager-initialize...
I/SensorService( 3508): Skipped sensor HRMLED IR because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3508): Skipped sensor HRMLED RED because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3508): Skipped sensor MAX86902 because it requires permission 
I/SensorService( 3508): Skipped sensor HRM Sensor because it requires permission 
I/SensorService( 3508): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SA      (11343): [TPM] There is no property file
I/SA      (11343): [SCU] isHaveSA() - false
I/SA      (11343): [TPM] getModelProperty : null
I/SA      (11343): [TPM] getCSCProperty : null
I/SA      (11343): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      (11343): [DM] init START
I/SA      (11343): [DM] This device is not a Vodafone
I/SA      (11343): checkReactivationActive for LOLLIPOP
I/SA      (11343): checkReactivationActive for reactiveActive
I/SA      (11343): setSupportRL : true
I/SA      (11343): [SCU] isHaveSA() - false
I/SA      (11343): support phone number id : false
I/SA      (11343): [DM] init END
D/VlingoApplication(11321): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
I/SA      (11343): [SUR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
D/VlingoApplication(11321): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
D/DialogFlow(11321): initQueue()
I/SA      (11343): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10556 extra.user_handle.:0 ]
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/Zygote  (11382): MountEmulatedStorage()
E/Zygote  (11382): v2
I/libpersona(11382): KNOX_SDCARD checking this for 10046
I/libpersona(11382): KNOX_SDCARD not a persona
I/SELinux (11382): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11382): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11382): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Start proc com.samsung.android.app.pinboard:sync for broadcast com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayReceiver: pid=11382 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager( 3508): Killing 9689:com.android.calendar/u0a164 (adj 13): bgCount ##31
I/art     ( 2883): Explicit concurrent mark sweep GC freed 8751(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 716us total 11.127ms
D/TimaKeyStoreProvider(11382): TimaSignature is unavailable
D/ActivityThread(11382): Added TimaKeyStore provider
I/MediaPlayer(11291): Need to enable context aware info
V/MediaPlayer-JNI(11291): native_setup
V/MediaPlayer(11291): constructor
I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 370us total 8.198ms
V/MediaPlayer(11291): setListener
I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 258us total 8.162ms
W/GAV2    (11033): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 3508): Killing 10609:com.samsung.dcm:DCMService/u0a4 (adj 13): bgCount ##31
I/art     ( 3508): Explicit concurrent mark sweep GC freed 237273(15MB) AllocSpace objects, 3(4MB) LOS objects, 24% free, 49MB/65MB, paused 1.313ms total 89.053ms
D/[CarModeFW](11291): MY_TAG-[YANG] MusicButtonReceiver construct MusicButtonReceiver() 
I/[CarModeFW](11291): DriveLinkServiceInterfaceImp-drivelink framework initialize end
D/[CarMode](11291): [DLServiceManager]-getOnDLLocationSuggestionListener..........
D/[CarModeFW](11291): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => start time : 1452511816423
D/ResourcesManager(11382): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
W/ResourcesManager(11382): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11382): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(11382): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/[CarModeFW](11291): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1452511816425
D/[CarMode](11291): [DLServiceManager]-updateLocationList
D/[CarMode](11291): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW](11291): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => start time : 1452511816426
D/[CarModeFW](11291): insertNavigationAvailable-sql: select distinct nav_package from tb_location_navigation_available
F/DLApplication(11291): DLApplication mListNavitationAvailable: [com.skt.skaf.l001mtm091, com.google.android.apps.maps, kt.navi, com.mnsoft.lgunavi, com.autonavi.xmgd.navigator.samsung, com.here.app.maps]
I/[CarMode](11291): [LogNotNull]-Package name is: com.here.app.maps
D/[CarModeFW](11291): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => start time : 1452511816428
D/[CarModeFW](11291): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => start time : 1452511816428
D/[CarModeFW](11291): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => start time : 1452511816428
D/[CarModeFW](11291): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1452511816428
D/[CarModeFW](11291): ContactDataHandler-getFavoriteContactList : cur len = 0
D/[CarModeFW](11291): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 5
D/TP/SmsProvider( 3981): query,matched:2, calling pid = 11291
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 3981): match 2:Elapsed time : 2.312 ms
D/[CarModeFW](11291): ContactDataHandler-getFavoriteContactList : cur len = 0
D/[CarModeFW](11291): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => execute time : 8
D/[CarModeFW](11291): ContactDataHandler-getFavoriteContactList : cur len = 0
D/[CarModeFW](11291): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 17
E/Zygote  (11399): MountEmulatedStorage()
I/libpersona(11399): KNOX_SDCARD checking this for 10047
E/Zygote  (11399): v2
I/libpersona(11399): KNOX_SDCARD not a persona
I/SELinux (11399): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11399): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11399): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=11399 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/[CarMode](11291): [DLApplication]-Init End!:true
D/[CarMode](11291): [TAG]-phone sound mode is: 0
V/[CarMode](11291): [DLApplication]-savePreviousGpsState
D/MessageDataHandler(11291):  getInboxList smsCursor : 30
D/[CarModeFW](11291): CalllogDataHandler-getCalllogList : cur len = 0
D/TP/SmsProvider( 3981): query,matched:2, calling pid = 11291
D/TP/SmsProvider( 3981): match 2:Elapsed time : 1.806 ms
V/[CarMode](11291): [DLApplication]-savePreviousGpsState: Previous state = 0
D/[CarModeFW](11291): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => execute time : 37
D/TP/MmsProvider( 3981): Query uri=content://mms/inbox, match=2, calling pid = 11291
D/MessageDataHandler(11291):  getInboxList mmsCursor : 6
D/TP/MmsProvider( 3981): Query uri=content://mms, match=0, calling pid = 11291
D/MessageDataHandler(11291):  getInboxList mms,sms cursor join : 3
I/MessageDataHandler(11291): getUnreadMessageCount :0
D/[CarModeFW](11291): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => execute time : 39
E/Minikin (11382): addFont failed to create font /system/fonts/SamsungSans-light.ttf
D/TP/MmsSmsProvider( 3981): query,matched:0, calling pid = 11291
V/TP/MmsSmsProvider( 3981): getSimpleConversations entered.
D/TP/MmsSmsProvider( 3981): match 0:Elapsed time : 0.772 ms
D/TimaKeyStoreProvider(11399): TimaSignature is unavailable
D/ActivityThread(11399): Added TimaKeyStore provider
D/[CarMode](11291): [DLApplication]-GooglePlayServices SUCCESS.
E/[CarMode](11291): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
D/TP/MmsSmsProvider( 3981): query,matched:13, calling pid = 11291
D/TP/MmsSmsProvider( 3981): match 13:Elapsed time : 0.876 ms
D/ResourcesManager(11399): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
I/[CarMode](11291): [[DLUncaughtExceptionHandler]]-setDLUncaughtExceptionHandler
E/[CarMode](11291): [[DLUncaughtExceptionHandler]]-DLUncaughtExceptionHandler is created!
D/MessageDataHandler(11291):  getInboxList address cursor : 5
W/ResourcesManager(11399): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 3981): query,matched:0, calling pid = 11291
V/TP/MmsSmsProvider( 3981): getSimpleConversations entered.
I/UpdateManagerReceiver(11291): Intent : android.intent.action.PACKAGE_ADDEDMon Jan 11 12:30:16 GMT+01:00 2016
D/TP/MmsSmsProvider( 3981): match 0:Elapsed time : 1.473 ms
I/RelayReceiver_PinBoard(11382): onReceive... android.intent.action.PACKAGE_ADDED
D/DialogFlow(11291): initQueue()
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
I/CalendarProvider2(11399): CalendarProvider2.onCreate() called
E/Zygote  (11414): MountEmulatedStorage()
E/Zygote  (11414): v2
I/libpersona(11414): KNOX_SDCARD checking this for 1000
I/libpersona(11414): KNOX_SDCARD not a persona
I/SELinux (11414): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11414): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11414): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=11414 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3508): Killing 9297:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
I/ActivityManager( 3508): Killing 9788:com.google.android.talk/u0a125 (adj 13): bgCount ##32
I/ActivityManager( 3508): Killing 10645:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##33
D/MessageDataHandler(11291):  getInboxList thread cursor : 27
D/MessageDataHandler(11291):  thread, addr result: 3
I/[CarModeFW](11291): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxList() : 83
I/[CarModeFW](11291): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW](11291): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => execute time : 83
I/RelayService_PinBoard(11382): RelayService Started!! : android.intent.action.PACKAGE_ADDED
D/TimaKeyStoreProvider(11414): TimaSignature is unavailable
D/ActivityThread(11414): Added TimaKeyStore provider
D/ResourcesManager(11414): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
W/ContextImpl(11414): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11414): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
E/Zygote  (11432): MountEmulatedStorage()
I/libpersona(11432): KNOX_SDCARD checking this for 10121
E/Zygote  (11432): v2
I/libpersona(11432): KNOX_SDCARD not a persona
I/SELinux (11432): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11432): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/FilterInstaller(11414): installFilters
E/SELinux (11432): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/FilterInstaller(11414): There is no requred permission
I/ActivityManager( 3508): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=11432 uid=10121 gids={50121, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
D/TimaKeyStoreProvider(11432): TimaSignature is unavailable
D/ActivityThread(11432): Added TimaKeyStore provider
I/ActivityManager( 3508): Killing 10504:com.google.android.gm/u0a122 (adj 15): bgCount ##31
D/[CarModeFW](11291): LocationDataHandler-No schedules found.
D/[CarModeFW](11291): MyPlaceProvider-Provider uri: content://com.samsung.android.internal.intelligence.useranalysis/place
D/ResourcesManager(11432): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
D/PackageIntentReceiver(11432): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver(11432): Not GearManger package! 
E/Zygote  (11451): MountEmulatedStorage()
E/Zygote  (11451): v2
I/libpersona(11451): KNOX_SDCARD checking this for 10003
I/libpersona(11451): KNOX_SDCARD not a persona
I/SELinux (11451): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11451): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11451): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=11451 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/Zygote  (11464): MountEmulatedStorage()
E/Zygote  (11464): v2
I/libpersona(11464): KNOX_SDCARD checking this for 1000
I/libpersona(11464): KNOX_SDCARD not a persona
I/System.out(11321): INFO:Resource not found:/Common.properties Using default values
I/SELinux (11464): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11464): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3508): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=11464 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11464): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider(11451): TimaSignature is unavailable
D/ActivityThread(11451): Added TimaKeyStore provider
D/TimaKeyStoreProvider(11464): TimaSignature is unavailable
D/ActivityThread(11464): Added TimaKeyStore provider
I/ActivityManager( 3508): Killing 10561:com.google.android.music:main/u0a135 (adj 15): bgCount ##31
D/ResourcesManager(11464): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/ResourcesManager(11451): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
D/UserAnalysis.PlaceProvider(11451): PlaceProvider onCreate()
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
D/UserAnalysis.SecureDbManager(11451): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper(11451): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(11451): Create SecureDbHelper
E/Zygote  (11483): MountEmulatedStorage()
I/libpersona(11483): KNOX_SDCARD checking this for 1000
E/Zygote  (11483): v2
I/libpersona(11483): KNOX_SDCARD not a persona
I/SELinux (11483): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11483): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3508): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=11483 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11483): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Killing 10695:com.google.android.gms:car/u0a14 (adj 15): bgCount ##31
I/Icing   ( 6857): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
D/IntelligenceServiceApplication(11451): onCreate()
D/TimaKeyStoreProvider(11483): TimaSignature is unavailable
D/ActivityThread(11483): Added TimaKeyStore provider
D/ResourcesManager(11483): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
D/[CarModeFW](11291): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW](11291): MyPlaceProvider-=============
D/[CarModeFW](11291): MyPlaceProvider-=============
D/[CarModeFW](11291): MyPlaceProvider-=============
D/[CarModeFW](11291): MyPlaceProvider-=============
D/[CarModeFW](11291): MyPlaceProvider-=============
D/[CarModeFW](11291): MyPlaceProvider-=============
D/[CarModeFW](11291): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW](11291): MyPlaceProvider-==============
D/[CarModeFW](11291): MyPlaceProvider-==============
D/[CarModeFW](11291): MyPlaceProvider-==============
D/[CarModeFW](11291): MyPlaceProvider-==============
D/[CarModeFW](11291): MyPlaceProvider-==============
D/[CarModeFW](11291): DestinationAvailableTableHandler-sql: select dest_name from tb_destination_list_available where ((1452511816724 - dest_date ) / 360000 ) <= 24 ORDER BY dest_date DESC LIMIT 100
E/[CarModeFW](11291): DestinationAvailableTableHandler-insert FAIL!
E/DestinationList(11291): loadLocationDestinationList is null
D/[CarModeFW](11291): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => execute time : 297
D/ResourcesManager( 6857): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
D/AcmsPackageEventListener(11483): Received: android.intent.action.PACKAGE_ADDED
W/ContextImpl(11483): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
E/Zygote  (11500): MountEmulatedStorage()
I/libpersona(11500): KNOX_SDCARD checking this for 10147
E/Zygote  (11500): v2
I/libpersona(11500): KNOX_SDCARD not a persona
I/SELinux (11500): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11500): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11500): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=11500 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/Icing   ( 6857): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
I/ActivityManager( 3508): Killing 6605:com.google.process.gapps/u0a14 (adj 15): bgCount ##31
D/AcmsService(11483): Enter Oncreate
D/AcmsServiceMonitor(11483): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService(11483): creating AcmsCore
D/AcmsCore(11483): AcmsCore.getAcmsCore() - Enter
D/AcmsCore(11483): AcmsCore
D/TimaKeyStoreProvider(11500): TimaSignature is unavailable
D/ActivityThread(11500): Added TimaKeyStore provider
D/ResourcesManager(11500): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/AcmsCore(11483): init
D/AcmsCore(11483): Looper handler is not null
D/AcmsCore(11483): Post to AcmsCoreHandler
D/AcmsServiceMonitor(11483): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(11483): Incrementing - Counter value: 1
D/AcmsCore(11483): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService(11483): onStartCommand
D/AcmsService(11483): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor(11483): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor(11483): Incrementing - Counter value: 2
D/AcmsService(11483): Incremented Counter Value : onStartCommand
D/AcmsCertificateMngr(11483): AcmsCertificateMngr
D/AcmsRevocationMngr(11483): AcmsRevocationMngr
W/ResourcesManager(11500): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ActivityThread(11483): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/AcmsService(11483): Inside handle Intent
D/AcmsService(11483): App added - package name: com.test.thalitest
D/AcmsCore(11483): Post to AcmsCoreHandler
D/AcmsServiceMonitor(11483): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(11483): Incrementing - Counter value: 3
D/AcmsCore(11483): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService(11483): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor(11483): Decrementing - Counter value: 2
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/Zygote  (11527): MountEmulatedStorage()
E/Zygote  (11527): v2
I/libpersona(11527): KNOX_SDCARD checking this for 10014
I/libpersona(11527): KNOX_SDCARD not a persona
I/SELinux (11527): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11527): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11527): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=11527 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
D/TimaKeyStoreProvider(11527): TimaSignature is unavailable
D/ActivityThread(11527): Added TimaKeyStore provider
D/ResourcesManager(11527): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
I/GservicesProvider(11527): Gservices pushing to system: true; secure/global: true
I/GoogleHttpClient(11527): GMS http client unavailable, use old client
D/ResourcesManager(11527): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
I/GoogleHttpClient(11527): GMS http client unavailable, use old client
V/GLSActivity( 4645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 4645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/Zygote  (11552): MountEmulatedStorage()
E/Zygote  (11552): v2
I/libpersona(11552): KNOX_SDCARD checking this for 10160
I/libpersona(11552): KNOX_SDCARD not a persona
I/SELinux (11552): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11552): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3508): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=11552 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
E/SELinux (11552): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11552): TimaSignature is unavailable
D/ActivityThread(11552): Added TimaKeyStore provider
D/ResourcesManager(11552): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/ResourcesManager(11552): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(11552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11552): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
I/Icing   ( 6857): Indexing 5F814D61A0DCF2E8041D271E5054F7C0773240D3 from com.google.android.googlequicksearchbox
V/Common  (11552): getScreenSize 1440 2560
I/JAM     (11552): Load The ApaService JNI
I/JAM     (11552): version: ProfessionalAudio_v1.0.b5
I/JAM     (11552): Try v1.0.b3 ...
D/Spen    (11552): SpenSdk version level = 55
D/Spen    (11552): SpenSdk jar version = 3.0.243
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
D/Spen    (11552): SpenSdk apk version = 3.0.235
D/Spen    (11552): Server UPDATE Check
W/linker  (11552): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
D/SPenError(11552): JNI_OnLoad
D/JNI_Bitmap(11552): Init .. Done
D/SPenSpiDecoder(11552): JNI_OnLoad .. Done
D/SPenError(11552): JNI_OnLoad Success
D/PluginManager(11552): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
D/PluginManager(11552): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
D/Init_SPenSdk_Jni(11552): JNI_OnLoad
D/Init_SPenSdk_Jni(11552): AndroidSDK: 21
D/Init_SPenSdk_Jni(11552): JNI_OnLoad .. Done
D/Model_ObjectBase_Jni(11552): JNI_OnLoad .. Done
D/Model_ObjectStroke_Jni(11552): JNI_OnLoad .. Done
D/Model_ObjectImage_Jni(11552): JNI_OnLoad .. Done
D/Model_ObjectText_Jni(11552): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni(11552): JNI_OnLoad .. Done
D/Model_PageDoc_Jni(11552): JNI_OnLoad .. Done
D/Model_NoteDoc_Jni(11552): check build type eng[0]
D/Model_NoteDoc_Jni(11552): JNI_OnLoad .. Done
D/Model_NoteFile_Jni(11552): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni(11552): JNI_OnLoad .. Done
D/Model   (11552): OnLoad class Done
E/Zygote  (11578): MountEmulatedStorage()
E/Zygote  (11578): v2
I/libpersona(11578): KNOX_SDCARD checking this for 10160
I/libpersona(11578): KNOX_SDCARD not a persona
D/spe_log (11552): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
D/SPen_Library(11552): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(11552): Canvas JNI_OnLoad enter!!
I/SELinux (11578): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/SPen_Library(11552): Canvas JNI_OnLoad Success
D/SPen_Library(11552): TextView JNI_OnLoad enter!!
D/SPen_Library(11552): TextView JNI_OnLoad Success
D/SPen_Library(11552): Text JNI_OnLoad enter!!
D/SPen_Library(11552): Text JNI_OnLoad Success
I/ActivityManager( 3508): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=11578 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
D/SPen_Library(11552): FontManager JNI_OnLoad enter!!
D/SPen_Library(11552): FontManager JNI_OnLoad Success
D/SPen_Library(11552): CapturePage JNI_OnLoad enter!!
D/SPen_Library(11552): CapturePage JNI_OnLoad Success
D/SPen_Library(11552): Multi JNI_OnLoad enter!!
D/SPen_Library(11552): Multi JNI_OnLoad Success
D/SPen_Library(11552): Draw Engine JNI_OnLoad Success
D/SPen_Library(11552): Brush JNI_OnLoad enter!!
D/SPen_Library(11552): Brush JNI_OnLoad Success
I/SELinux (11578): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/SPen_Library(11552): ChineseBrush JNI_OnLoad enter!!
D/SPen_Library(11552): ChineseBrush JNI_OnLoad Success
D/SPen_Library(11552): InkPen JNI_OnLoad enter!!
E/SELinux (11578): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SPen_Library(11552): InkPen JNI_OnLoad Success
D/SPen_Library(11552): Marker JNI_OnLoad enter!!
D/SPen_Library(11552): Marker JNI_OnLoad Success
D/SPen_Library(11552): Pencil JNI_OnLoad enter!!
D/SPen_Library(11552): Pencil JNI_OnLoad Success
D/SPen_Library(11552): NativePen JNI_OnLoad enter!!
D/SPen_Library(11552): NativePen JNI_OnLoad Success
D/SPen_Library(11552): MontblancFountainPen JNI_OnLoad enter!!
D/SPen_Library(11552): MontblancFountainPen JNI_OnLoad Success
D/SPen_Library(11552): MontblancCalligraphyPen JNI_OnLoad enter!!
D/SPen_Library(11552): MontblancCalligraphyPen JNI_OnLoad Success
D/SPen_Library(11552): MagicPen JNI_OnLoad enter!!
D/SPen_Library(11552): MagicPen JNI_OnLoad Success
D/SPen_Library(11552): ObliquePen JNI_OnLoad enter!!
D/SPen_Library(11552): ObliquePen JNI_OnLoad Success
D/SPen_Library(11552): FountainPen JNI_OnLoad enter!!
D/SPen_Library(11552): FountainPen JNI_OnLoad Success
D/Spen    (11552): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(11552): SPenSdk_init2
D/Init_SPenSdk(11552): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
D/Init_SPenSdk(11552): Total S Pen SDK Directory Size = 0
D/Spen    (11552): initialize complete
W/linker  (11552): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
I/Icing   ( 6857): Indexing done 5F814D61A0DCF2E8041D271E5054F7C0773240D3
D/ResourcesManager(11552): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/TimaKeyStoreProvider(11578): TimaSignature is unavailable
D/ActivityThread(11578): Added TimaKeyStore provider
D/ResourcesManager(11578): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
W/ResourcesManager(11578): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(11578): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11578): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
E/Zygote  (11595): MountEmulatedStorage()
E/Zygote  (11595): v2
I/libpersona(11595): KNOX_SDCARD checking this for 10183
I/libpersona(11595): KNOX_SDCARD not a persona
I/SELinux (11595): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3508): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=11595 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
I/SELinux (11595): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3508): Killing 10273:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
I/ActivityManager( 3508): Killing 11000:com.samsung.android.app.vrsetupwizardstub/u0a63 (adj 15): bgCount ##32
E/SELinux (11595): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     ( 2883): Explicit concurrent mark sweep GC freed 8781(373KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.384ms total 24.993ms
D/SNoteProvider(11578): onCreate enableSnoteSync = true
I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 318us total 9.175ms
D/TimaKeyStoreProvider(11595): TimaSignature is unavailable
D/ActivityThread(11595): Added TimaKeyStore provider
I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 297us total 9.749ms
D/ResourcesManager(11595): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
D/SNoteProvider(11578): ===query=== 
V/Common  (11578): getScreenSize 1440 2560
E/SQLiteLog(11595): (284) automatic index on shooting_modes(title_id)
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime(11575): 
D/AndroidRuntime(11575): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11575): CheckJNI is OFF
D/AndroidRuntime(11575): readGMSProperty: start
D/AndroidRuntime(11575): readGMSProperty: already setted!!
D/AndroidRuntime(11575): readGMSProperty: end
D/AndroidRuntime(11575): addProductProperty: start
E/Zygote  (11615): MountEmulatedStorage()
E/Zygote  (11615): v2
I/libpersona(11615): KNOX_SDCARD checking this for 10190
I/libpersona(11615): KNOX_SDCARD not a persona
I/SELinux (11615): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3508): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=11615 uid=10190 gids={50190, 9997} abi=armeabi-v7a
I/SELinux (11615): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11615): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Killing 11048:com.facebook.system/u0a10 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(11615): TimaSignature is unavailable
D/ActivityThread(11615): Added TimaKeyStore provider
D/ResourcesManager(11615): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
D/SNoteProvider(11578): ===query=== 
I/TapandpayWidget:TanpandpayAppWidgetProvider(11615): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(11615): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
I/TapandpayWidget:Utils(11615): Clear T&P info.
D/TapandpayWidget:TanpandpayAppWidgetProvider(11615): Widget is not attached.
I/splitIntent( 3508): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/ActivityManager( 3508): Killing 11018:com.google.android.partnersetup/u0a17 (adj 13): bgCount ##31
D/BootupListener( 3981): ACTION_DRIVELINK
D/SettingsProvider( 3508): name = drivelink_navigation
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 1001
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
D/BootupListener( 3981): NAVI : com.here.app.maps
D/SettingsProvider( 3508): name = internet_call_settings_visibility
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 1001
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
D/BootupListener( 3981): intent.getAction() = com.sec.android.automotive.drivelink.NAVIGATION_PACKAGE_NAME
D/Widget  (11552): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
D/Widget  (11552): onReceive android.appwidget.action.APPWIDGET_UPDATE
D/Widget  (11552): widgetUpdate 5
D/RCPManagerService( 3508): exchangeData() failure , invalid userId
E/AffinityControl(11575): AffinityControl: registerfunction enter
D/AndroidRuntime(11575): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3508): inState():  stateMachine is null !!
I/PersonaManagerService( 3508): PersonaId don't exist
I/ActivityManager( 3508): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3508): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3508): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3508): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3508): mDVFSHelper.acquire()
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/Zygote  (11642): MountEmulatedStorage()
E/Zygote  (11642): v2
I/libpersona(11642): KNOX_SDCARD checking this for 10556
I/libpersona(11642): KNOX_SDCARD not a persona
I/SELinux (11642): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11642): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11642): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11642 uid=10556 gids={50556, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime(11575): Shutting down VM
D/PointerIcon( 3508): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3508): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3508): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3508): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11642): TimaSignature is unavailable
D/ActivityThread(11642): Added TimaKeyStore provider
D/ResourcesManager(11642): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2850): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2850): id=11 Removed YUIInstallC (-2/8)
V/ActivityThread( 6202): updateVisibility : ActivityRecord{94a06eb token=android.os.BinderProxy@201604dc {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11642): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11642): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11642): Loading: webviewchromium
I/LibraryLoader(11642): Time to load native libraries: 2 ms (timestamps 7678-7680)
I/LibraryLoader(11642): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(11642): Binding Chromium to main looper Looper (main, tid 1) {3d78a64a}
I/LibraryLoader(11642): Expected native library version number "",actual native library version number ""
I/chromium(11642): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(11642): Initializing chromium process, renderers=0
W/art     (11642): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(11642): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(11642): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11642): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
I/CalendarProvider2(11399): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/Zygote  (11686): MountEmulatedStorage()
E/Zygote  (11686): v2
I/libpersona(11686): KNOX_SDCARD checking this for 10022
I/libpersona(11686): KNOX_SDCARD not a persona
I/SELinux (11686): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11686): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11686): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=11686 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3508): Killing 11086:com.sec.android.service.health/u0a19 (adj 15): bgCount ##31
W/chromium(11642): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(11642): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/TimaKeyStoreProvider(11686): TimaSignature is unavailable
,D/ActivityThread(11686): Added TimaKeyStore provider
,D/ResourcesManager(11686): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(11686): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11686): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11686): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/art     (11642): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11642): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11642): CordovaWebView is running on device made by: samsung
,W/art     (11642): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11642): Attempt to remove local handle scope entry from IRT, ignoring
,I/LocationWidgetApplication(11686): onCreate() : start
,D/LocationWidgetApplication(11686): countryCode = POLAND
,D/LocationWidgetUtils(11686): getUpcommingInstances() start: 1452511817664, end: 1453071599999
D/LocationWidgetUtils(11686): getUpcommingInstances() DB begin time >= start:1452511817664, DB begin time <= end:1453071599999
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/Activity(11642): performCreate Call secproduct feature valuefalse
D/Activity(11642): performCreate Call debug elastic valuetrue
,I/Mms/MmsApp(11064):  start initViewCache mms
,D/Mms/ComposeMessageFragment(11064): [start]    fillCache consume time = 1921.424083
D/Mms/ComposeMessageFragment(11064): fillCache, easy = false
,E/Zygote  (11711): MountEmulatedStorage()
E/Zygote  (11711): v2
I/libpersona(11711): KNOX_SDCARD checking this for 10163
I/libpersona(11711): KNOX_SDCARD not a persona
,I/SELinux (11711): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11711): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11711): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=11711 uid=10163 gids={50163, 9997} abi=armeabi-v7a
,I/ActivityManager( 3508): Killing 11110:com.sec.pcw.device/1000 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/11110/oom_score_adj; errno=22
,D/OpenGLRenderer(11642): Render dirty regions requested: true
,D/ActivityManager( 3508): post active user change for 0
D/KnoxTimeoutHandler( 3508): postActiveUserChange for user 0
,D/KnoxTimeoutHandler( 3508): handleActiveUserChange for user 0
,D/TimaKeyStoreProvider(11711): TimaSignature is unavailable
,D/ActivityThread(11711): Added TimaKeyStore provider
,D/ResourcesManager(11711): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,D/AbsListView(11064): Get MotionRecognitionManager
,W/ResourcesManager(11711): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11711): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/MotionRecognitionService( 3508):  ssp status : true
,I/SurfaceFlinger( 2850): id=14 createSurf (1x1),1 flag=404, NainActivit
D/Mms/ComposeMessageFragment(11064): [end]    fillCache consume time = 57.135542
,D/StatusBarManagerService( 3508): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3508): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
D/PointerIcon( 3508): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3508): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3508): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3508): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11642): Initialized EGL, version 1.4
,I/OpenGLRenderer(11642): HWUI protection enabled for context ,  &this =0xaf645060 ,&mEglDisplay = 1 , &mEglConfig = -1278643952 
E/Zygote  (11733): MountEmulatedStorage()
E/Zygote  (11733): v2
I/libpersona(11733): KNOX_SDCARD checking this for 10164
I/libpersona(11733): KNOX_SDCARD not a persona
,I/SELinux (11733): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/OpenGLRenderer(11642): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11642): Enabling debug mode 0
I/SELinux (11733): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11733): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/mali_winsys(11642): new_window_surface returns 0x3000,  [1440x2560]-format:1
,I/ActivityManager( 3508): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=11733 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,V/ActivityThread(11642): updateVisibility : ActivityRecord{14af35fa token=android.os.BinderProxy@368abcf9 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/ActivityManager( 3508): Killing 10376:com.facebook.appmanager/u0a110 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/10376/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(11733): TimaSignature is unavailable
,D/ActivityThread(11733): Added TimaKeyStore provider
,D/ResourcesManager(11733): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11733): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11733): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11733): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11733): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/InputMethodManagerService( 3508): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3508): mDVFSHelper.release()
I/Timeline( 3508): Timeline: Activity_windows_visible id: ActivityRecord{1a90440c u0 com.test.thalitest/.MainActivity t26} time:118010
,D/Mms/BubbleViewCache(11064): fillCache bubble = 8
,I/art     ( 3508): Explicit concurrent mark sweep GC freed 21445(1257KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 6.244ms total 108.613ms
,W/IInputConnectionWrapper(11642): showStatusIcon on inactive InputConnection
,I/Timeline(11642): Timeline: Activity_idle id: android.os.BinderProxy@368abcf9 time:118114
,D/daemonapp( 3773): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LocationManagerService( 3508): getProviders()=[]
D/LocationManagerService( 3508): getProviders()=[passive]
D/LocationManagerService( 3508): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/LWLocationManager(11686): mPrivacy is null
,W/ContextImpl(11686): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,I/ActivityManager( 3508): Killing 11064:com.android.mms/u0a52 (adj 15): bgCount ##31
,D/ContextFramework:PrivacyManager(11686): Service for PrivacyManager is connected
,D/LWLocationManager(11686): Privacy service : STATUS_PLACE
D/LWLocationManager(11686): updateLocationStatus()
,I/LocationWidgetFuctionData(11686): readDB
,I/LocationWidgetFuctionData(11686): selectedAppSize: 3
I/LocationWidgetFuctionData(11686): configPlaceList aroundMeItems
,I/LocationWidgetFuctionData(11686): selectedAppSize: 3
,I/LocationWidgetFuctionData(11686): selectedAppSize: 3
,I/LocationWidgetFuctionData(11686): selectedAppSize: 3
,I/LocationWidgetFuctionData(11686): selectedAppSize: 3
,D/JsMessageQueue(11642): Set native->JS mode to OnlineEventsBridgeMode
,E/LWLocationManager(11686): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager(11686): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager(11686): setShouldUpdateLocationId
D/LWLocationManager(11686): setShouldUpdateLocationId return false
D/LWLocationManager(11686): setShouldUpdateLocationId
D/LWLocationManager(11686): setShouldUpdateLocationId return false
D/LWLocationManager(11686): setShouldUpdateLocationId
D/LWLocationManager(11686): setShouldUpdateLocationId return false
D/LWLocationManager(11686): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,D/CountryDetector( 3508): No listener is left
,I/chromium(11642): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11642): 
,D/jxcore_app_log(11642): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357424896
D/JX-Cordova(11642): jxcore cordova android initializing
,D/AcmsKeyStoreHelper(11483):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper(11483): Key Store exist
I/AcmsKeyStoreHelper(11483): Hence loading the keystore file
,D/AcmsKeyStoreHelper(11483):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr(11483): getKeyStoreForApplication success 
D/AcmsCore(11483): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor(11483): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(11483): Decrementing - Counter value: 1
D/AcmsCore(11483): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore(11483): This is NOT a valid MirrorLink app
D/AcmsCore(11483): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor(11483): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(11483): Decrementing - Counter value: 0
D/AcmsServiceMonitor(11483): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor(11483): getSvcCounter - Counter value: 0
D/AcmsService(11483): Enter onDestroy
I/AcmsService(11483): cleanUp(): inside service clean up
D/AcmsCore(11483): AcmsCore: inside DeInit
D/AcmsCore(11483): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr(11483): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr(11483): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper(11483): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface(11483): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor(11483): getSvcCounter - Counter value: 0
D/AcmsService(11483): killing acms process
I/Process (11483): Sending signal. PID: 11483 SIG: 9
,I/ActivityManager( 3508): Process ACMS.Process (pid 11483)(adj 0) has died(136,1186)
,W/jxcore-log(11642): Initializing JXcore engine
W/jxcore-log(11642): JXcore engine is ready
,W/jxcore-log(11642): Starting JXcore engine
,E/auditd  ( 4622): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3508): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3508): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11642): Platform android
W/jxcore-log(11642): 
W/jxcore-log(11642): Process ARCH arm
W/jxcore-log(11642): 
,I/jxcore-log(11642): JXcore Cordova bridge is ready!
I/jxcore-log(11642): 
W/jxcore-log(11642): JXcore engine is started
,I/jxcore-log(11642): Toggling radios to true
I/jxcore-log(11642): 
,D/BluetoothAdapter(11642): enable()
,D/BluetoothAdapter(11642): enable(): BT is already enabled..!
,D/WifiService( 3508): New client listening to asynchronous messages
,I/WifiManager(11642): packageName : com.test.thalitest
D/SecContentProvider( 3508): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3508): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3508): mCursor = null
D/WifiService( 3508): setWifiEnabled: true pid=11642, uid=10556
E/WifiService( 3508): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3508): Permission Denial: getCurrentUser() from pid=11642, uid=10556 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3508): Failed getting userId using ActivityManagerNative
W/WifiService( 3508): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11642, uid=10556 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3508): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3508): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3508): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3508): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3508): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3508): name = wifi_on
,I/WifiService( 3508): disconnect: pid=11642, uid=10556
,I/wpa_supplicant( 3823): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11642): Radios toggled
I/jxcore-log(11642): 
,I/jxcore-log(11642): My device name is: samsung-SM-N910C
I/jxcore-log(11642): 
,I/wpa_supplicant( 3823): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3823): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3823): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3823): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3508): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3823): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3823): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3823): Disconnected - do not scan
I/wpa_supplicant( 3823): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3508): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3508): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3508): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3508): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3508): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3508): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3508): do suspend true
,D/WifiP2pService( 3508): InactiveState{ what=143375 },
D/WifiP2pService( 3508): P2pEnabledState{ what=143375 }
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3689): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:"NG700"
E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
E/WifiStateMachine( 3508): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3508): updateNetworkInfo()
E/WifiConfigStore( 3508): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3508): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3508): updateNetworkInfo()
D/ConnectivityService( 3508): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
I/WifiTrafficPoller( 3508): evaluateTrafficStatsPolling
D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
E/WifiStateMachine( 3508): Start Disconnecting Watchdog 1
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
I/wpa_supplicant( 3823): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3823): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3823): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3823): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3823): First Scan Start
E/WifiStateMachine( 3508): ConnectModeState: Network connection lost 
I/wpa_supplicant( 3823): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 3508): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3508): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3508): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3508): do suspend true
,I/Hs20UtilService( 4107): Starting #8
,I/Hs20UtilService( 4107): Message received 5007
,D/NearbySettings( 8779): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8779): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8779): MountReceiver.onReceive - Create mPrefHandler
,D/WifiP2pService( 3508): InactiveState{ what=143375 }
D/WifiP2pService( 3508): P2pEnabledState{ what=143375 }
D/NearbySettings( 8779): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8779): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8779): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3508): New client listening to asynchronous messages
,I/NearbySettings( 8779): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8779): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8779): MountReceiver.onReceive - Set preference state off
D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
I/SignOutReceiver(11552): NETWORK_STATE_CHANGED_ACTION
,V/NearbySettings( 8779): MountReceiver.mPrefHandler - 7002
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3508): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3508): Not allowed due to - mEnabled false
,E/WifiStateMachine( 3508): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 3689): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3508): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3508): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiStateMachine( 3508): updateConfiguredNetworkExpiration - currTime: 1452511819109
D/WifiStateMachine( 3508): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/CSLegacyTypeTracker( 3508): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
E/WifiStateMachine( 3508): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
D/CSLegacyTypeTracker( 3508): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
E/WifiStateMachine( 3508): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService( 3508): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 6857): CM callback handler got msg 524292
I/WifiTrafficPoller( 3508): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3508): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3508): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3508): NetworkAgent: NetworkAgent channel lost
,D/TelephonyNetworkFactory( 3981): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine( 3508): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3508): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3508): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3508): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3508): mCursor = null
D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
,D/EntConnectivity( 3508): Not allowed due to - mEnabled false
D/Tethering( 3508): MasterInitialState.processMessage what=3
D/ConnectivityService( 3508): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/SmartBondingService( 3508): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3508): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
D/SmartBondingService( 3508): getSBEnabled() enabled =false
V/NetworkStats( 3508): updateIfacesLocked()
V/NetworkStats( 3508): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3508): UpdateStatsForKnox
,D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3689): updateDataNetType()
D/StatusBar.NetworkController( 3689): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3689): updateLTEICONDataNetType:0
D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
,D/SmartBondingService( 3508): getNetworkEnabled : wifi : true mobile : false
V/NetworkStats( 3508): performPollLocked() took 4ms
D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
V/NetworkStats( 3508): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 3689): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
I/Hs20UtilService( 4107): Starting #9
,I/Hs20UtilService( 4107): Message received 5007
,D/SecContentProvider2( 3508): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3508): mCursor = null
,D/NearbySettings( 8779): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8779): DMSUtil.isNetworkConnected - flag-null, state-null
,D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
I/NearbySettings( 8779): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8779): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8779): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8779): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8779): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11552): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
D/ConnectivityService( 3508): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/ApplicationPolicy( 3508): updateDataUsageMap
I/ApplicationPolicy( 3508): updateDataUsageMap  idList is null 
D/SmartBondingService( 3508): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3508): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
D/GpsLocationProvider( 3508): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3508): getNetworkEnabled : wifi : true mobile : false
W/SLocation( 3508): No Active Data Connection
I/DBG_DM  ( 6202): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
I/DBG_DM  ( 6202): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/Zygote  (11789): MountEmulatedStorage()
E/Zygote  (11789): v2
I/libpersona(11789): KNOX_SDCARD checking this for 10110
I/libpersona(11789): KNOX_SDCARD not a persona
I/SELinux (11789): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11789): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3508): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11789 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (11789): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider(11789): TimaSignature is unavailable
D/ActivityThread(11789): Added TimaKeyStore provider
D/ResourcesManager(11789): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
D/ACRA    (11789): ACRA is enabled for com.facebook.appmanager, intializing...
I/DexLibLoader(11789): not using cross-dex optimization: ART in use
I/art     (11789): Thread[1,tid=11789,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
V/DexLibLoader(11789): about to lock: /data/data/com.facebook.appmanager/mdex_lock
V/DexLibLoader(11789): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(11789): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
D/DexLibLoader(11789): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11789): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
W/art     (11789): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(11789): loading pre-built fallback odex files
V/MultiDexClassLoader(11789): installing MultiDexClassLoader before application classloader
D/DexLibLoader(11789): released odex store lock
D/DexLibLoader(11789): DexLibLoader.loadAll took 18 ms
W/ca      (11789): Verify
W/LightSharedPreferencesImpl(11789): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11789): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11789): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11789): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11789): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11789): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11789): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11789): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11789): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11789): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11789): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11789): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11789): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11789): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11789): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11789): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11789): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11789): 	... 10 more
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/Zygote  (11814): MountEmulatedStorage()
E/Zygote  (11814): v2
I/libpersona(11814): KNOX_SDCARD checking this for 1000
I/libpersona(11814): KNOX_SDCARD not a persona
I/SELinux (11814): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11814): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3508): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11814 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3508): Killing 10254:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): bgCount ##31
W/appmanager(:<default>):b(11789): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
E/SELinux (11814): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/appmanager(:<default>):b(11789): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/TimaKeyStoreProvider(11814): TimaSignature is unavailable
D/ActivityThread(11814): Added TimaKeyStore provider
D/ResourcesManager(11814): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
W/appmanager(:<default>):QuickExperimentControllerImpl(11789): Exposure of experiment com.facebook.common.network.l@9a55b09 occurred when no user was logged in
I/PCWCLIENTTRACE_LOG(11814): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11814): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11814): new DMDBOpenHelper instance
W/BroadcastQueue( 3508): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3d135e07 u0 ReceiverList{117b2c46 11789 com.facebook.appmanager/10110/u0 remote:64a6021}}
W/BroadcastQueue( 3508): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3d135e07 u0 ReceiverList{117b2c46 11789 com.facebook.appmanager/10110/u0 remote:64a6021}}
I/PCWCLIENTTRACE_PushUtil(11814): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11814): sales region : global
I/PCWCLIENTTRACE_PushUtil(11814): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11814): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver(11814): noConnectivity : true
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/Zygote  (11838): MountEmulatedStorage()
E/Zygote  (11838): v2
I/libpersona(11838): KNOX_SDCARD checking this for 10135
I/libpersona(11838): KNOX_SDCARD not a persona
I/SELinux (11838): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11838): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3508): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11838 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11838): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Killing 10413:com.android.vending/u0a31 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11838): TimaSignature is unavailable
,D/ActivityThread(11838): Added TimaKeyStore provider
,D/ResourcesManager(11838): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BroadcastQueue( 3508): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{2f68141b u0 ReceiverList{1c7f5e2a 11789 com.facebook.appmanager/10110/u0 remote:3e825b15}}
,I/MusicStore(11838): Database version: 104
,D/ResourcesManager(11838): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11838): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11838): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11838): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11838): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11838): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1faf9efe: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11838): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11838): GMSCore installation verified
,I/ConfigStore(11838): Config Database version: 1
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11789): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11838): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11789): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11838): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11838): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/appmanager(:<default>):QuickExperimentControllerImpl(11789): Exposure of experiment com.facebook.imagepipeline.a.g@f0d7eaf occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11789): Exposure of experiment com.facebook.imagepipeline.a.d@91fea8 occurred when no user was logged in
,I/wpa_supplicant( 3823): nl80211: Received scan results (6 BSSes)
,I/wpa_supplicant( 3823): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3823): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3823): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3823): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3508): [1,452,511,820,144 ms] noteScanEnd no scan source
,D/WifiDisplayAdapter( 3508): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/WifiStateMachine( 3508): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3bde2cbd sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3508): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3508): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3508): setDetailed state send new extra info
,D/SecContentProvider2( 3508): uri = 20 selection = getPromptCredentialsEnabled
D/WifiDisplayAdapter( 3508): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/SecContentProvider2( 3508): mCursor = null
,I/AudioService( 3508): getStreamVolume 3 index 0
,I/MediaRouter(11838): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/art     (11789): Explicit concurrent mark sweep GC freed 46404(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 594us total 23.625ms
,W/appmanager(:<default>):m(11789): No feature status reporters found; is this dead code?
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11872): MountEmulatedStorage()
I/libpersona(11872): KNOX_SDCARD checking this for 10002
E/Zygote  (11872): v2
I/libpersona(11872): KNOX_SDCARD not a persona
,I/SELinux (11872): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11872): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11872): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11872 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3508): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/TimaKeyStoreProvider(11872): TimaSignature is unavailable
,D/ActivityThread(11872): Added TimaKeyStore provider
,I/NetworkMonitor(11838): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager( 3508): Killing 9831:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
,D/ResourcesManager(11872): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3508): Killing 11137:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,I/wpa_supplicant( 3823): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3823): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3508): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3508): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3508): setDetailed state send new extra info"NG700"
I/wpa_supplicant( 3823): Associated with C0.AA.48
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2( 3508): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3508): mCursor = null
,E/Zygote  (11894): MountEmulatedStorage()
I/libpersona(11894): KNOX_SDCARD checking this for 1000
E/Zygote  (11894): v2
I/libpersona(11894): KNOX_SDCARD not a persona
,I/SELinux (11894): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11894): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11894): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11894 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/wpa_supplicant( 3823): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3823): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3508): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3508): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3508): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3508): mCursor = null
,D/TimaKeyStoreProvider(11894): TimaSignature is unavailable
,I/wpa_supplicant( 3823): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/ActivityThread(11894): Added TimaKeyStore provider
,I/wpa_supplicant( 3823): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3823): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3508): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3508): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3823): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3823): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3823): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3823): Blacklist: Clear (temp) 
I/wpa_supplicant( 3823): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3508): Network connection established
,D/WifiNative-HAL( 3508): callSECApiVoid - ID [50]
E/WifiStateMachine( 3508): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3508): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3508): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3508): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3508): L2ConnectedState "NG700" nid=0
D/ConnectivityService( 3508): hsengiv:checkWhatTypeOfNetwork and the value is false
E/WifiConfigStore( 3508): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3508): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3508): updateNetworkInfo()
,D/ResourcesManager(11894): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3508): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3508): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3508): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3508): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener( 2845): Setting iface cfg
,E/WifiStateMachine( 3508): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3508): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3508): mCursor = null
,E/WifiStateMachine( 3508): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3508): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DIAGMON_AGENT(11894): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(11894): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11894): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11894): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11894): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/WifiStateMachine( 3508): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3508): do suspend false
,D/SecContentProvider2( 3508): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3508): mCursor = null
D/WifiP2pService( 3508): InactiveState{ what=143375 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=143375 }
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11911): MountEmulatedStorage()
E/Zygote  (11911): v2
I/libpersona(11911): KNOX_SDCARD checking this for 10012
I/libpersona(11911): KNOX_SDCARD not a persona
,I/SELinux (11911): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11911): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11911): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11911 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 8743(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 270us total 9.648ms
,D/TimaKeyStoreProvider(11911): TimaSignature is unavailable
,D/ActivityThread(11911): Added TimaKeyStore provider
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 254us total 7.943ms
,D/ResourcesManager(11911): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 255us total 8.541ms
,I/ActivityManager( 3508): Killing 11152:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,I/FOTA_Client(11911): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11911): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11911): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11927): MountEmulatedStorage()
I/libpersona(11927): KNOX_SDCARD checking this for 10021
E/Zygote  (11927): v2
I/libpersona(11927): KNOX_SDCARD not a persona
,I/SELinux (11927): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11927): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11927): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11927 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3508): Killing 11167:com.policydm/1000 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/11167/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(11927): TimaSignature is unavailable
,D/ActivityThread(11927): Added TimaKeyStore provider
,D/ResourcesManager(11927): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (11927): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 12:30:20 GMT+01:00 2016
,I/KLMS-2.4.521: (11927): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11927): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11927): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11927): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11927): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11927): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11927): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (11927): StateImplV2(): networkChangeListener().END
,E/Zygote  (11943): MountEmulatedStorage()
I/libpersona(11943): KNOX_SDCARD checking this for 10038
E/Zygote  (11943): v2
I/libpersona(11943): KNOX_SDCARD not a persona
,I/SELinux (11943): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3508): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11943 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/SELinux (11943): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11943): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (11927): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3508): Killing 11182:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11943): TimaSignature is unavailable
,D/ActivityThread(11943): Added TimaKeyStore provider
,D/ResourcesManager(11943): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(11943): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11958): MountEmulatedStorage()
I/libpersona(11958): KNOX_SDCARD checking this for 1000
E/Zygote  (11958): v2
I/libpersona(11958): KNOX_SDCARD not a persona
,I/SELinux (11958): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11958): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3508): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11958 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11958): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Killing 11203:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,E/dhcpcd  (11964): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11964): version 5.5.6 starting
E/dhcpcd  (11964): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,W/ProcessCpuTracker( 3508): Skipping unknown process pid 11182
D/TimaKeyStoreProvider(11958): TimaSignature is unavailable
D/ActivityThread(11958): Added TimaKeyStore provider
,D/ResourcesManager(11958): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
I/dhcpcd  (11964): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11964): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (11964): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (11964): bssid match
I/dhcpcd  (11964): wlan0: rebinding lease of 192.168.1.124
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11987): MountEmulatedStorage()
I/libpersona(11987): KNOX_SDCARD checking this for 10039
E/Zygote  (11987): v2
I/libpersona(11987): KNOX_SDCARD not a persona
,I/SELinux (11987): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11987): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11987): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=11987 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3508): Killing 11216:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11987): TimaSignature is unavailable
,D/ActivityThread(11987): Added TimaKeyStore provider
,D/ResourcesManager(11987): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(11987): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(11987): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(11987): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(11987): PushLog.txt file is not deleted.
D/SPPClientService(11987): PushLog.txt file is not deleted.
D/SPPClientService(11987): ============PushLog. stop!
,I/SA      (11343): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11343): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11343): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11343): [SLFUCHKMGR] constructor called
,E/SPPClientService(11987): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11343): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11343): [OR] == isSIMCardReady false ==
,I/SA      (11343): [SCU] == networkStateCheck == false
I/SA      (11343): [OR] onReceive END
,V/DownloadManager( 3714): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 3508): Killing 11234:com.wsomacp/u0a28 (adj 15): bgCount ##31
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12007): MountEmulatedStorage()
I/libpersona(12007): KNOX_SDCARD checking this for 10067
E/Zygote  (12007): v2
I/libpersona(12007): KNOX_SDCARD not a persona
,I/SELinux (12007): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12007): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12007): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12007 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12007): TimaSignature is unavailable
,D/ActivityThread(12007): Added TimaKeyStore provider
,D/ResourcesManager(12007): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12007): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12007): Other Intent
,I/ActivityManager( 3508): Killing 11033:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/11033/oom_score_adj; errno=22
,D/accuweather( 5158): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3773): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 5158): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5158): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5158): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5158): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5158): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5158): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12023): MountEmulatedStorage()
E/Zygote  (12023): v2
I/libpersona(12023): KNOX_SDCARD checking this for 1000
I/libpersona(12023): KNOX_SDCARD not a persona
,I/SELinux (12023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12023): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12023 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12023): TimaSignature is unavailable
,D/ActivityThread(12023): Added TimaKeyStore provider
,D/ResourcesManager(12023): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12023): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12023): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12023): premStatus:2
,I/KnoxUsageLogPro(12023): isEulaShown : false
I/KnoxUsageLogPro(12023): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12038): MountEmulatedStorage()
E/Zygote  (12038): v2
I/libpersona(12038): KNOX_SDCARD checking this for 10090
I/libpersona(12038): KNOX_SDCARD not a persona
,I/SELinux (12038): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12038): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12038): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12038 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3508): Killing 11272:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12038): TimaSignature is unavailable
,D/ActivityThread(12038): Added TimaKeyStore provider
,D/ResourcesManager(12038): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12054): MountEmulatedStorage()
E/Zygote  (12054): v2
I/libpersona(12054): KNOX_SDCARD checking this for 10127
I/libpersona(12054): KNOX_SDCARD not a persona
,I/SELinux (12054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12054): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12054 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3508): Killing 11256:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12054): TimaSignature is unavailable
,D/ActivityThread(12054): Added TimaKeyStore provider
,D/ResourcesManager(12054): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12054): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12054): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12054): stopCheckCategoryVersion
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12071): MountEmulatedStorage()
I/libpersona(12071): KNOX_SDCARD checking this for 10136
E/Zygote  (12071): v2
I/libpersona(12071): KNOX_SDCARD not a persona
,I/SELinux (12071): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12071): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12071): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12071 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3508): Killing 11321:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12071): TimaSignature is unavailable
,D/ActivityThread(12071): Added TimaKeyStore provider
,D/ResourcesManager(12071): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12071): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12071): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12071): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12071): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager( 3508): Killing 11291:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,I/WebViewFactory(12071): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12071): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12071): Loading: webviewchromium
,I/LibraryLoader(12071): Time to load native libraries: 3 ms (timestamps 1313-1316)
I/LibraryLoader(12071): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12071): Binding Chromium to main looper Looper (main, tid 1) {2ee2ad0a}
,I/LibraryLoader(12071): Expected native library version number "",actual native library version number ""
,I/chromium(12071): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12071): Initializing chromium process, renderers=0
,W/art     (12071): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12071): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12071): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12071): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid(12071): Requires BLUETOOTH permission
,I/NSApplication(12071): Starting up...
,I/ActivityManager( 3508): Killing 11414:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/11414/oom_score_adj; errno=22
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12139): MountEmulatedStorage()
I/libpersona(12139): KNOX_SDCARD checking this for 10150
E/Zygote  (12139): v2
I/libpersona(12139): KNOX_SDCARD not a persona
,I/SELinux (12139): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12139): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12139): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12139 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12139): TimaSignature is unavailable
,D/ActivityThread(12139): Added TimaKeyStore provider
,D/ResourcesManager(12139): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12139): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12139): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12139): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12139): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12139): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12139): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12154): MountEmulatedStorage()
E/Zygote  (12154): v2
I/libpersona(12154): KNOX_SDCARD checking this for 10178
I/libpersona(12154): KNOX_SDCARD not a persona
,I/SELinux (12154): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12154): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12154): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12154 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3508): Killing 11432:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 8756(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 702us total 10.708ms
,D/TimaKeyStoreProvider(12154): TimaSignature is unavailable
,D/ActivityThread(12154): Added TimaKeyStore provider
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 359us total 14.817ms
,D/ResourcesManager(12154): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 683us total 8.524ms
,W/ResourcesManager(12154): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12154): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12154): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12154): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12154): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12154): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3508): exchangeData() failure , invalid userId
,D/RCPManagerService( 3508): exchangeData() failure , invalid userId
,D/RCPManagerService( 3508): exchangeData() failure , invalid userId
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 3508): exchangeData() failure , invalid userId
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3508): exchangeData() failure , invalid userId
,E/Zygote  (12178): MountEmulatedStorage()
E/Zygote  (12178): v2
I/libpersona(12178): KNOX_SDCARD checking this for 10082
I/SELinux (12178): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/libpersona(12178): KNOX_SDCARD not a persona
,I/SELinux (12178): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12178): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12178 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/RCPManagerService( 3508): exchangeData() failure , invalid userId
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12178): TimaSignature is unavailable
,D/ActivityThread(12178): Added TimaKeyStore provider
,E/Zygote  (12194): MountEmulatedStorage()
E/Zygote  (12194): v2
I/libpersona(12194): KNOX_SDCARD checking this for 1000
I/libpersona(12194): KNOX_SDCARD not a persona
,I/SELinux (12194): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12194): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12194): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12194 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3508): Killing 11399:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,I/ActivityManager( 3508): Killing 11451:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12194): TimaSignature is unavailable
,D/ActivityThread(12194): Added TimaKeyStore provider
,I/art     ( 3508): Explicit concurrent mark sweep GC freed 50341(2MB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 49MB/65MB, paused 1.276ms total 77.140ms
,D/ResourcesManager(12194): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/ResourcesManager(12178): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider(12178): onCreate
,D/BadgeProvider(12178): DatabaseHelper
,I/ActivityManager( 3508): Killing 11464:com.samsung.helphub/1000 (adj 13): bgCount ##31
,W/ActivityManager( 3508): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/BadgeProvider(12178): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider(12178): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12178): sendNotify, [notify] : null
D/BadgeProvider(12178): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider(12178): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12178): update, [UpdateCount] : 1
D/Launcher.Model( 3997): reloadBadges entered.
,I/iu.Environment( 6857): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6857): num queued entries: 0
,I/iu.UploadsManager( 6857): num updated entries: 0
I/iu.SyncManager( 6857): NEXT; no task
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12214): MountEmulatedStorage()
I/libpersona(12214): KNOX_SDCARD checking this for 10013
E/Zygote  (12214): v2
I/libpersona(12214): KNOX_SDCARD not a persona
I/SELinux (12214): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12214): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12214): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12214 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12214): TimaSignature is unavailable
,D/ActivityThread(12214): Added TimaKeyStore provider
,D/ResourcesManager(12214): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/ActivityManager( 3508): Killing 11578:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,I/Hs20UtilService( 4107): Starting #10
,I/Hs20UtilService( 4107): Message received 5007
,D/NearbySettings( 8779): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8779): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8779): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8779): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8779): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8779): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8779): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11552): NETWORK_STATE_CHANGED_ACTION
,I/GAV2    (11500): Thread[GAThread,5,main]: No campaign data found.
,I/dhcpcd  (11964): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (11964): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3508): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3508): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/ActivityManager( 3508): Killing 11595:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/11595/oom_score_adj; errno=22
,E/WifiStateMachine( 3508): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3508): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3508): do suspend true
,D/WifiP2pService( 3508): InactiveState{ what=143375 }
D/WifiP2pService( 3508): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3508): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3508): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3508): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3508): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3508): Not connected state, yet.
E/WifiStateMachine( 3508): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3508): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3508): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3508): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3508): callSECApiInt - ID [210]
,E/WifiStateMachine( 3508): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3508): updateNetworkInfo()
,D/ConnectivityService( 3508): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3508): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3508): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3508): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3508): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3508): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3508): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 4107): Starting #11
,I/Hs20UtilService( 4107): Message received 5007
,D/NearbySettings( 8779): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8779): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 3508): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 3508): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 3508): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3508): Unexpected mtu value: 0, wlan0
V/        ( 2845): QcRouteController
,I/SignOutReceiver(11552): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,E/WifiStateMachine( 3508): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine( 3508): Now, connected state.
E/WifiStateMachine( 3508): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
E/WifiStateMachine( 3508): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3508): evaluateTrafficStatsPolling
,V/        ( 2845): QcRouteController
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 4107): Starting #12
,E/WifiStateMachine( 3508): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 3508): evaluateTrafficStatsPolling
D/WifiNative-HAL( 3508): callSECApiVoid - ID [212],
I/Hs20UtilService( 4107): Message received 5007
V/        ( 2845): QcRouteController
,E/WifiStateMachine( 3508): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3508): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 3689): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
V/        ( 2845): QcRouteController
,D/NearbySettings( 8779): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8779): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8779): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8779): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8779): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8779): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8779): MountReceiver.mPrefHandler - 7002
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,I/SignOutReceiver(11552): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService( 3508): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 3508): LTETest block dns file not exists
I/Hs20UtilService( 4107): Starting #13
,I/Hs20UtilService( 4107): Message received 5007
,D/NearbySettings( 8779): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8779): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 3508): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3508): updateNetworkInfo()
D/ConnectivityService( 3508): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3508): updateNetworkInfo()
D/ConnectivityService( 3508): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3508): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3508): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3508): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3508): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3508): Checking http://clients3.google.com/generate_204 on "NG700"
,I/System.out( 3508): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 3508):    accepting network in place of null
,E/CSLegacyTypeTracker( 3508): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/TelephonyNetworkFactory( 3981): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 3508): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3508): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/WifiStateMachine( 3508): callSECApi what=220
D/WifiStateMachine( 3508): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
D/ConnectivityService( 3508): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 3508): MasterInitialState.processMessage what=3
D/EntConnectivity( 3508): Not allowed due to - mEnabled false
D/SmartBondingService( 3508): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 3508): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/SmartBondingService( 3508): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/ConnectivityManager.CallbackHandler( 3689): CM callback handler got msg 524290
D/SmartBondingService( 3508): getSBEnabled() enabled =false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
,D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
V/NetworkStats( 3508): updateIfacesLocked()
V/NetworkStats( 3508): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3508): UpdateStatsForKnox
,D/ConnectivityManager.CallbackHandler( 6857): CM callback handler got msg 524290
D/SmartBondingService( 3508): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
V/NetworkStats( 3508): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,V/NetworkStats( 3508): performPollLocked() took 3ms
D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3689): updateDataNetType()
D/StatusBar.NetworkController( 3689): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3689): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3689): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3689): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
I/SignOutReceiver(11552): NETWORK_STATE_CHANGED_ACTION
,I/SurfaceFlinger( 2850): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3508): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3508
,D/mali_winsys( 3689): new_window_surface returns 0x3000,  [1120x201]-format:1
,I/System.out( 3508): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3508): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 11:30:22 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452511822405], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452511822376]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3508): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3508): Validated
D/ConnectivityService( 3508): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3508): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3508): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3508): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3689): CM callback handler got msg 524290
D/ConnectivityService( 3508): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 6857): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3689): updateDataNetType()
D/StatusBar.NetworkController( 3689): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3689): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3689): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3689): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/ConnectivityService( 3508): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3508): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3508): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3508): SmartBondingReceiver: wifi ap is not changed
D/SmartBondingService( 3508): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
,D/SmartBondingService( 3508): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3508): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 6202): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6202): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/ResourceType( 5370): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5370): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/NetworkMonitor(11838): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil(11814): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11814): sales region : global
I/PCWCLIENTTRACE_PushUtil(11814): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11814): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11894): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11894): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 3508): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3508): mCursor = null
,I/FOTA_Client(11911): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11911): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11911): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (11927): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 12:30:22 GMT+01:00 2016
,I/KLMS-2.4.521: (11927): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11927): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11927): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11927): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11927): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/SO_AGENT(11943): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (11927): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11927): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11927): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11927): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (11927): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11927): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (11927): KLMSIntentService(): onDestroy()
,E/SPPClientService(11987): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11343): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11343): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11343): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11343): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11343): [OR] == isSIMCardReady false ==
,I/SA      (11343): [SCU] == networkStateCheck == true
I/SA      (11343): [DM] getCountryCodeFromCSC : PL
I/SA      (11343): isChinaCountryCode : false
I/SA      (11343): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11343): [OR] == networkStateCheck true ==
,I/SA      (11343): [OR] GetMyCountryZoneTask
I/SA      (11343): [OR] onReceive END
,I/SA      (11343): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 3714): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11343): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11343): [SSP] query invoked
,I/SA      (11343): [TPMU] GetMccFromDB : null
I/SA      (11343): [SCU] getMccFromPreferece mcc = 260
I/SA      (11343): [TPM] isNoProxy(default) : true
,I/SCloudBackupReceiver(12007): Other Intent
,D/accuweather( 5158): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3773): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 5158): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5158): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5158): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5158): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5158): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5158): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12023): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12023): premStatus:2
,I/KnoxUsageLogPro(12023): isEulaShown : false
I/KnoxUsageLogPro(12023): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12054): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12054): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12054): stopCheckCategoryVersion
,D/QuickConnect(12139): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12139): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12139): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3508): exchangeData() failure , invalid userId
,D/RCPManagerService( 3508): exchangeData() failure , invalid userId
,I/iu.Environment( 6857): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6857): num queued entries: 0
,I/iu.UploadsManager( 6857): num updated entries: 0
,I/iu.SyncManager( 6857): NEXT; no task
,D/WaitQueueForNetworkActivate(12214): notifyNetworkActivated
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10014
,W/ContextImpl(12214): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3508): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12214): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12214): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12214): exit::IDLE
D/InitializeManagerStateMachine(12214): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12214): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12214): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12214): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12214): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12214): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12214): entry::SUCCESS
D/hcjo    (12214): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12214): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12214): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12214): exit::SUCCESS
D/InitializeManagerStateMachine(12214): entry::IDLE
,I/SA      (11343): [RC New] Execute method=[GET] start
,I/SA      (11343): [RC New] Security=[true]
,I/System.out(11343): Thread-1545(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11343): Thread-1545(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11343): Thread-1545(ApacheHTTPLog):isShipBuild true
I/System.out(11343): Thread-1545(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3508): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SA      (11343): [RC New] [v2liruge] api execute + 591
I/SA      (11343): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11343): AsyncTask #1 calls detatch()
,I/SA      (11343): [TPMU] getNetworkMcc : 
,I/SA      (11343): [SCU] saveMccToPreferece Start
I/SA      (11343): [SCU] RegionMCC : 260
I/SA      (11343): [SSP] query invoked
,I/SA      (11343): [TPMU] GetMccFromDB : null
I/SA      (11343): [SCU] getMccFromPreferece mcc = 260
I/SA      (11343): [SCU] saveMccToPreferece End
,I/SA      (11343): [RC New] executeRequest [v2liruge] end. 612
I/SA      (11343): [RC New] Execute end
I/SA      (11343): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11343): [OR] GetMyCountryZoneTask Success
,V/AlarmManager( 3508): waitForAlarm result :4
,V/AlarmManager( 3508): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 3508): <AppSync3 Whitelist>
V/AlarmManager( 3508): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 3689): handleTimeUpdate
,D/KeyguardEffectViewController( 3689): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3689): *** don't update sliding image ***
,D/DateView( 3689): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3689): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3508): SIOP:: AP = 330, PST = 277, CUR = -73
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4334, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3508): online:4, current avg:-532, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-329
D/BatteryService( 3508): stay LED for fully charged
D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5657): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5657): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3508): [PWL] Off : 30s ago
,I/jxcore-log(11642): Test app app.js loaded
I/jxcore-log(11642): 
,I/Choreographer(11642): Skipped 303 frames!  The application may be doing too much work on its main thread.
,I/chromium(11642): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium(11642): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/WifiStateMachine( 3508): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService( 3508): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2845): QcRouteController
,E/WifiStateMachine( 3508): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,I/dhcpcd  (11964): wlan0: sending IPv6 Router Solicitation
,D/SmartBondingService( 3508): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3508): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3508): getSBEnabled() enabled =false
,D/SmartBondingService( 3508): getSBEnabled() enabled =false
,D/SmartBondingService( 3508): getSBEnabled() enabled =false
,V/        ( 2845): QcRouteController
,W/NetworkManagementService( 3508): route cmd failed: 
W/NetworkManagementService( 3508): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3508): '
W/NetworkManagementService( 3508): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3508): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3508): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3508): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3508): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3508): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3508): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3508): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3508): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3508): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3508): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3508): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3508): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3689): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6857): CM callback handler got msg 524295
D/ConnectivityService( 3508): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3689): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6857): CM callback handler got msg 524295
,D/WearableService( 4645): callingUid 10014, callindPid: 4645
,D/ResourcesManager(11838): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11838): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(11838): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11838): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11838): Conditions not met for autocaching.
I/MusicLeanback(11838): Stop autocaching.
,D/WearableClient(11838): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11838): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11838): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11838): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11838): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11838): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11838): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2fbb0296 that was originally bound here
E/ActivityThread(11838): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2fbb0296 that was originally bound here
E/ActivityThread(11838): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11838): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11838): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11838): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11838): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11838): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11838): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11838): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11838): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11838): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11838): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11838): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11838): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11838): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11838): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11838): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11838): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11838): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11838): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11838): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11838): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11838): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11838): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11838): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11838): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/WifiStateMachine( 3508): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3508): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,W/ProcessCpuTracker( 3508): Skipping unknown process pid 12334
,I/SurfaceFlinger( 2850): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2850): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3508): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3508) eventTime = 125975
,D/PowerManagerService( 3508): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3508 (0x0)
D/PowerManagerService( 3508): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3508, ws=WorkSource{10060}) (elapsedTime=3471)
,D/PackageManager( 3508): [MSG] MCS_UNBIND
,I/ActivityManager( 3508): Killing 11615:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/GAV4    (12071): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PackageManager( 3508): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/PCWCLIENTTRACE_SYSTEMReceiver(11814): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11814): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11814): ================================================
,I/CSTORAGE(11814):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11814): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11814): [GetString-S]
E/art     (11814): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI(11814): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11814): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11814): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11814): sales region : global
I/PCWCLIENTTRACE_PushUtil(11814): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11814): [ensureRegistration] - No Samsung account
,I/dhcpcd  (11964): wlan0: sending IPv6 Router Solicitation
,V/AlarmManager( 3508): waitForAlarm result :4
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12385): MountEmulatedStorage()
E/Zygote  (12385): v2
I/libpersona(12385): KNOX_SDCARD checking this for 10031
I/libpersona(12385): KNOX_SDCARD not a persona
,I/SELinux (12385): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3508): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=12385 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12385): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12385): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12385): TimaSignature is unavailable
,D/ActivityThread(12385): Added TimaKeyStore provider
,D/ResourcesManager(12385): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,W/ProcessCpuTracker( 3508): Skipping unknown process pid 12384
,D/Finsky  (12385): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  (12385): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings(12385): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings(12385): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SQLiteLog(11527): (283) recovered 720 frames from WAL file /data/user/0/com.google.android.gsf/databases/googlesettings.db-wal
,D/Ads     (12385): Skipping gmscore version check
,D/Finsky  (12385): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  (12385): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  (12385): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  (12385): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager( 3508): Waited long enough for: ServiceRecord{3c5462f1 u0 com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayService}
,D/Finsky  (12385): [1750] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  (12385): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/dhcpcd  (11964): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (11964): wlan0: no IPv6 Routers available
,E/Watchdog( 3508): !@Sync 4
,D/PreloadUpdateManagerStateMachine(12214): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12214): exit::IDLE
D/PreloadUpdateManagerStateMachine(12214): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12214): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12214): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12214): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12214): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12214): entry::IDLE
,D/SSRM:n  ( 3508): SIOP:: AP = 290, PST = 272, CUR = -532
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:-132, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:137
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5657): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5657): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3508): SIOP:: AP = 270, PST = 280, CUR = -132,
,I/PowerManagerService( 3508): [PWL] Off : 50s ago
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:103
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5657): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5657): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3508): SIOP:: AP = 260, PST = 277, CUR = 17
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3508): online:4, current avg:68, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:86
D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5657): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5657): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3508): Killing 11711:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,V/AlarmManager( 3508): waitForAlarm result :8
,W/ProcessCpuTracker( 3508): Skipping unknown process pid 12516
,E/Watchdog( 3508): !@Sync 5
,D/SSRM:n  ( 3508): SIOP:: AP = 250, PST = 276, CUR = 68
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:81, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:87
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5657): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5657): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3508): [PWL] Off : 75s ago
,D/SSRM:n  ( 3508): SIOP:: AP = 250, PST = 276, CUR = 81
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:81, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:78
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5657): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5657): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3508): SIOP:: AP = 250, PST = 275, CUR = 81
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:77, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:74
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5657): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5657): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3508): !@Sync 6
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 273, CUR = 77
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:72, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:77
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5657): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5657): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3508): [PWL] Off : 105s ago
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 272, CUR = 72
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:70, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:60
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5657): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5657): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 271, CUR = 70
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:66, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:61
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5657): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5657): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3508): !@Sync 7
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 267, CUR = 66
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:63, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5657): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5657): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3508): [PWL] Off : 140s ago
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 263, CUR = 63
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3508): online:4, current avg:59, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged,
I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5657): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5657): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4645): disconnect managed GoogleApiClient
,V/AlarmManager( 3508): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3689): handleTimeUpdate
,D/KeyguardEffectViewController( 3689): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3689): *** don't update sliding image ***
,D/DateView( 3689): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3689): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 261, CUR = 59,
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:56, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:73
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5657): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5657): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3508): !@Sync 8
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 260, CUR = 56
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5657): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5657): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/jxcore-log(11642): --= Surplus to requirements =--
I/jxcore-log(11642): 
I/jxcore-log(11642): ****TEST TOOK:  ms ****
I/jxcore-log(11642): 
I/jxcore-log(11642): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11642): 
,D/AndroidRuntime(12596): 
D/AndroidRuntime(12596): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12596): CheckJNI is OFF
,D/AndroidRuntime(12596): readGMSProperty: start
D/AndroidRuntime(12596): readGMSProperty: already setted!!
,D/AndroidRuntime(12596): readGMSProperty: end
D/AndroidRuntime(12596): addProductProperty: start
,E/AffinityControl(12596): AffinityControl: registerfunction enter
,D/AndroidRuntime(12596): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3508): START PACKAGE DELETE: observer{484738826}
D/PackageManager( 3508): pkg{<packageName>}
D/PackageManager( 3508): user{0}
D/PackageManager( 3508): caller{2000}
D/PackageManager( 3508): flags{3}
,D/PersonaManagerService( 3508): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3508): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 3508): [MSG] DELETE_PACKAGE_AS_USER
,D/PersonaManagerService( 3508): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3508): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3508): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3508): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 3508): !@killApplicatoin: 10556, uninstall pkg
,D/PackageManagerService( 3508): deletePackage- pkg:com.test.thalitest, edmuserId:-1
I/ActivityManager( 3508): Force stopping com.test.thalitest appid=10556 user=-1: uninstall pkg
D/ApplicationPolicy( 3508): getApplicationUninstallationEnabled
I/ActivityManager( 3508): Killing 11642:com.test.thalitest/u0a556 (adj 0): stop com.test.thalitest
,D/ApplicationPolicy( 3508): getApplicationUninstallationEnabled :  enabled true
,I/ActivityManager( 3508):   Force finishing activity ActivityRecord{1a90440c u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3508): mDVFSHelper.acquire()
,W/PackageSettings( 3508): Skipping PackageSetting{a0ea331 com.example.hello/10549} due to missing metadata
,I/ActivityManager( 3508): Force stopping com.test.thalitest appid=10556 user=0: pkg removed
,I/ActivityManager( 3508):   Force finishing activity ActivityRecord{1a90440c u0 com.test.thalitest/.MainActivity t26 f}
E/JavaBinder( 3508): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager( 3508): Duplicate finish request for ActivityRecord{1a90440c u0 com.test.thalitest/.MainActivity t26 f}
,D/PointerIcon( 3508): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3508): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3508): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3508): setHoveringSpenCustomIcon IconType is same.1
,I/WindowState( 3508): WIN DEATH: Window{1a058d1f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 3508): Client connection lost with reason: 4
,I/SurfaceFlinger( 2850): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2850): id=14 Removed NainActivit (-2/8)
,I/DBG_DM  ( 6202): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,I/DBG_DM  ( 6202): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 9
,I/art     ( 6857): Explicit concurrent mark sweep GC freed 28300(1598KB) AllocSpace objects, 3(48KB) LOS objects, 20% free, 31MB/39MB, paused 1.414ms total 72.911ms
,I/DBG_DM  ( 6202): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 8937): Explicit concurrent mark sweep GC freed 28463(1608KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 714us total 67.155ms
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/InputReader( 3508): Reconfiguring input devices.  changes=0x00000010
,I/DBG_DM  ( 6202): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6202): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 9
,I/art     ( 4051): Explicit concurrent mark sweep GC freed 33283(2040KB) AllocSpace objects, 1(39KB) LOS objects, 21% free, 28MB/36MB, paused 1.340ms total 56.305ms
,I/DBG_DM  ( 6202): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,E/SamsungIME( 4454): mOCRHelper is null
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,W/GeofencerStateMachine( 4645): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 6202): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/LWLocationManager(11686): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11686): getLastUiLocationId() : mLastUiLocationId = -100
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/Zygote  (12615): MountEmulatedStorage()
E/Zygote  (12615): v2
I/libpersona(12615): KNOX_SDCARD checking this for 10063
I/libpersona(12615): KNOX_SDCARD not a persona
,I/SELinux (12615): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3508): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12615 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12615): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12615): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 6202): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,W/ResourceType( 5370): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
,W/ResourceType( 5370): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/SecContentProvider2( 3508): uri = 14 selection = getSealedState
D/SecContentProvider2( 3508): mCursor = null
,D/ApplicationPolicy( 3508): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3508): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/DBG_DM  ( 6202): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 9
,I/DBG_DM  ( 6202): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,D/TimaKeyStoreProvider(12615): TimaSignature is unavailable
,D/EnterpriseDeviceManagerService( 3508): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3508): Admin package name: com.google.android.gms
D/ActivityThread(12615): Added TimaKeyStore provider
,I/DBG_DM  ( 6202): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6202): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
D/ResourcesManager(11686): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/DBG_DM  ( 6202): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6202): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6202): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3508): post active user change for 0
D/KnoxTimeoutHandler( 3508): postActiveUserChange for user 0
,I/DBG_DM  ( 6202): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,I/SurfaceFlinger( 2850): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/ResourcesManager(12615): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/StatusBarManagerService( 3508): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3508): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/PointerIcon( 3508): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3508): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3508): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3508): setHoveringSpenCustomIcon IconType is same.1
,V/ActivityThread( 6202): updateVisibility : ActivityRecord{94a06eb token=android.os.BinderProxy@201604dc {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/VRSetupWizardStub/PackageIntentReceiver(12615): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12615): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12615): packagename:com.test.thalitest
,D/ResourcesManager(11686): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/art     ( 3508): Explicit concurrent mark sweep GC freed 70864(4MB) AllocSpace objects, 50(800KB) LOS objects, 24% free, 49MB/65MB, paused 2.737ms total 223.362ms
,I/art     ( 3508): WaitForGcToComplete blocked for 196.045ms for cause Explicit
,D/ResourcesManager( 3508): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(11686): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/InputMethodManagerService( 3508): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/KLMS-2.4.521: (11927): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 12:32:38 GMT+01:00 2016
,D/ResourcesManager(11686): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/KLMS-2.4.521: (11927): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3508): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
,I/splitIntent( 3508): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,W/InputMethodManagerService( 3508): Got RemoteException sending setActive(false) notification to pid 11642 uid 10556
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(11686): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/Timeline( 6202): Timeline: Activity_idle id: android.os.BinderProxy@201604dc time:258892
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/KLMS-2.4.521: (11927): KLMSIntentService(): onCreate()
W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/KLMS-2.4.521: (11927): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11927): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ResourcesManager(11686): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,I/KLMS-2.4.521: (11927): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11927): KLMSIntentService(): PACKAGE_REMOVED
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
D/RCPManager(12023):  in createShortcut() for packageName: com.test.thalitest userId0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3508):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3508): queryAllProviders():  providerCallBack is not register for 0
,I/KLMS-2.4.521: (11927): KLMSIntentService(): listeningToPackageRemoved().START
,D/SecContentProvider2( 3508): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3508): mCursor = null
I/KLMS-2.4.521: (11927): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(11686): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/Zygote  (12636): MountEmulatedStorage()
E/Zygote  (12636): v2
I/libpersona(12636): KNOX_SDCARD checking this for 10106
I/libpersona(12636): KNOX_SDCARD not a persona
,I/SELinux (12636): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
I/SELinux (12636): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12636): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
D/ResourcesManager( 3508): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
I/ActivityManager( 3508): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12636 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(11686): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,W/ActivityManager( 3508): mDVFSHelper.release()
I/Timeline( 3508): Timeline: Activity_windows_visible id: ActivityRecord{22c4879e u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:258957
,D/ResourcesManager(11686): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/RegisteredServicesCache( 3963): empty dynamic service
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12636): TimaSignature is unavailable
E/Zygote  (12652): MountEmulatedStorage()
I/libpersona(12652): KNOX_SDCARD checking this for 10050
E/Zygote  (12652): v2
I/libpersona(12652): KNOX_SDCARD not a persona
,I/KLMS-2.4.521: (11927): KLMSIntentService(): listeningToPackageRemoved().END
D/ActivityThread(12636): Added TimaKeyStore provider
I/SELinux (12652): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12652): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3508): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12652 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux (12652): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11686): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11686): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (11927): KLMSIntentService(): onDestroy()
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12652): TimaSignature is unavailable
,D/ActivityThread(12652): Added TimaKeyStore provider
,D/ResourcesManager(12636): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,I/art     ( 3508): Explicit concurrent mark sweep GC freed 8937(439KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 2.153ms total 160.353ms
,E/Zygote  (12667): MountEmulatedStorage()
E/Zygote  (12667): v2
I/libpersona(12667): KNOX_SDCARD checking this for 10183
I/libpersona(12667): KNOX_SDCARD not a persona
,I/SELinux (12667): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12667): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12667): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12667 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,D/ResourcesManager(11686): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/elm:14491(12636): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12636): ELMEngine.ELMEngine( context ).
,D/elm:14491(12636): MDMBridge.setEnterpriseBridge()
,D/TimaKeyStoreProvider(12667): TimaSignature is unavailable
,D/ActivityThread(12667): Added TimaKeyStore provider
,D/ResourcesManager(11686): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourceType( 3508): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/elm:14491(12636): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
D/elm:14491(12636): ElmAgentService : onCreate()
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
D/elm:14491(12636): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/ResourcesManager(12652): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager(11686): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager(12652): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12652): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12652): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12652): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12652): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(12652): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager(12652): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(12652): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/elm:14491(12636): MainReceiver.listeningToPackageRemoved()
D/PackageManager( 3508): delete codoeFile: 
D/elm:14491(12636): MDMBridge.getInstance()
D/elm:14491(12636): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491(12636): MDMBridge.getAllLicenseInfoFromSDK()
,I/AASAUninstall( 3508):  com.test.thalitest not target!
,D/ResourcesManager(11686): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/Zygote  (12683): MountEmulatedStorage()
E/Zygote  (12683): v2
I/libpersona(12683): KNOX_SDCARD checking this for 10101
I/libpersona(12683): KNOX_SDCARD not a persona
W/ResourcesManager(11686): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11686): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11686): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11686): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/SELinux (12683): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3508): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12683 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12683): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12683): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/PackageManager( 3508): result of delete: 1{484738826}
,D/AndroidRuntime(12596): Shutting down VM
,D/ResourcesManager(11686): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,I/ActivityManager( 3508): Killing 11733:com.android.calendar/u0a164 (adj 13): bgCount ##31
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11686): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12683): TimaSignature is unavailable
,D/ActivityThread(12683): Added TimaKeyStore provider
,E/Zygote  (12699): MountEmulatedStorage()
E/Zygote  (12699): v2
I/libpersona(12699): KNOX_SDCARD checking this for 10019
I/libpersona(12699): KNOX_SDCARD not a persona
I/SELinux (12699): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12699): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12699): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12699 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/ResourcesManager(12667): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/elm:14491(12636): ElmAgentService : onDestroy().
,D/ResourcesManager(11686): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/ActivityManager( 3508): Killing 11686:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,D/ResourcesManager(12683): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/TimaKeyStoreProvider(12699): TimaSignature is unavailable
,D/ActivityThread(12699): Added TimaKeyStore provider
,E/SQLiteLog(12667): (284) automatic index on shooting_modes(title_id)
,D/ResourcesManager(12699): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,E/Zygote  (12715): MountEmulatedStorage()
E/Zygote  (12715): v2
I/libpersona(12715): KNOX_SDCARD checking this for 10190
I/libpersona(12715): KNOX_SDCARD not a persona
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
I/SELinux (12715): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12715): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,E/SELinux (12715): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12715 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Books/Books.apk
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/art     ( 2883): Explicit concurrent mark sweep GC freed 8708(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.292ms total 26.880ms
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12699): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12699): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12699): onReceive() : package name is not s health. Return !!!
,D/TimaKeyStoreProvider(12715): TimaSignature is unavailable
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ActivityThread(12715): Added TimaKeyStore provider
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 353us total 13.393ms
,D/DocsApplication(12683): Installing DEX configuration.
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/ActivityManager( 3508): Killing 12178:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 344us total 11.043ms
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/PackageManager( 3508): findPreferredActivity: No PreferredActivities set
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(12715): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,E/Zygote  (12732): MountEmulatedStorage()
E/Zygote  (12732): v2
I/libpersona(12732): KNOX_SDCARD checking this for 10022
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/libpersona(12732): KNOX_SDCARD not a persona
,I/SELinux (12732): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
I/SELinux (12732): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12715): onReceive()
E/SELinux (12732): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12732 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
D/TapandpayWidget:TanpandpayAppWidgetProvider(12715): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Videos/Videos.apk
W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/ActivityManager( 3508): Killing 8779:com.android.settings/1000 (adj 13): bgCount ##31
,I/TapandpayWidget:Utils(12715): Clear T&P info.
,D/DexInstaller(12683): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
D/TapandpayWidget:TanpandpayAppWidgetProvider(12715): Widget is not attached.
,I/ActivityManager( 3508): Killing 11814:com.sec.pcw.device/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12732): TimaSignature is unavailable
,D/ActivityThread(12732): Added TimaKeyStore provider
,I/PackageInfoHelper(12683): Provided clientMode=RELEASE, packageInfo=PackageInfo{3cd4b543 com.google.android.apps.docs}
,D/TAG     (12683): onCreate()
D/PackageBroadcastService( 6857): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 6857): Clearing selected account for com.test.thalitest
,W/ResourcesManager( 3508): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3508): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3508): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3508): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
D/ResourcesManager(12732): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12732): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12732): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12732): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/CrossAppStateProvider(12683): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,I/LocationSettingsChecker( 6857): Removing dialog suppression flag for package com.test.thalitest
,D/RCPManagerService( 3508): PackageReceiver onReceive()
I/HarmonyEASService( 3508): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/KnoxMUMContainerPolicy( 3508): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3508): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3508): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3508): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3508): uID is 10556
V/EnterpriseBillingPolicy( 3508): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3508): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3508): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3508): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3508): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3508): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3508): getBillingProfileForVpnEngine - end - null
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/WifiService( 3508): Client connection lost with reason: 4
,D/ChimeraCfgMgr( 6857): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6857): Module APK com.google.android.play.games already loaded
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,I/LocationWidgetApplication(12732): onCreate() : start
,D/LocationWidgetApplication(12732): countryCode = POLAND
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/gH_CompatibleDatabase( 6857): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6857): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/gH_MetricsDatabase( 6857): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6857): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 6857): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 6857): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 6857): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 6857): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6857): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 6857): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 6857): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 6857): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6857): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/UsbSettingsManager( 3508): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3508): onPackageRemoved : com.test.thalitest
,E/TaskPersister( 3508): Unable to open android.util.AtomicFile@2da7532e for persisting. java.io.IOException: Couldn't create directory /data/system/recent_tasks/24_task.xml
,D/TaskPersister( 3508): removeObsoleteFile: deleting file=26_task.xml
,D/KnoxTimeoutHandler( 3508): handleActiveUserChange for user 0
,W/System.err( 3508): java.io.FileNotFoundException: /data/system/harmony_third_party_apps.xml.tmp: open failed: EROFS (Read-only file system)
,W/System.err( 3508): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/SQLiteLog( 4645): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4645): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteLog( 6857): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
W/System.err( 3508): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 3508): 	at com.android.server.HarmonyEASService.saveHash(HarmonyEASService.java:303)
D/AndroidRuntime( 4645): Shutting down VM
,W/System.err( 3508): 	at com.android.server.HarmonyEASService.access$000(HarmonyEASService.java:60)
W/System.err( 3508): 	at com.android.server.HarmonyEASService$PackageHandler.handleMessage(HarmonyEASService.java:100)
W/System.err( 3508): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6857): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 6857): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6857): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6857): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6857): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6857): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6857): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6857): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6857): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6857): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6857): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6857): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6857): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 6857): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6857): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6857): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6857): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 4645): FATAL EXCEPTION: main
E/AndroidRuntime( 4645): Process: com.google.android.gms.persistent, PID: 4645
E/AndroidRuntime( 4645): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4645): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime( 4645): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime( 4645): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime( 4645): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4645): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4645): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime( 4645): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4645): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4645): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 4645): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 4645): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4645): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4645): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConn,ection.java:904)
E/AndroidRuntime( 4645): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4645): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4645): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4645): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 4645): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 4645): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 4645): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime( 4645): 	... 9 more
E/PhenotypeInitializer( 6857): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 6857): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 6857): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 6857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/PhenotypeInitializer( 6857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/PhenotypeInitializer( 6857): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 6857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 6857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 6857): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/PhenotypeInitializer( 6857): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/PhenotypeInitializer( 6857): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/PhenotypeInitializer( 6857): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/PhenotypeInitializer( 6857): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6857): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6857): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 6857): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 6857): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 6857): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 6857): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 6857): 	at android.os.Looper.loop(Looper.java:145)
E/PhenotypeInitializer( 6857): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 3508): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3508): 	at com.android.server.SystemServer.run(SystemServer.java:427)
W/System.err( 3508): 	at com.android.server.SystemServer.main(SystemServer.java:312)
W/System.err( 3508): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3508): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/System.err( 3508): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 3508): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 3508): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
,W/System.err( 3508): 	at libcore.io.Posix.open(Native Method)
W/System.err( 3508): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 3508): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 3508): 	... 12 more
,W/System.err( 3508): java.io.FileNotFoundException: /data/system/harmony_third_party_apps.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 3508): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err( 3508): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 3508): 	at com.android.server.HarmonyEASService.saveHash(HarmonyEASService.java:303)
W/System.err( 3508): 	at com.android.server.HarmonyEASService.access$000(HarmonyEASService.java:60)
W/System.err( 3508): 	at com.android.server.HarmonyEASService$PackageHandler.handleMessage(HarmonyEASService.java:100)
W/System.err( 3508): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3508): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3508): 	at com.android.server.SystemServer.run(SystemServer.java:427)
W/System.err( 3508): 	at com.android.server.SystemServer.main(SystemServer.java:312)
W/System.err( 3508): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3508): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3508): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 3508): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 3508): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 3508): 	at libcore.io.Posix.open(Native Method)
W/System.err( 3508): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 3508): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 3508): 	... 12 more
,W/System.err( 3508): java.io.FileNotFoundException: /data/system/harmony_third_party_apps.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 3508): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 3508): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 3508): 	at com.android.server.HarmonyEASService.saveHash(HarmonyEASService.java:303)
W/System.err( 3508): 	at com.android.server.HarmonyEASService.access$000(HarmonyEASService.java:60)
W/System.err( 3508): 	at com.android.server.HarmonyEASService$PackageHandler.handleMessage(HarmonyEASService.java:100)
W/System.err( 3508): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3508): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3508): 	at com.android.server.SystemServer.run(SystemServer.java:427)
W/System.err( 3508): 	at com.android.server.SystemServer.main(SystemServer.java:312)
W/System.err( 3508): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3508): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3508): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 3508): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 3508): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 3508): 	at libcore.io.Posix.open(Native Method)
W/System.err( 3508): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 3508): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 3508): 	... 12 more
,D/NearbySource(12652): Nearby Source Create!
D/NearbyContext(12652): Nearby Context Create!
,D/StatusBar( 3689): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
V/ApplicationPolicy( 3508): isApplicationStateBlocked userId 0 pkgname com.google.android.gms.persistent
,D/ChimeraCfgMgr( 6857): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/PersonaManager( 3689): isKioskContainerExistOnDevice
D/PersonaManager( 3689): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3689): Icon Only
,I/StatusBar( 3689): Icon Only
,D/ChimeraModuleLdr( 6857): Module APK com.google.android.play.games already loaded
,D/PanelView( 3689): There is/are notification(s) 
,D/PanelView( 3689): There is/are notification(s) 
,E/DropBoxManagerService( 3508): Can't write: system_app_crash
E/DropBoxManagerService( 3508): java.io.FileNotFoundException: /data/system/dropbox/drop195.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3508): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3508): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3508): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3508): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3508): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3508): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3508): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3508): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3508): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3508): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3508): 	... 5 more
,D/PersonaManager( 3689): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3689): Icon Only
,I/StatusBar( 3689): Icon Only
,D/PanelView( 3689): There is/are notification(s) 
,E/SQLiteLog( 6857): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6857): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,D/LocationManagerService( 3508): getProviders()=[]
,D/LocationManagerService( 3508): getProviders()=[passive]
D/LocationManagerService( 3508): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,I/Process ( 4645): Sending signal. PID: 4645 SIG: 9
,D/LWLocationManager(12732): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(12732): getLastUiLocationId() : mLastUiLocationId = -100
,E/SQLiteLog(12732): (28) failed to open "/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db" with flag (131138) and mode_t (0) due to error (30)
W/ContextImpl(12652): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(12652): Samsung link source created
,E/GMPM-SVC( 6857): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
,E/SQLiteDatabase(12732): Failed to open database '/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db'.
E/SQLiteDatabase(12732): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12732): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12732): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12732): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12732): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12732): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12732): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12732): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12732): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12732): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/SQLiteDatabase(12732): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/SQLiteDatabase(12732): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/SQLiteDatabase(12732): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/SQLiteDatabase(12732): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/SQLiteDatabase(12732): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/SQLiteDatabase(12732): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/SQLiteDatabase(12732): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/SQLiteDatabase(12732): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12732): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12732): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12732): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12732): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12732): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12732): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/AndroidRuntime(12732): Shutting down VM
E/AndroidRuntime(12732): FATAL EXCEPTION: main
E/AndroidRuntime(12732): Process: com.sec.android.widgetapp.locationwidget, PID: 12732
E/AndroidRuntime(12732): java.lang.RuntimeException: Unable to start receiver com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12732): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime(12732): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime(12732): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime(12732): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12732): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12732): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12732): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12732): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12732): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12732): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12732): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12732): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12732): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12732): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12732): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12732): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12732): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12732): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12732): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12732): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/AndroidRuntime(12732): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/AndroidRuntime(12732): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/AndroidRuntime(12732): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/AndroidRuntime(12732): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/AndroidRuntime(12732): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime(12732): 	... 9 more
,D/UsbHostManager( 3508): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3508): displayNotification : [02h,02h,01h]
,D/UsbHostManager( 3508): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3508): displayNotification : [0ah,00h,00h]
,D/UsbHostManager( 3508): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3508): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3508): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3508): displayNotification : [0ah,00h,01h]
,D/UsbHostManager( 3508): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3508): displayNotification : [09h,00h,00h]
,D/UsbHostManager( 3508): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3508): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3508): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,V/ApplicationPolicy( 3508): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.locationwidget
,E/SharedPreferencesImpl( 6857): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,E/SQLiteLog( 6857): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6857): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/AndroidRuntime( 6857): FATAL EXCEPTION: PlayGamesAsyncThread2
E/AndroidRuntime( 6857): Process: com.google.android.gms, PID: 6857
E/AndroidRuntime( 6857): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6857): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6857): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime( 6857): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6857): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6857): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/AndroidRuntime( 6857): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/AndroidRuntime( 6857): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 6857): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 6857): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 6857): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/AndroidRuntime( 6857): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/AndroidRuntime( 6857): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 6857): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 6857): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 6857): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 6857): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 6857): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 6857): 	at java.lang.Thread.run(Thread.java:818)
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/DropBoxManagerService( 3508): Can't write: system_app_crash
E/DropBoxManagerService( 3508): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3508): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3508): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3508): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3508): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3508): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3508): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3508): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3508): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3508): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3508): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3508): 	... 5 more
,E/SQLiteLog(12652): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteLog( 6857): (10) POSIX Error : 9 SQLite Error : 3850
,E/SQLiteLog( 6857): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/Process ( 6857): Sending signal. PID: 6857 SIG: 9
,E/SQLiteDatabase(12652): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(12652): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12652): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12652): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12652): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12652): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12652): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12652): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12652): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12652): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12652): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12652): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12652): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12652): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(12652): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(12652): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(12652): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(12652): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(12652): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12652): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12652): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12652): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12652): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12652): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12652): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12652): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12652): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12652): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12652): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12652): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(12652): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12652): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12652): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12652): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12652): 	at android.database.sqlite.SQLiteConne,ctionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12652): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12652): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12652): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12652): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12652): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12652): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12652): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12652): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(12652): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(12652): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(12652): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(12652): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(12652): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12652): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12652): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12652): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12652): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12652): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12652): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12652): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12652): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12652): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12652): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12652): Opened local.db in read-only mode
D/WifiDisplayAdapter( 3508): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Zygote  (12769): MountEmulatedStorage()
E/Zygote  (12769): v2
I/libpersona(12769): KNOX_SDCARD checking this for 1000
I/libpersona(12769): KNOX_SDCARD not a persona
,I/SELinux (12769): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3508): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12769 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (12769): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12769): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PanelView( 3689): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/UsbHostManager( 3508): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3508): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,V/ApplicationPolicy( 3508): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/ActivityThread(11789): Failed to find provider info for com.facebook.appmanager.installrecord
,W/ActivityManager( 3508): Process com.google.android.gms has crashed too many times: killing!
,I/ActivityManager( 3508): Killing 6857:com.google.android.gms/u0a14 (adj 0): crash
,I/EventHub( 3508): Removing device '/dev/input/event10' due to inotify event
,D/LocationManagerService( 3508): Location listener died
D/GpsStatusListenerHelper( 3508): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@8765092
I/LocationManagerService( 3508): remove 5d7e8f by com.google.android.gms
D/LocationManagerService( 3508): provider request: passive ProviderRequest[ON interval=0]
,E/DropBoxManagerService( 3508): Can't write: system_app_crash
E/DropBoxManagerService( 3508): java.io.FileNotFoundException: /data/system/dropbox/drop197.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3508): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3508): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3508): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3508): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3508): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3508): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3508): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3508): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3508): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3508): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3508): 	... 5 more
,D/LocationManagerService( 3508): Location listener died
I/LocationManagerService( 3508): remove e3e0045 by com.google.android.gms
D/LocationManagerService( 3508): provider request: passive ProviderRequest[ON interval=0]
,D/WifiService( 3508): Client connection lost with reason: 4
,V/BackupManagerService( 3508): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService( 3508): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
,W/ActivityManager( 3508): Exception when unbinding service com.google.android.gms/.clearcut.service.ClearcutLoggerService
W/ActivityManager( 3508): android.os.DeadObjectException
W/ActivityManager( 3508): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager( 3508): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager( 3508): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:1007)
W/ActivityManager( 3508): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1852)
W/ActivityManager( 3508): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2236)
W/ActivityManager( 3508): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:17705)
W/ActivityManager( 3508): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:6129)
W/ActivityManager( 3508): 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:7561)
W/ActivityManager( 3508): 	at com.android.server.am.ActivityManagerService.handleAppCrashLocked(ActivityManagerService.java:14542)
W/ActivityManager( 3508): 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:14421)
W/ActivityManager( 3508): 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:15187)
W/ActivityManager( 3508): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:14695)
W/ActivityManager( 3508): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:14677)
W/ActivityManager( 3508): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1457)
W/ActivityManager( 3508): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3123)
W/ActivityManager( 3508): 	at android.os.Binder.execTransact(Binder.java:446)
,I/Process (12732): Sending signal. PID: 12732 SIG: 9
,I/EventHub( 3508): Removing device '/dev/input/event7' due to inotify event
,I/ActivityManager( 3508): Process com.google.android.gms.persistent (pid 4645)(adj 0) has died(353,1164)
,D/TimaKeyStoreProvider(12769): TimaSignature is unavailable
,D/ActivityThread(12769): Added TimaKeyStore provider
D/ConnectivityService( 3508): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@37a4e3de)
,D/ConnectivityService( 3508): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService( 3508): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/ActivityManager( 3508): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
W/ActivityManager( 3508): Scheduling restart of crashed service com.google.android.gms/.fitness.disconnect.FitCleanupService in 10999ms
W/ActivityManager( 3508): Scheduling restart of crashed service com.google.android.gms/.deviceconnection.service.DeviceConnectionServiceBroker in 20999ms
W/ActivityManager( 3508): Scheduling restart of crashed service com.google.android.gms/.wearable.service.WearableControlService in 30999ms
W/ActivityManager( 3508): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.FusedLocationService in 40998ms
,W/ActivityManager( 3508): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geocode.GeocodeService in 50998ms
W/ActivityManager( 3508): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService in 60997ms
,W/ActivityManager( 3508): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.network.NetworkLocationService in 70997ms
,W/ActivityManager( 3508): Scheduling restart of crashed service com.google.android.gms/.backup.BackupTransportService in 80996ms
,W/ActivityManager( 3508): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.server.GoogleLocationService in 90994ms
,I/EventHub( 3508): Removing device '/dev/input/event8' due to inotify event
,W/ActivityManager( 3508): Scheduling restart of crashed service com.google.android.gms/.common.stats.GmsCoreStatsService in 100989ms
W/ActivityManager( 3508): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geofencer.service.GeofenceProviderService in 110988ms
,D/WifiDisplayAdapter( 3508): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/EventHub( 3508): Removing device '/dev/input/event9' due to inotify event
,D/ResourcesManager(12769): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
D/MtpClient(12652): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12652): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,D/ContactProvider(12652): getAllContactInfoList Start
,E/SharedPreferencesImpl(12652): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,I/ActivityManager( 3508): Process com.sec.android.widgetapp.locationwidget (pid 12732)(adj 9) has died(358,1165)
,I/EventHub( 3508): Removing device '/dev/input/event11' due to inotify event
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_LOG(12769): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(12769): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(12769): new DMDBOpenHelper instance
,E/SQLiteLog(12769): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12769): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(12769): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12769): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12769): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12769): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12769): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12769): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12769): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12769): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12769): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12769): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase(12769): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(12769): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(12769): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(12769): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(12769): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(12769): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12769): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12769): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12769): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12769): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12769): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12769): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12769): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12769): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(12769): Shutting down VM
E/AndroidRuntime(12769): FATAL EXCEPTION: main
E/AndroidRuntime(12769): Process: com.sec.pcw.device, PID: 12769
E/AndroidRuntime(12769): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12769): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(12769): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
,E/AndroidRuntime(12769): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(12769): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(12769): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(12769): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12769): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12769): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12769): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12769): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12769): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12769): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12769): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12769): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12769): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12769): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12769): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12769): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12769): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12769): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12769): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12769): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime(12769): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(12769): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(12769): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(12769): 	... 11 more
,I/EventHub( 3508): Removing device '/dev/input/event12' due to inotify event
,E/Zygote  (12789): MountEmulatedStorage()
,E/Zygote  (12789): v2
I/libpersona(12789): KNOX_SDCARD checking this for 10052
I/libpersona(12789): KNOX_SDCARD not a persona
,I/SELinux (12789): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12789): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3508): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12789 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/SELinux (12789): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/ApplicationPolicy( 3508): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,I/EventHub( 3508): Removing device '/dev/input/event13' due to inotify event
,E/DropBoxManagerService( 3508): Can't write: system_app_crash
E/DropBoxManagerService( 3508): java.io.FileNotFoundException: /data/system/dropbox/drop198.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3508): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3508): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3508): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3508): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3508): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3508): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3508): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3508): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3508): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3508): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3508): 	... 5 more
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12805): MountEmulatedStorage()
E/Zygote  (12805): v2
I/libpersona(12805): KNOX_SDCARD checking this for 10035
I/libpersona(12805): KNOX_SDCARD not a persona
I/EventHub( 3508): Removing device '/dev/input/event14' due to inotify event
,I/SELinux (12805): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27,
,I/SELinux (12805): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12805): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12805 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/Process (12769): Sending signal. PID: 12769 SIG: 9
,D/TimaKeyStoreProvider(12789): TimaSignature is unavailable
,D/ActivityThread(12789): Added TimaKeyStore provider
,E/lowmemorykiller( 2827): Error writing /proc/12769/oom_score_adj; errno=22
I/ActivityManager( 3508): Killing 11872:com.sec.android.cloudagent/u0a2 (adj 13): bgCount ##31
,I/ActivityManager( 3508): Process com.sec.pcw.device (pid 12769)(adj 9) has died(352,1165)
,D/ResourcesManager(12789): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/TimaKeyStoreProvider(12805): TimaSignature is unavailable
,D/ActivityThread(12805): Added TimaKeyStore provider
,W/ResourcesManager(12789): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12789): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12789): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(12789): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12789): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager(12789): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(12805): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk

```
