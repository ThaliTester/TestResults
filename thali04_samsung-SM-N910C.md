#### Test 50388019f4ce509_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
--------- beginning of main
I/SA      ( 9963): [SSP] onCreated
E/Zygote  ( 9986): MountEmulatedStorage()
E/Zygote  ( 9986): v2
I/SELinux ( 9986): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9986): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/libpersona( 9986): KNOX_SDCARD checking this for 10034
I/libpersona( 9986): KNOX_SDCARD not a persona
E/SELinux ( 9986): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/SA      ( 9963): [TPM] There is no property file
I/ActivityManager( 3524): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=9986 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/SA      ( 9963): [SCU] isHaveSA() - false
I/SA      ( 9963): [TPM] getModelProperty : null
I/SA      ( 9963): [TPM] getCSCProperty : null
I/SA      ( 9963): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 9963): [DM] init START
I/art     ( 2880): Explicit concurrent mark sweep GC freed 8770(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 739us total 10.711ms
D/TimaKeyStoreProvider( 9986): TimaSignature is unavailable
D/ActivityThread( 9986): Added TimaKeyStore provider
I/SA      ( 9963): [DM] This device is not a Vodafone
I/SA      ( 9963): checkReactivationActive for LOLLIPOP
I/SA      ( 9963): checkReactivationActive for reactiveActive
I/SA      ( 9963): setSupportRL : true
I/SA      ( 9963): [SCU] isHaveSA() - false
I/SA      ( 9963): support phone number id : false
I/SA      ( 9963): [DM] init END
I/SA      ( 9963): [SUR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      ( 9963): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10402 extra.user_handle.:0 ]
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 430us total 8.333ms
D/ResourcesManager( 9986): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 243us total 7.578ms
E/Zygote  (10004): MountEmulatedStorage()
E/Zygote  (10004): v2
I/SELinux (10004): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/libpersona(10004): KNOX_SDCARD checking this for 10046
I/libpersona(10004): KNOX_SDCARD not a persona
I/SELinux (10004): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10004): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.samsung.android.app.pinboard:sync for broadcast com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayReceiver: pid=10004 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager( 3524): Killing 8842:com.google.android.talk/u0a125 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(10004): TimaSignature is unavailable
D/ActivityThread(10004): Added TimaKeyStore provider
I/System.out( 9986): Inside WakeupProvider
D/ResourcesManager(10004): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
E/DatabaseUtils( 9986): Writing exception to parcel
E/DatabaseUtils( 9986): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 9986): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 9986): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 9986): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils( 9986): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 9986): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 9986): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 9986): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils( 9986): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils( 9986): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 9986): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 9943): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 9943): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 9943): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 9943): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 9943): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 9943): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 9943): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 9943): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/ResourcesManager(10004): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10004): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(10004): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/System.err( 9943): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 9943): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 9943): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 9943): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 9943): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 9943): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 9943): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 9943): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 9943): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 9943): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 9943): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:131)
W/System.err( 9943): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:197)
W/System.err( 9943): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err( 9943): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 9943): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err( 9943): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err( 9943): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err( 9943): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 9943): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 9943): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err( 9943): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 9943): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 9943): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 9943): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/DatabaseUtils( 9986): Writing exception to parcel
E/DatabaseUtils( 9986): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 9986): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 9986): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 9986): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils( 9986): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 9986): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 9986): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 9986): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils( 9986): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils( 9986): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 9986): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 9943): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 9943): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 9943): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 9943): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 9943): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 9943): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 9943): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 9943): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 9943): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 9943): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 9943): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 9943): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 9943): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 9943): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 9943): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 9943): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 9943): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:242)
W/System.err( 9943): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err( 9943): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 9943): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err( 9943): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err( 9943): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err( 9943): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 9943): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 9943): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err( 9943): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 9943): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 9943): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 9943): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 9943): [DLApplication]-Init Called!:false
W/[CarMode]( 9943): [CommonUtil]-=========================================
W/[CarMode]( 9943): [CommonUtil]-CarMode Version:1.10.38.19768
W/[CarMode]( 9943): [CommonUtil]-=========================================
E/[CarMode]( 9943): [DLApplication]-Init Started!:true
I/[CarModeFW]( 9943): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 9943): ### com.sec.android.app.automotive.carmode.framework.DriveLinkServiceInterfaceImp::initialize(132)
I/[CarModeFW]( 9943): ### com.sec.android.automotive.drivelink.DLApplication::init(211)
I/[CarModeFW]( 9943): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(135)
I/[CarModeFW]( 9943): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 9943): ### android.app.ActivityThread::handleBindApplication(5115)
I/[CarModeFW]( 9943): ### android.app.ActivityThread::access$1600(178)
I/[CarModeFW]( 9943): ### android.app.ActivityThread$H::handleMessage(1510)
I/[CarModeFW]( 9943): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 9943): ### android.os.Looper::loop(145)
I/[CarModeFW]( 9943): ### android.app.ActivityThread::main(5944)
I/[CarModeFW]( 9943): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 9943): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 9943): ### com.android.internal.os.ZygoteInit::main(1194)
I/VlingoApplication( 9986): VlingoApplication appVersion ='11.7.0.1.39589', coreVersion = '2.5.2.15201', ro.csc.sales_code=XEO
D/BluetoothAdapter( 9986): 53212088: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 9986): 53212088: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 9986): 53212088: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore( 9986): AppName: SamsungTproject, Core: 2.5.2.15201, SDK: 2.0.1657, EDM:15201
I/MessageDataHandler( 9943): initialize
D/[CarModeFW]( 9943): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 9943): CDH-initiazlieCaches : after sync
E/Minikin (10004): addFont failed to create font /system/fonts/SamsungSans-light.ttf
D/[CarModeFW]( 9943): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 9943): CDH-ContactDataHandler initiazlieCaches time : 13
D/[CarModeFW]( 9943): CDH-initiazlieCaches : end sync
D/BluetoothAdapter( 9943): 654144718: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 9943): 654144718: getState() :  mService = null. Returning STATE_OFF
D/[CarModeFW]( 9943): DrivingManager-initialize...
I/SensorService( 3524): Skipped sensor HRMLED IR because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3524): Skipped sensor HRMLED RED because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3524): Skipped sensor MAX86902 because it requires permission 
I/SensorService( 3524): Skipped sensor HRM Sensor because it requires permission 
I/SensorService( 3524): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/RelayReceiver_PinBoard(10004): onReceive... android.intent.action.PACKAGE_ADDED
I/RelayService_PinBoard(10004): RelayService Started!! : android.intent.action.PACKAGE_ADDED
D/VlingoApplication( 9986): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 9986): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
D/DialogFlow( 9986): initQueue()
I/MediaPlayer( 9943): Need to enable context aware info
V/MediaPlayer-JNI( 9943): native_setup
V/MediaPlayer( 9943): constructor
V/MediaPlayer( 9943): setListener
D/[CarModeFW]( 9943): MY_TAG-[YANG] MusicButtonReceiver construct MusicButtonReceiver() 
I/[CarModeFW]( 9943): DriveLinkServiceInterfaceImp-drivelink framework initialize end
D/[CarMode]( 9943): [DLServiceManager]-getOnDLLocationSuggestionListener..........
D/[CarModeFW]( 9943): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => start time : 1447834401545
D/[CarMode]( 9943): [DLServiceManager]-updateLocationList
D/[CarMode]( 9943): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 9943): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1447834401546
D/[CarModeFW]( 9943): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => start time : 1447834401547
D/[CarModeFW]( 9943): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => start time : 1447834401546
D/[CarModeFW]( 9943): insertNavigationAvailable-sql: select distinct nav_package from tb_location_navigation_available
D/[CarModeFW]( 9943): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => start time : 1447834401547
D/[CarModeFW]( 9943): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1447834401547
D/[CarModeFW]( 9943): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => start time : 1447834401546
F/DLApplication( 9943): DLApplication mListNavitationAvailable: [com.skt.skaf.l001mtm091, com.google.android.apps.maps, kt.navi, com.mnsoft.lgunavi, com.autonavi.xmgd.navigator.samsung, com.here.app.maps]
I/[CarMode]( 9943): [LogNotNull]-Package name is: com.here.app.maps
D/[CarModeFW]( 9943): ContactDataHandler-getFavoriteContactList : cur len = 0
D/[CarModeFW]( 9943): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 4
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 7972): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 3972): query,matched:2, calling pid = 9943
D/[CarModeFW]( 9943): ContactDataHandler-getFavoriteContactList : cur len = 0
D/[CarModeFW]( 9943): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => execute time : 7
D/TP/SmsProvider( 3972): match 2:Elapsed time : 1.659 ms
D/[CarModeFW]( 9943): ContactDataHandler-getFavoriteContactList : cur len = 0
D/[CarModeFW]( 9943): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 12
E/Zygote  (10039): MountEmulatedStorage()
I/libpersona(10039): KNOX_SDCARD checking this for 10047
E/Zygote  (10039): v2
I/libpersona(10039): KNOX_SDCARD not a persona
I/SELinux (10039): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10039): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10039): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=10039 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/[CarMode]( 9943): [DLApplication]-Init End!:true
D/[CarModeFW]( 9943): CalllogDataHandler-getCalllogList : cur len = 0
D/TP/SmsProvider( 3972): query,matched:2, calling pid = 9943
D/MessageDataHandler( 9943):  getInboxList smsCursor : 21
D/[CarMode]( 9943): [TAG]-phone sound mode is: 0
V/[CarMode]( 9943): [DLApplication]-savePreviousGpsState
D/[CarModeFW]( 9943): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => execute time : 25
D/TP/SmsProvider( 3972): match 2:Elapsed time : 2.288 ms
D/TP/MmsProvider( 3972): Query uri=content://mms/inbox, match=2, calling pid = 9943
V/[CarMode]( 9943): [DLApplication]-savePreviousGpsState: Previous state = 0
D/MessageDataHandler( 9943):  getInboxList mmsCursor : 5
D/TP/MmsProvider( 3972): Query uri=content://mms, match=0, calling pid = 9943
D/MessageDataHandler( 9943):  getInboxList mms,sms cursor join : 3
D/TP/MmsSmsProvider( 3972): query,matched:0, calling pid = 9943
V/TP/MmsSmsProvider( 3972): getSimpleConversations entered.
D/TP/MmsSmsProvider( 3972): match 0:Elapsed time : 0.805 ms
I/MessageDataHandler( 9943): getUnreadMessageCount :0
D/[CarMode]( 9943): [DLApplication]-GooglePlayServices SUCCESS.
E/[CarMode]( 9943): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
D/[CarModeFW]( 9943): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => execute time : 33
D/TP/MmsSmsProvider( 3972): query,matched:13, calling pid = 9943
I/[CarMode]( 9943): [[DLUncaughtExceptionHandler]]-setDLUncaughtExceptionHandler
E/[CarMode]( 9943): [[DLUncaughtExceptionHandler]]-DLUncaughtExceptionHandler is created!
D/TP/MmsSmsProvider( 3972): match 13:Elapsed time : 2.100 ms
D/TimaKeyStoreProvider(10039): TimaSignature is unavailable
D/ActivityThread(10039): Added TimaKeyStore provider
I/UpdateManagerReceiver( 9943): Intent : android.intent.action.PACKAGE_ADDEDWed Nov 18 09:13:21 GMT+01:00 2015
D/DialogFlow( 9943): initQueue()
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(10039): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
W/ResourcesManager(10039): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
E/Zygote  (10054): MountEmulatedStorage()
E/Zygote  (10054): v2
I/libpersona(10054): KNOX_SDCARD checking this for 1000
I/libpersona(10054): KNOX_SDCARD not a persona
I/SELinux (10054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10054): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=10054 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3524): Killing 9419:com.sec.knox.knoxsetupwizardclient/1000 (adj 13): bgCount ##31
I/ActivityManager( 3524): Killing 9402:com.sec.knox.bridge/1000 (adj 13): bgCount ##32
I/ActivityManager( 3524): Killing 9386:com.samsung.android.app.FileShareServer/u0a79 (adj 15): bgCount ##33
E/lowmemorykiller( 2828): Error writing /proc/9386/oom_score_adj; errno=22
D/MessageDataHandler( 9943):  getInboxList address cursor : 28
D/TP/MmsSmsProvider( 3972): query,matched:0, calling pid = 9943
V/TP/MmsSmsProvider( 3972): getSimpleConversations entered.
I/CalendarProvider2(10039): CalendarProvider2.onCreate() called
D/TP/MmsSmsProvider( 3972): match 0:Elapsed time : 1.293 ms
D/MessageDataHandler( 9943):  getInboxList thread cursor : 8
D/MessageDataHandler( 9943):  thread, addr result: 3
I/[CarModeFW]( 9943): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxList() : 74
I/[CarModeFW]( 9943): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 9943): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => execute time : 75
D/TimaKeyStoreProvider(10054): TimaSignature is unavailable
D/ActivityThread(10054): Added TimaKeyStore provider
W/GAV2    ( 9720): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 3524): Killing 9434:com.google.android.apps.plus/u0a147 (adj 15): bgCount ##31
I/art     ( 3524): Explicit concurrent mark sweep GC freed 51070(2MB) AllocSpace objects, 2(146KB) LOS objects, 24% free, 48MB/64MB, paused 1.176ms total 95.780ms
D/ResourcesManager(10054): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
W/ContextImpl(10054): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(10054): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
E/FilterInstaller(10054): installFilters
E/FilterInstaller(10054): There is no requred permission
E/Zygote  (10072): MountEmulatedStorage()
E/Zygote  (10072): v2
I/libpersona(10072): KNOX_SDCARD checking this for 10121
I/libpersona(10072): KNOX_SDCARD not a persona
I/SELinux (10072): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10072): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10072): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=10072 uid=10121 gids={50121, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 3524): Killing 8798:com.google.android.gm/u0a122 (adj 15): bgCount ##31
E/lowmemorykiller( 2828): Error writing /proc/8798/oom_score_adj; errno=22
D/TimaKeyStoreProvider(10072): TimaSignature is unavailable
D/ActivityThread(10072): Added TimaKeyStore provider
D/[CarModeFW]( 9943): LocationDataHandler-No schedules found.
D/[CarModeFW]( 9943): MyPlaceProvider-Provider uri: content://com.samsung.android.internal.intelligence.useranalysis/place
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(10072): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
D/PackageIntentReceiver(10072): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver(10072): Not GearManger package! 
E/Zygote  (10088): MountEmulatedStorage()
E/Zygote  (10088): v2
I/libpersona(10088): KNOX_SDCARD checking this for 10003
I/libpersona(10088): KNOX_SDCARD not a persona
I/SELinux (10088): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10088): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10088): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=10088 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  (10103): MountEmulatedStorage()
E/Zygote  (10103): v2
I/libpersona(10103): KNOX_SDCARD checking this for 1000
I/libpersona(10103): KNOX_SDCARD not a persona
I/SELinux (10103): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10103): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/TimaKeyStoreProvider(10088): TimaSignature is unavailable
E/SELinux (10103): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=10103 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ActivityThread(10088): Added TimaKeyStore provider
I/ActivityManager( 3524): Killing 9582:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##31
D/ResourcesManager(10088): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
I/System.out( 9986): INFO:Resource not found:/Common.properties Using default values
D/TimaKeyStoreProvider(10103): TimaSignature is unavailable
D/ActivityThread(10103): Added TimaKeyStore provider
D/UserAnalysis.PlaceProvider(10088): PlaceProvider onCreate()
D/ResourcesManager(10103): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/UserAnalysis.SecureDbManager(10088): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper(10088): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(10088): Create SecureDbHelper
D/IntelligenceServiceApplication(10088): onCreate()
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  (10120): MountEmulatedStorage()
I/libpersona(10120): KNOX_SDCARD checking this for 1000
E/Zygote  (10120): v2
I/libpersona(10120): KNOX_SDCARD not a persona
I/SELinux (10120): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10120): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=10120 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (10120): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/lowmemorykiller( 2828): Error writing /proc/9622/oom_score_adj; errno=22
I/ActivityManager( 3524): Killing 9622:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##31
D/[CarModeFW]( 9943): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 9943): MyPlaceProvider-=============
D/[CarModeFW]( 9943): MyPlaceProvider-=============
D/[CarModeFW]( 9943): MyPlaceProvider-=============
D/[CarModeFW]( 9943): MyPlaceProvider-=============
D/[CarModeFW]( 9943): MyPlaceProvider-=============
D/[CarModeFW]( 9943): MyPlaceProvider-=============
D/[CarModeFW]( 9943): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 9943): MyPlaceProvider-==============
D/[CarModeFW]( 9943): MyPlaceProvider-==============
D/[CarModeFW]( 9943): MyPlaceProvider-==============
D/[CarModeFW]( 9943): MyPlaceProvider-==============
D/[CarModeFW]( 9943): MyPlaceProvider-==============
D/[CarModeFW]( 9943): DestinationAvailableTableHandler-sql: select dest_name from tb_destination_list_available where ((1447834401881 - dest_date ) / 360000 ) <= 24 ORDER BY dest_date DESC LIMIT 100
E/[CarModeFW]( 9943): DestinationAvailableTableHandler-insert FAIL!
E/DestinationList( 9943): loadLocationDestinationList is null
D/[CarModeFW]( 9943): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => execute time : 335
D/TimaKeyStoreProvider(10120): TimaSignature is unavailable
D/ActivityThread(10120): Added TimaKeyStore provider
D/ResourcesManager(10120): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
D/AcmsPackageEventListener(10120): Received: android.intent.action.PACKAGE_ADDED
W/ContextImpl(10120): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  (10137): MountEmulatedStorage()
I/libpersona(10137): KNOX_SDCARD checking this for 10147
E/Zygote  (10137): v2
I/libpersona(10137): KNOX_SDCARD not a persona
I/SELinux (10137): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10137): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10137): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=10137 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3524): Killing 8697:com.sec.android.widgetapp.locationwidget/u0a22 (adj 15): bgCount ##31
E/lowmemorykiller( 2828): Error writing /proc/8697/oom_score_adj; errno=22
D/AcmsService(10120): Enter Oncreate
D/AcmsServiceMonitor(10120): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService(10120): creating AcmsCore
D/AcmsCore(10120): AcmsCore.getAcmsCore() - Enter
D/AcmsCore(10120): AcmsCore
D/AcmsCore(10120): init
D/AcmsCore(10120): Looper handler is not null
D/AcmsCore(10120): Post to AcmsCoreHandler
D/AcmsServiceMonitor(10120): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10120): Incrementing - Counter value: 1
D/AcmsCore(10120): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService(10120): onStartCommand
D/AcmsService(10120): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor(10120): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor(10120): Incrementing - Counter value: 2
D/AcmsService(10120): Incremented Counter Value : onStartCommand
D/AcmsCertificateMngr(10120): AcmsCertificateMngr
D/AcmsRevocationMngr(10120): AcmsRevocationMngr
D/ActivityThread(10120): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/TimaKeyStoreProvider(10137): TimaSignature is unavailable
D/ActivityThread(10137): Added TimaKeyStore provider
D/ResourcesManager(10137): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/AcmsService(10120): Inside handle Intent
W/ResourcesManager(10137): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/AcmsService(10120): App added - package name: com.example.hello
D/AcmsCore(10120): Post to AcmsCoreHandler
D/AcmsServiceMonitor(10120): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10120): Incrementing - Counter value: 3
D/AcmsCore(10120): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService(10120): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor(10120): Decrementing - Counter value: 2
V/GLSActivity( 4139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 4139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  (10169): MountEmulatedStorage()
I/libpersona(10169): KNOX_SDCARD checking this for 10160
E/Zygote  (10169): v2
I/libpersona(10169): KNOX_SDCARD not a persona
I/SELinux (10169): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10169): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10169): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=10169 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
D/TimaKeyStoreProvider(10169): TimaSignature is unavailable
D/ActivityThread(10169): Added TimaKeyStore provider
D/ResourcesManager(10169): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/ResourcesManager(10169): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(10169): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10169): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
V/Common  (10169): getScreenSize 1440 2560
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  (10192): MountEmulatedStorage()
E/Zygote  (10192): v2
I/libpersona(10192): KNOX_SDCARD checking this for 10160
I/libpersona(10192): KNOX_SDCARD not a persona
I/SELinux (10192): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10192): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10192): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=10192 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
I/JAM     (10169): Load The ApaService JNI
I/JAM     (10169): version: ProfessionalAudio_v1.0.b5
I/JAM     (10169): Try v1.0.b3 ...
D/Spen    (10169): SpenSdk version level = 55
D/Spen    (10169): SpenSdk jar version = 3.0.243
D/Spen    (10169): SpenSdk apk version = 3.0.235
D/Spen    (10169): Server UPDATE Check
W/linker  (10169): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
D/SPenError(10169): JNI_OnLoad
D/JNI_Bitmap(10169): Init .. Done
D/SPenSpiDecoder(10169): JNI_OnLoad .. Done
D/SPenError(10169): JNI_OnLoad Success
D/PluginManager(10169): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
D/PluginManager(10169): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
D/Init_SPenSdk_Jni(10169): JNI_OnLoad
D/Init_SPenSdk_Jni(10169): AndroidSDK: 21
D/Init_SPenSdk_Jni(10169): JNI_OnLoad .. Done
D/Model_ObjectBase_Jni(10169): JNI_OnLoad .. Done
D/Model_ObjectStroke_Jni(10169): JNI_OnLoad .. Done
D/Model_ObjectImage_Jni(10169): JNI_OnLoad .. Done
D/Model_ObjectText_Jni(10169): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni(10169): JNI_OnLoad .. Done
D/Model_PageDoc_Jni(10169): JNI_OnLoad .. Done
D/Model_NoteDoc_Jni(10169): check build type eng[0]
D/Model_NoteDoc_Jni(10169): JNI_OnLoad .. Done
D/Model_NoteFile_Jni(10169): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni(10169): JNI_OnLoad .. Done
D/Model   (10169): OnLoad class Done
I/Icing   ( 4474): Indexing 5F814D61A0DCF2E8041D271E5054F7C0773240D3 from com.google.android.googlequicksearchbox
D/spe_log (10169): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
D/SPen_Library(10169): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(10169): Canvas JNI_OnLoad enter!!
D/SPen_Library(10169): Canvas JNI_OnLoad Success
D/SPen_Library(10169): TextView JNI_OnLoad enter!!
D/SPen_Library(10169): TextView JNI_OnLoad Success
D/SPen_Library(10169): Text JNI_OnLoad enter!!
D/SPen_Library(10169): Text JNI_OnLoad Success
D/SPen_Library(10169): FontManager JNI_OnLoad enter!!
D/SPen_Library(10169): FontManager JNI_OnLoad Success
D/SPen_Library(10169): CapturePage JNI_OnLoad enter!!
D/SPen_Library(10169): CapturePage JNI_OnLoad Success
D/SPen_Library(10169): Multi JNI_OnLoad enter!!
D/SPen_Library(10169): Multi JNI_OnLoad Success
D/SPen_Library(10169): Draw Engine JNI_OnLoad Success
D/TimaKeyStoreProvider(10192): TimaSignature is unavailable
D/ActivityThread(10192): Added TimaKeyStore provider
D/SPen_Library(10169): Brush JNI_OnLoad enter!!
D/SPen_Library(10169): Brush JNI_OnLoad Success
D/SPen_Library(10169): ChineseBrush JNI_OnLoad enter!!
D/SPen_Library(10169): ChineseBrush JNI_OnLoad Success
D/SPen_Library(10169): InkPen JNI_OnLoad enter!!
D/SPen_Library(10169): InkPen JNI_OnLoad Success
D/SPen_Library(10169): Marker JNI_OnLoad enter!!
D/SPen_Library(10169): Marker JNI_OnLoad Success
D/SPen_Library(10169): Pencil JNI_OnLoad enter!!
D/SPen_Library(10169): Pencil JNI_OnLoad Success
D/SPen_Library(10169): NativePen JNI_OnLoad enter!!
D/SPen_Library(10169): NativePen JNI_OnLoad Success
D/SPen_Library(10169): MontblancFountainPen JNI_OnLoad enter!!
D/SPen_Library(10169): MontblancFountainPen JNI_OnLoad Success
D/SPen_Library(10169): MontblancCalligraphyPen JNI_OnLoad enter!!
D/ResourcesManager(10192): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/SPen_Library(10169): MontblancCalligraphyPen JNI_OnLoad Success
D/SPen_Library(10169): MagicPen JNI_OnLoad enter!!
D/SPen_Library(10169): MagicPen JNI_OnLoad Success
W/ResourcesManager(10192): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(10192): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10192): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/SPen_Library(10169): ObliquePen JNI_OnLoad enter!!
D/SPen_Library(10169): ObliquePen JNI_OnLoad Success
D/SPen_Library(10169): FountainPen JNI_OnLoad enter!!
D/SPen_Library(10169): FountainPen JNI_OnLoad Success
D/Spen    (10169): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(10169): SPenSdk_init2
D/Init_SPenSdk(10169): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
D/Init_SPenSdk(10169): Total S Pen SDK Directory Size = 0
D/Spen    (10169): initialize complete
W/linker  (10169): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
D/ResourcesManager(10169): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/Icing   ( 4474): Loaded CLD2 Version V2.0 - 20141016
,E/Zygote  (10209): MountEmulatedStorage()
I/libpersona(10209): KNOX_SDCARD checking this for 10183
E/Zygote  (10209): v2
I/libpersona(10209): KNOX_SDCARD not a persona
I/SELinux (10209): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10209): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10209): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=10209 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
I/ActivityManager( 3524): Killing 9539:com.google.android.music:main/u0a135 (adj 15): bgCount ##31
D/SNoteProvider(10192): onCreate enableSnoteSync = true
I/art     ( 2880): Explicit concurrent mark sweep GC freed 8778(373KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 301us total 10.895ms
D/TimaKeyStoreProvider(10209): TimaSignature is unavailable
D/ActivityThread(10209): Added TimaKeyStore provider
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 276us total 7.982ms
D/SNoteProvider(10192): ===query=== 
D/ResourcesManager(10209): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 552us total 8.747ms
V/Common  (10192): getScreenSize 1440 2560
E/SQLiteLog(10209): (284) automatic index on shooting_modes(title_id)
I/Icing   ( 4474): Indexing done 5F814D61A0DCF2E8041D271E5054F7C0773240D3
I/splitIntent( 3524): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/ActivityManager( 3524): Killing 9702:com.samsung.android.app.vrsetupwizardstub/u0a63 (adj 15): bgCount ##31
E/lowmemorykiller( 2828): Error writing /proc/9702/oom_score_adj; errno=22
D/SNoteProvider(10192): ===query=== 
D/BootupListener( 3972): ACTION_DRIVELINK
D/SettingsProvider( 3524): name = drivelink_navigation
D/SettingsProvider( 3524): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3524): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3524): selectionArgs: false
D/SettingsProvider( 3524): selectionArgs: 1001
D/SecContentProvider( 3524): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3524): ret = -1
D/BootupListener( 3972): NAVI : com.here.app.maps
D/SettingsProvider( 3524): name = internet_call_settings_visibility
D/SettingsProvider( 3524): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3524): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3524): selectionArgs: false
D/SettingsProvider( 3524): selectionArgs: 1001
D/SecContentProvider( 3524): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3524): ret = -1
D/BootupListener( 3972): intent.getAction() = com.sec.android.automotive.drivelink.NAVIGATION_PACKAGE_NAME
D/Widget  (10169): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
D/Widget  (10169): onReceive android.appwidget.action.APPWIDGET_UPDATE
D/Widget  (10169): widgetUpdate 5
D/RCPManagerService( 3524): exchangeData() failure , invalid userId
I/PowerManagerService( 3524): [PWL] On : 0 (50430 ms ago)
I/PowerManagerService( 3524): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
I/PowerManagerService( 3524): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI.Notification' ACQUIRE_CAUSES_WAKEUP (uid=10060, pid=3690, ws=null) (elapsedTime=17029)
D/AndroidRuntime(10228): 
D/AndroidRuntime(10228): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10228): CheckJNI is OFF
D/AndroidRuntime(10228): readGMSProperty: start
D/AndroidRuntime(10228): readGMSProperty: already setted!!
D/AndroidRuntime(10228): readGMSProperty: end
D/AndroidRuntime(10228): addProductProperty: start
E/AffinityControl(10228): AffinityControl: registerfunction enter
D/AndroidRuntime(10228): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3524): inState():  stateMachine is null !!
I/PersonaManagerService( 3524): PersonaId don't exist
I/ActivityManager( 3524): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager( 3524): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/CustomFrequencyManagerService( 3524): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3524  pkgName : ACTIVITY_RESUME_BOOSTER@2
W/ActivityManager( 3524): mDVFSHelper.acquire()
D/FocusedStackFrame( 3524): Set to : 0
D/AndroidRuntime(10228): Shutting down VM
E/libEGL  ( 3996): call to OpenGL ES API with no current context (logged once per thread)
D/Launcher.HomeView( 3996): onPause
D/Launcher( 3996): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
I/SurfaceFlinger( 2850): id=10 createSurf (1x1),1 flag=404, iello
E/Zygote  (10242): MountEmulatedStorage()
E/Zygote  (10242): v2
I/libpersona(10242): KNOX_SDCARD checking this for 10173
I/libpersona(10242): KNOX_SDCARD not a persona
I/SELinux (10242): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10242): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=10242 uid=10173 gids={50173, 9997, 1028, 1015} abi=armeabi-v7a
E/SELinux (10242): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider(10242): TimaSignature is unavailable
D/ActivityThread(10242): Added TimaKeyStore provider
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  (10257): MountEmulatedStorage()
I/libpersona(10257): KNOX_SDCARD checking this for 10402
E/Zygote  (10257): v2
I/libpersona(10257): KNOX_SDCARD not a persona
I/SELinux (10257): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10257): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10257): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=10257 uid=10402 gids={50402, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/StatusBarManagerService( 3524): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/MicrophoneInputStream( 4051): mic_close gfk@123fb142
D/TimaKeyStoreProvider(10257): TimaSignature is unavailable
D/ActivityThread(10257): Added TimaKeyStore provider
V/WindowOrientationListener( 3524): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3524): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
V/WindowManager( 3524): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=0 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3524): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3524): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
D/ResourcesManager(10242): creating new AssetManager and set to /system/app/SamsungWidget_ActiveApplication/SamsungWidget_ActiveApplication.apk
V/ActivityThread( 3996): updateVisibility : ActivityRecord{185d348f token=android.os.BinderProxy@37297002 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
V/TaskCloserActivity(10242): TaskCloserActivity enter()
V/AudioPolicyManager( 2859): stopInput() input 15
V/TaskCloserActivity(10242): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
D/Launcher.HomeView( 3996): onStop
V/ActivityThread( 3996): updateVisibility : ActivityRecord{185d348f token=android.os.BinderProxy@37297002 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
V/AudioPolicyManager( 2859): releaseInput() 15
D/Launcher( 3996): onTrimMemory. Level: 20
V/AudioPolicyManager( 2859): closeInput(15)
I/HotwordRecognitionRnr( 4051): Stopping hotword detection.
I/HotwordRecognitionRnr( 4051): Hotword detection finished
D/AudioHardwareTinyALSA( 2859): Entering AudioStreamInALSA standby mode
I/AudioHardwareTinyALSA( 2859): Close mHandle:b01a9600
D/StatusBarManagerService( 3524): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/AudioHardwareTinyALSA( 2859): closeInputStream +
D/TinyUCM ( 2859): Disable Input dev(0x80000004)
I/ActivityManager( 3524): Killing 9732:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
D/TinyUCM ( 2859): set channel: None
D/AudioHardwareTinyALSA( 2859): Entering AudioStreamInALSA standby mode
V/AudioPolicyManager( 2859): releaseInput() exit
D/ResourcesManager(10257): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/WebViewFactory(10257): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(10257): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(10257): Loading: webviewchromium
I/LibraryLoader(10257): Time to load native libraries: 3 ms (timestamps 763-766)
I/LibraryLoader(10257): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(10257): Binding Chromium to main looper Looper (main, tid 1) {23785221}
I/LibraryLoader(10257): Expected native library version number "",actual native library version number ""
I/chromium(10257): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(10257): Initializing chromium process, renderers=0
W/art     (10257): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(10257): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium(10257): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(10257): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(10257): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/BluetoothAdapter(10257): 700921414: getState() :  mService = null. Returning STATE_OFF
,I/CalendarProvider2(10039): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,W/chromium(10257): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(10257): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,E/Zygote  (10307): MountEmulatedStorage()
,I/libpersona(10307): KNOX_SDCARD checking this for 10022
E/Zygote  (10307): v2
I/libpersona(10307): KNOX_SDCARD not a persona
,I/SELinux (10307): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10307): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10307): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=10307 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 9172:com.google.android.partnersetup/u0a17 (adj 13): bgCount ##31
,W/art     (10257): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(10257): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(10257): CordovaWebView is running on device made by: samsung
,W/art     (10257): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (10257): Attempt to remove local handle scope entry from IRT, ignoring
,D/TimaKeyStoreProvider(10307): TimaSignature is unavailable
,D/ActivityThread(10307): Added TimaKeyStore provider
,D/ResourcesManager(10307): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(10307): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10307): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(10307): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/Activity(10257): performCreate Call secproduct feature valuefalse
D/Activity(10257): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(10257): Render dirty regions requested: true
,D/ActivityManager( 3524): post active user change for 0
D/KnoxTimeoutHandler( 3524): postActiveUserChange for user 0
,D/KnoxTimeoutHandler( 3524): handleActiveUserChange for user 0
,I/LocationWidgetApplication(10307): onCreate() : start
,D/LocationWidgetApplication(10307): countryCode = POLAND
,I/SurfaceFlinger( 2850): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(10257): Initialized EGL, version 1.4
I/OpenGLRenderer(10257): HWUI protection enabled for context ,  &this =0xb3c31a10 ,&mEglDisplay = 1 , &mEglConfig = -1278906096 
,D/LocationWidgetUtils(10307): getUpcommingInstances() start: 1447834402897, end: 1448405999999
D/LocationWidgetUtils(10307): getUpcommingInstances() DB begin time >= start:1447834402897, DB begin time <= end:1448405999999
,D/OpenGLRenderer(10257): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(10257): Enabling debug mode 0
D/mali_winsys(10257): new_window_surface returns 0x3000,  [1440x2560]-format:1
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10334): MountEmulatedStorage()
E/Zygote  (10334): v2
I/libpersona(10334): KNOX_SDCARD checking this for 10163
I/libpersona(10334): KNOX_SDCARD not a persona
,I/SELinux (10334): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10334): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10334): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=10334 uid=10163 gids={50163, 9997} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 9357:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,D/InputMethodManagerService( 3524): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 3524): Displayed com.example.hello/.MainActivity: +338ms
,D/TimaKeyStoreProvider(10334): TimaSignature is unavailable
,D/ActivityThread(10334): Added TimaKeyStore provider
,I/Timeline(10257): Timeline: Activity_idle id: android.os.BinderProxy@20a1ee9c time:50997
,D/ResourcesManager(10334): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,W/ResourcesManager(10334): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10334): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10358): MountEmulatedStorage()
I/libpersona(10358): KNOX_SDCARD checking this for 10164
E/Zygote  (10358): v2
I/libpersona(10358): KNOX_SDCARD not a persona
,I/SELinux (10358): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=10358 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux (10358): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/chromium(10257): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/ActivityManager( 3524): Killing 9755:com.sec.android.service.health/u0a19 (adj 13): bgCount ##31
E/SELinux (10358): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/AndroidProtocolHandler(10257): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/TimaKeyStoreProvider(10358): TimaSignature is unavailable
D/ActivityThread(10358): Added TimaKeyStore provider
D/ResourcesManager(10358): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(10358): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10358): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10358): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10358): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/JsMessageQueue(10257): Set native->JS mode to OnlineEventsBridgeMode
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/chromium(10257): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(10257): 
,D/LocationManagerService( 3524): getProviders()=[]
D/LocationManagerService( 3524): getProviders()=[passive]
D/LocationManagerService( 3524): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/LWLocationManager(10307): mPrivacy is null
,W/ContextImpl(10307): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,I/ActivityManager( 3524): Killing 8576:com.android.mms/u0a52 (adj 13): bgCount ##31
,D/ContextFramework:PrivacyManager(10307): Service for PrivacyManager is connected
,D/jxcore_app_log(10257): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357917696
,D/JX-Cordova(10257): jxcore cordova android initializing
,D/LWLocationManager(10307): Privacy service : STATUS_PLACE
D/LWLocationManager(10307): updateLocationStatus()
,I/LocationWidgetFuctionData(10307): readDB
,I/LocationWidgetFuctionData(10307): selectedAppSize: 3
I/LocationWidgetFuctionData(10307): configPlaceList aroundMeItems
,I/LocationWidgetFuctionData(10307): selectedAppSize: 3
,I/LocationWidgetFuctionData(10307): selectedAppSize: 3
,I/LocationWidgetFuctionData(10307): selectedAppSize: 3
,I/LocationWidgetFuctionData(10307): selectedAppSize: 3
,W/jxcore-log(10257): Initializing JXcore engine
W/jxcore-log(10257): JXcore engine is ready
,W/jxcore-log(10257): Starting JXcore engine
,D/CountryDetector( 3524): No listener is left
,I/SurfaceFlinger( 2850): id=8 Removed Mauncher (4/9)
,I/SurfaceFlinger( 2850): id=8 Removed Mauncher (-2/9)
,E/LWLocationManager(10307): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager(10307): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager(10307): setShouldUpdateLocationId
D/LWLocationManager(10307): setShouldUpdateLocationId return false
D/LWLocationManager(10307): setShouldUpdateLocationId
D/LWLocationManager(10307): setShouldUpdateLocationId return false
D/LWLocationManager(10307): setShouldUpdateLocationId
D/LWLocationManager(10307): setShouldUpdateLocationId return false
D/LWLocationManager(10307): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,D/SecurityLogAgent:SEDenialService( 3524): Got Modify Event and sending Denial Intent foraudit.log
E/auditd  ( 4532): In denial and Property audit_ondenial is set to 1 
W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3524): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,I/SurfaceFlinger( 2850): id=10 Removed iello (7/8)
,I/SurfaceFlinger( 2850): id=10 Removed iello (-2/8)
,W/jxcore-log(10257): Platform android
W/jxcore-log(10257): 
W/jxcore-log(10257): Process ARCH arm
W/jxcore-log(10257): 
,I/jxcore-log(10257): JXcore Cordova bridge is ready!
I/jxcore-log(10257): 
W/jxcore-log(10257): JXcore engine is started
,E/jxcore-log(10257): >> samsung-SM-N910C
E/jxcore-log(10257): 
,I/jxcore-log(10257): Total memory 2970812416
I/jxcore-log(10257): 
I/jxcore-log(10257): Free memory 74182656
I/jxcore-log(10257): 
I/jxcore-log(10257): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10257): 
I/jxcore-log(10257): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10257): 
,I/jxcore-log(10257): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(10257): 
,I/jxcore-log(10257): Size 1440 2560
I/jxcore-log(10257): 
,I/jxcore-log(10257): Screen Brightness 134
I/jxcore-log(10257): 
E/jxcore-log(10257): Dummy Error Log.
E/jxcore-log(10257): 
,D/AcmsKeyStoreHelper(10120):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper(10120): Key Store exist
I/AcmsKeyStoreHelper(10120): Hence loading the keystore file
,D/AcmsKeyStoreHelper(10120):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr(10120): getKeyStoreForApplication success 
D/AcmsCore(10120): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor(10120): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10120): Decrementing - Counter value: 1
D/AcmsCore(10120): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore(10120): This is NOT a valid MirrorLink app
D/AcmsCore(10120): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor(10120): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10120): Decrementing - Counter value: 0
D/AcmsServiceMonitor(10120): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor(10120): getSvcCounter - Counter value: 0
D/AcmsService(10120): Enter onDestroy
I/AcmsService(10120): cleanUp(): inside service clean up
D/AcmsCore(10120): AcmsCore: inside DeInit
D/AcmsCore(10120): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr(10120): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr(10120): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper(10120): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface(10120): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor(10120): getSvcCounter - Counter value: 0
D/AcmsService(10120): killing acms process
I/Process (10120): Sending signal. PID: 10120 SIG: 9
,I/ActivityManager( 3524): Process ACMS.Process (pid 10120)(adj 0) has died(77,1354)
,D/CustomFrequencyManagerService( 3524): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3524  tag : ACTIVITY_RESUME_BOOSTER@2
,W/ActivityManager( 3524): mDVFSHelper.release()
I/Timeline( 3524): Timeline: Activity_windows_visible id: ActivityRecord{325f89a3 u0 com.example.hello/.MainActivity t24} time:51455
D/CustomFrequencyManagerService( 3524): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3524  pkgName : ACTIVITY_RESUME_BOOSTER@6
,D/CustomFrequencyManagerService( 3524): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3524  tag : ACTIVITY_RESUME_BOOSTER@6
I/jxcore-log(10257): getBuffer is called!!!!
I/jxcore-log(10257): 
W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 330, PST = 330, CUR = -531
,D/PowerManagerService( 3524): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10060 pid=3690 (0x0)
,I/PowerManagerService( 3524): !@[ps] Screen__Off - 0 : release wake lock: (0x1) (2)
I/PowerManagerService( 3524): Going to sleep due to screen timeout (uid 1000)...
,D/InputManager-JNI( 3524): setDeviceInteractive: 0
,D/InputManager-JNI( 3524): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/DisplayPowerController( 3524): getFinalBrightness : 15 -> 15
D/InputManager-JNI( 3524): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/DisplayPowerController( 3524): animation target = 15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/InputManager-JNI( 3524): sysfs_write +: /sys/class/input/event2/device/enabled: 0
D/PowerManagerService( 3524): [s] DisplayPowerCallbacks : onStateChanged()
,D/InputManager-JNI( 3524): sysfs_write -: /sys/class/input/event3/device/enabled: 0,
,D/PowerManagerService( 3524): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 3524): SecHardwareInterface.setBatteryADC : false
D/InputManager-JNI( 3524): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI( 3524): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/PowerManagerService( 3524): handleSandman : startDream()
,E/PowerManagerService( 3524): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 3524): Sleeping (uid 1000)...
D/PowerManagerService( 3524): [s] UserActivityState : 4 -> 0
D/PowerManagerService( 3524): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService( 3524): [input device light] handleInputDeviceLightOff
,D/SContextService( 3524): 	.unregisterCallback : 1, client=
D/SContextService( 3524): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@2ed14fcf, Service = Auto Rotation, used = 1
,I/SurfaceFlinger( 2850): id=12 createSurf (1440x2560),2 flag=404, DolorFade
,W/CAE     ( 3524): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     ( 3524): stop(ContextProvider.java:149)
,V/CAE     ( 3524): clear(AutoRotationRunner.java:182)
,V/CAE     ( 3524): disable(AutoRotationRunner.java:171)
,I/CAE     ( 3524): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager( 3524): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs( 2870): sendContextData: -78, 7, 0, 0
,D/CAE     ( 3524): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     ( 3524): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/PowerManagerService( 3524): Excessive delay in ColorFade : createSurface: 22ms
,D/PowerManagerService( 3524): Excessive delay in ColorFade : createEglContext: 23ms
,D/mali_winsys( 3524): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/PermissionCache( 2850): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (256 us)
,D/CAE     ( 3524): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     ( 3524): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     ( 3524): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     ( 3524): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService( 3524): removeSContextService() : service = Auto Rotation
D/SContextService( 3524): ===== SContext Service List =====
D/SContextManager( 3524):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@18155f83, service=Auto Rotation
,D/KeyguardViewMediator( 3690): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 3690): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 3690): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 3690): notifyScreenOffLocked
,V/ActivityThread(10257): updateVisibility : ActivityRecord{1a3f9c0f token=android.os.BinderProxy@20a1ee9c {com.example.hello/com.example.hello.MainActivity}} show : true
,D/PowerManagerService( 3524): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 39ms
,D/KeyguardViewMediator( 3690): timeout : 5000
,D/KeyguardViewMediator( 3690): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 3690): handleNotifyScreenOff
,I/CAE     ( 3524): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     ( 3524): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
I/CAE     ( 3524): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager( 3524): SendSensorHubData: send data = -76, 13, -47, 0
,D/Sensorhubs( 2870): sendContextData: -76, 13, -47, 0
,D/InputMethodManagerService( 3524): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService( 3524):   mReceiver.onReceive : ACTION_SCREEN_ON
,I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
,E/MotionRecognitionService( 3524):  handler : SCREEN_ON end
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
I/WifiNative-HAL( 3524): startHal
D/BatteryService( 3524): online:4, current avg:-526, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:159
E/wifi    ( 3524): getStaticLongField sWifiHalHandle 0x8ff2b7fc
D/wifi    ( 3524): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x7020e2
I/WifiNative-HAL( 3524): Could not start hal
D/WifiStateMachine( 3524): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine( 3524): handleScreenStateChanged Exit: true
,D/NotificationService( 3524): ACTION_SCREEN_ON
D/LightsService( 3524): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3524) 
D/LightsService( 3524): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 3524): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 3524): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/WifiStateMachine( 3524): setSuspendOptimizations: 4 false
E/WifiStateMachine( 3524): mSuspendOptNeedsDisabled 4
,D/PowerManagerService( 3524): Excessive delay in ColorFade : initGLShaders: 41ms
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/AudioHardwareTinyALSA( 2859): setParameters(screen_state=on)
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,I/SecExternalDisplayIntents_Java( 3524): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/PowerManagerService( 3524): Excessive delay in ColorFade : draw: 19ms
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PowerManagerService( 3524): Excessive delay in ColorFade : draw: 16ms
,D/IpRemoteDisplayController( 3524): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 3524): Bridge Server is not available
,D/PowerManagerService( 3524): Excessive delay in ColorFade : draw: 19ms
D/PowerManagerService( 3524): Excessive delay in ColorFade prepare: 191ms
D/DisplayPowerController( 3524): ColorFade: onAnimationStart
D/DisplayPowerController( 3524): getFinalBrightness : 87 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/GpsLocationProvider( 3524): receive broadcast intent, action: android.intent.action.SCREEN_ON
,E/GpsLocationProvider( 3524): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:1 ++
E/GpsLocationProvider( 3524): sExerciseIterface is not available
,D/PersonaManagerService( 3524): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 3524): MSG_ACTION_SCREEN_ON called
,D/lights  ( 3524): lcd : 9 +
,D/lights  ( 3524): lcd : 9 -
,I/NfcService( 3959): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 3959): call the applyRouting
,D/lights  ( 3524): lcd : 0 +
D/DisplayPowerController( 3524): getFinalBrightness : 87 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3524): lcd : 0 -
,I/SamsungIME( 4438): getNextShiftState() cursorCapsMode : 0
,D/accuweather( 4997): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 4997): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
D/accuweather( 4997): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 4997): [KK AccuPhone]>>> UIM:281 [0:0] update clock event, is not screen on!!
,D/SSRM:n  ( 3524): SIOP:: AP = 330, PST = 330, CUR = -526
,D/LightsService( 3524): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3524) 
D/LightsService( 3524): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService( 3524): [SvcLED]  onSensorChanged::light value = 50
,D/SensorManager( 3524): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager( 3524): unregisterListener ::   
,D/daemonapp( 3774): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/lights  ( 3524): led_pattern : 5 +
D/BatteryService( 3524): turn on LED for fully charged
D/daemonapp( 3774): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/lights  ( 3524): led_pattern : 5 -
D/LightsService( 3524): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/CAE     ( 3524): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     ( 3524): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     ( 3524): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager( 3524): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs( 2870): sendContextData: -76, 13, -46, 0
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/CAE     ( 3524): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 8, 13, 25,
D/SensorHubManager( 3524): SendSensorHubData: send data = -63, 14, 8, 13, 25
D/Sensorhubs( 2870): sendContextData: -63, 14, 8, 13, 25
,I/ActivityManager( 3524): Waited long enough for: ServiceRecord{28817989 u0 com.samsung.android.MtpApplication/.MtpService}
,D/MotionRecognitionService( 3524):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 3524):  handler : SCREEN_OFF end 
,I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
,D/daemonapp( 3774): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,I/WifiNative-HAL( 3524): startHal
E/wifi    ( 3524): getStaticLongField sWifiHalHandle 0x8ff2b7fc
D/wifi    ( 3524): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0xa013ee
I/WifiNative-HAL( 3524): Could not start hal
D/WifiStateMachine( 3524): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine( 3524): handleScreenStateChanged Exit: false
,D/NotificationService( 3524): ACTION_SCREEN_OFF
D/LightsService( 3524): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3524) 
,D/LightsService( 3524): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 3524): [SvcLED]  onSensorChanged::light value = 50
E/WifiStateMachine( 3524): setSuspendOptimizations: 4 true
E/WifiStateMachine( 3524): mSuspendOptNeedsDisabled 0
,D/comsamsunglog( 3774): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3774): [MSC_Daemon]>>> daemonapp [Version : 15022501 ] [ 3 ] 
,D/comsamsunglog( 3774): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3774): [MSC_Daemon]>>> ====================================================================================================================
D/SensorManager( 3524): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/daemonapp( 3774): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 3774): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/SensorManager( 3524): unregisterListener ::   
D/LightsService( 3524): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AudioHardwareTinyALSA( 2859): setParameters(screen_state=off)
,D/daemonapp( 3774): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 3774): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1447855920000
D/daemonapp( 3774): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1447834405750
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3774): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,I/SecExternalDisplayIntents_Java( 3524): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/daemonapp( 3774): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3774): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 3774): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 3774): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/IpRemoteDisplayController( 3524): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 3524): Bridge Server is not available
,D/VolumePanel( 3690): registerReceiver: onReceive start 
D/VolumePanel( 3690): registerReceiver ACTION_SCREEN_OFF start
D/VolumePanel( 3690): registerReceiver ACTION_SCREEN_OFF end
D/VolumePanel( 3690): registerReceiver: onReceive end 
,D/VolumePanel( 3690): mCoverBroadcastReceiver: onReceive() start : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
D/VolumePanel( 3690): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 3690): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 3690): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 3690): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/GpsLocationProvider( 3524): receive broadcast intent, action: android.intent.action.SCREEN_OFF
E/GpsLocationProvider( 3524): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:0 ++
E/GpsLocationProvider( 3524): sExerciseIterface is not available
,D/PersonaManagerService( 3524): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 3524): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 3959): call the applyRouting
,D/DisplayPowerState( 3524): !@ ColorFade entry
D/DisplayPowerController( 3524): ColorFade: onAnimationEnd
,D/STATUSBAR-PhoneStatusBar( 3690):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 3690): onReceive : Intent.ACTION_SCREEN_OFF
,D/AutomaticBrightnessController( 3524): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController( 3524): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,D/AutomaticBrightnessController( 3524): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/AutomaticBrightnessController( 3524): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
I/Sensors ( 3524): Light old sensor_state 513, new sensor_state : 1 en : 0
I/AutomaticBrightnessController( 3524): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,D/DisplayPowerController( 3524): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 3524): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/SensorManager( 3524): unregisterListener ::   
,I/Sensors ( 3524): Acc old sensor_state 1, new sensor_state : 0 en : 0
I/DisplayManagerService( 3524): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 59.0 fps, supportedRefreshRates [59.0], density 640, 515.154 x 520.192 dpi, appVsyncOff 0, presDeadline 17949152, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager( 3524): Display changed displayId=0
,D/SurfaceFlinger( 2850): Set power mode=0, type=0 flinger=0xb6962000
,D/SensorManager( 3524): unregisterListener ::   
I/hwcomposer( 2850): int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(1)
,D/DisplayPowerController( 3524): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 3524): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 3524): [PWL] sb release: PowerManagerService.Display
,D/accuweather( 4997): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 4997): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 4997): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/SSRM:n  ( 3524): SIOP:: AP = 330, PST = 330, CUR = -526
,D/accuweather( 4997): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 4997): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 4997): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 4997): [KK AccuPhone]>>> UIM:311 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/PowerManagerService( 3524): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 4997): [KK AccuPhone]>>> UIM:157 [0:0] make widget 4x1 view!!! 
,D/accuweather( 4997): [KK AccuPhone]>>> UIM:159 [0:0] make widget 4x2 view!!! 
,D/accuweather( 4997): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
,D/accuweather( 4997): [KK AccuPhone]>>> UIM:184 [0:0] get widget 4x2 view!!! wid = 2
,D/accuweather( 4997): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 4997): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 4997): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/SurfaceControl( 3524): Excessive delay in setPowerMode(): 203ms
D/PowerManagerService( 3524): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL( 3524): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 3524): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,D/PowerManagerService( 3524): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 205ms
I/PowerManagerService( 3524): [PWL] Off : 0s ago
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 35839(2MB) AllocSpace objects, 8(128KB) LOS objects, 24% free, 48MB/64MB, paused 2.230ms total 165.053ms
,I/GAV2    ( 9720): Thread[GAThread,5,main]: No campaign data found.
,D/SSRM:a  ( 3524): DeviceInfo:: 000000100000
D/SSRM:a  ( 3524): SettingsAirViewInfo:: 000000000
,I/GAV2    (10137): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 3524): Killing 9770:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
,W/ProcessCpuTracker( 3524): Skipping unknown process pid 10446
,D/BluetoothAdapter(10257): disable()
,E/BluetoothManagerService( 3524): Bluetooth is already disabled. DO NOT disable again.
,D/WifiService( 3524): New client listening to asynchronous messages
,I/WifiManager(10257): packageName : com.example.hello
,D/SecContentProvider( 3524): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 3524): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3524): mCursor = null
,D/WifiService( 3524): setWifiEnabled: false pid=10257, uid=10402
,E/WifiService( 3524): Invoking mWifiStateMachine.setWifiEnabled
D/SettingsProvider( 3524): name = wifi_on
,I/jxcore-log(10257): ****TEST TOOK:  5068  ms ****
I/jxcore-log(10257): 
,I/jxcore-log(10257): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10257): 
,V/AlarmManager( 3524): waitForAlarm result :4
,D/Finsky  ( 9462): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 4139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 9462): Thread-1222(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
D/AndroidRuntime(10457): 
D/AndroidRuntime(10457): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,I/System.out( 9462): Thread-1222(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 9462): Thread-1222(ApacheHTTPLog):isShipBuild true
I/System.out( 9462): Thread-1222(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/AndroidRuntime(10457): CheckJNI is OFF
,D/AndroidRuntime(10457): readGMSProperty: start
D/AndroidRuntime(10457): readGMSProperty: already setted!!
,D/AndroidRuntime(10457): readGMSProperty: end
D/AndroidRuntime(10457): addProductProperty: start
D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 0 for uid 10031
,I/System.out( 9462): Thread-1222 calls detatch()
,V/GLSActivity( 4139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10475): MountEmulatedStorage()
E/Zygote  (10475): v2
I/libpersona(10475): KNOX_SDCARD checking this for 10014
I/libpersona(10475): KNOX_SDCARD not a persona
,I/SELinux (10475): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10475): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=10475 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,E/SELinux (10475): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10475): TimaSignature is unavailable
,D/ActivityThread(10475): Added TimaKeyStore provider
,E/AffinityControl(10457): AffinityControl: registerfunction enter
,D/ResourcesManager(10475): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/ResourcesManager(10475): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(10475): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/System.out( 9462): Thread-1223 calls detatch()
,W/Finsky  ( 9462): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/AndroidRuntime(10457): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3524): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3524): START PACKAGE DELETE: observer{409042625}
D/PackageManager( 3524): pkg{<packageName>}
D/PackageManager( 3524): user{0}
D/PackageManager( 3524): caller{2000}
D/PackageManager( 3524): flags{3}
D/PersonaManagerService( 3524): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3524): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3524): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3524): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3524): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 3524): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 3524): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 3524): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3524): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3524): !@killApplicatoin: 10402, uninstall pkg
I/ActivityManager( 3524): Force stopping com.example.hello appid=10402 user=-1: uninstall pkg
I/ActivityManager( 3524): Killing 10257:com.example.hello/u0a402 (adj 0): stop com.example.hello
,I/ActivityManager( 3524):   Force finishing activity ActivityRecord{325f89a3 u0 com.example.hello/.MainActivity t24}
,I/SurfaceFlinger( 2850): id=11 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2850): id=11 Removed NainActivit (-2/8)
,D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3524): Skipping PackageSetting{bbfe294 com.test.thalitest/10401} due to missing metadata
,I/ActivityManager( 3524): Force stopping com.example.hello appid=10402 user=0: pkg removed
,D/WifiService( 3524): Client connection lost with reason: 4
,D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/MultiDex(10475): VM with version 2.1.0 has multidex support
I/MultiDex(10475): install
I/MultiDex(10475): VM has multidex support, MultiDex support library is disabled.
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/InputReader( 3524): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
E/SamsungIME( 4438): mOCRHelper is null
W/GeofencerStateMachine( 4274): Ignoring removeGeofence because network location is disabled.
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
I/art     ( 7972): Explicit concurrent mark sweep GC freed 26382(1511KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 2.658ms total 62.356ms
D/LWLocationManager(10307): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(10307): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/Zygote  (10493): MountEmulatedStorage()
,E/Zygote  (10493): v2
I/libpersona(10493): KNOX_SDCARD checking this for 10063
I/libpersona(10493): KNOX_SDCARD not a persona
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/SELinux (10493): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/SELinux (10493): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=10493 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SELinux (10493): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/TimaKeyStoreProvider(10493): TimaSignature is unavailable
,D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,D/ActivityThread(10493): Added TimaKeyStore provider
,D/ResourcesManager(10307): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(10493): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,W/ResourceType( 5115): For resource 0x7f020a0f, entry index(2575) is beyond type entryCount(725)
W/ResourceType( 5115): Failure getting entry for 0x7f020a0f (t=1 e=2575) (error -75)
W/ResourceType( 5115): For resource 0x7f020a62, entry index(2658) is beyond type entryCount(725)
W/ResourceType( 5115): Failure getting entry for 0x7f020a62 (t=1 e=2658) (error -75)
,W/ResourceType( 5115): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5115): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/VRSetupWizardStub/PackageIntentReceiver(10493): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(10493): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(10493): packagename:com.example.hello
,D/ResourcesManager(10307): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,V/JNIHelp (10475): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/ResourcesManager(10307): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,E/Zygote  (10511): MountEmulatedStorage()
E/Zygote  (10511): v2
I/libpersona(10511): KNOX_SDCARD checking this for 10021
I/libpersona(10511): KNOX_SDCARD not a persona
I/SELinux (10511): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10511): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=10511 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
E/SELinux (10511): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(10307): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(10307): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/RegisteredServicesCache( 3959): empty dynamic service
,D/SecContentProvider2( 3524): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3524): mCursor = null
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/TimaKeyStoreProvider(10511): TimaSignature is unavailable
,D/ActivityThread(10511): Added TimaKeyStore provider
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/ActivityThread(10475): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (10475): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@ea599e2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(10475): Installed default security provider GmsCore_OpenSSL
,D/EnterpriseDeviceManagerService( 3524): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 3524): Admin package name: com.google.android.gms
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager(10511): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 20947(1531KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 48MB/64MB, paused 7.463ms total 180.623ms
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/PackageManager( 3524): delete codoeFile: 
D/ResourcesManager(10307): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/AASAUninstall( 3524):  com.example.hello not target!
,D/PackageManager( 3524): result of delete: 1{409042625}
,D/AndroidRuntime(10457): Shutting down VM
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(10307): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,I/KLMS-2.4.521: (10511): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Nov 18 09:13:29 GMT+01:00 2015
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/KLMS-2.4.521: (10511): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3524): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=24, mSplitNum[2]=34 divideNum= 10 r.nextReceiver= 2 receivers.size=44
I/splitIntent( 3524): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(10307): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (10511): KLMSIntentService(): onCreate()
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,I/KLMS-2.4.521: (10511): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/KLMS-2.4.521: (10511): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (10511): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/Zygote  (10531): MountEmulatedStorage()
E/Zygote  (10531): v2
I/libpersona(10531): KNOX_SDCARD checking this for 10106
I/libpersona(10531): KNOX_SDCARD not a persona
,I/SELinux (10531): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=10531 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
I/SELinux (10531): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10531): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/KLMS-2.4.521: (10511): KLMSIntentService(): PACKAGE_REMOVED
,W/ResourcesManager(10307): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10307): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10307): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10307): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (10511): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (10511): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/TimaKeyStoreProvider(10531): TimaSignature is unavailable
D/NativeLibraryUtils(10475): Install completed successfully. count=13 extracted=0
D/ActivityThread(10531): Added TimaKeyStore provider
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,E/Zygote  (10547): MountEmulatedStorage()
E/Zygote  (10547): v2
I/libpersona(10547): KNOX_SDCARD checking this for 10050
I/libpersona(10547): KNOX_SDCARD not a persona
,I/SELinux (10547): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10547): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=10547 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux (10547): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,W/ContextImpl(10054): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,D/ResourcesManager(10307): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ResourcesManager(10531): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/TimaKeyStoreProvider(10547): TimaSignature is unavailable
,D/ActivityThread(10547): Added TimaKeyStore provider
,E/Zygote  (10562): MountEmulatedStorage()
E/Zygote  (10562): v2
I/libpersona(10562): KNOX_SDCARD checking this for 10190
I/libpersona(10562): KNOX_SDCARD not a persona
,I/SELinux (10562): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager(10307): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
I/SELinux (10562): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10562): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourceType( 3524): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/ActivityManager( 3524): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=10562 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager(10307): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/elm:14491(10531): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/elm:14491(10531): ELMEngine.ELMEngine( context ).
,D/elm:14491(10531): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8712(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 880us total 23.011ms
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager(10307): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 727us total 14.920ms
,D/TimaKeyStoreProvider(10562): TimaSignature is unavailable
,D/ActivityThread(10562): Added TimaKeyStore provider
,D/ResourcesManager(10307): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(10547): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 384us total 11.845ms
,D/elm:14491(10531): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14491(10531): ElmAgentService : onCreate()
,D/elm:14491(10531): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/ResourcesManager(10307): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(10547): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(10547): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10547): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10547): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10547): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(10547): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(10547): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(10547): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/elm:14491(10531): MainReceiver.listeningToPackageRemoved()
D/elm:14491(10531): MDMBridge.getInstance()
D/elm:14491(10531): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(10531): MDMBridge.getAllLicenseInfoFromSDK()
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10562): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,I/KLMS-2.4.521: (10511): KLMSIntentService(): listeningToPackageRemoved().END
E/Zygote  (10580): MountEmulatedStorage()
I/libpersona(10580): KNOX_SDCARD checking this for 10019
E/Zygote  (10580): v2
I/libpersona(10580): KNOX_SDCARD not a persona
I/SELinux (10580): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10580): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10580): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=10580 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/ResourcesManager(10307): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,I/TapandpayWidget:TanpandpayAppWidgetProvider(10562): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(10562): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,I/TapandpayWidget:Utils(10562): Clear T&P info.
,D/elm:14491(10531): ElmAgentService : onDestroy().
,I/KLMS-2.4.521: (10511): KLMSIntentService(): onDestroy()
D/TimaKeyStoreProvider(10580): TimaSignature is unavailable
,D/ResourcesManager(10307): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ActivityThread(10580): Added TimaKeyStore provider
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/TapandpayWidget:TanpandpayAppWidgetProvider(10562): Widget is not attached.
,E/Zygote  (10596): MountEmulatedStorage()
I/libpersona(10596): KNOX_SDCARD checking this for 10116
E/Zygote  (10596): v2
I/libpersona(10596): KNOX_SDCARD not a persona
,I/SELinux (10596): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10596): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10596): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=10596 uid=10116 gids={50116, 9997, 1023} abi=armeabi-v7a
,D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/TimaKeyStoreProvider(10596): TimaSignature is unavailable
D/ResourcesManager(10307): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ActivityThread(10596): Added TimaKeyStore provider
,W/ResourcesManager( 3524): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3524): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3524): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3524): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(10580): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/Books/Books.apk
,D/RCPManagerService( 3524): PackageReceiver onReceive()
,I/HarmonyEASService( 3524): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3524): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3524): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 3524): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 3524): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3524): uID is 10402
V/EnterpriseBillingPolicy( 3524): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3524): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3524): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3524): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3524): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3524): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 3524): getBillingProfileForVpnEngine - end - null
,D/com.sec.android.service.health.upgrade.UninstallReceiver(10580): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(10580): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver(10580): onReceive() : package name is not s health. Return !!!
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager(10596): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
I/ActivityManager( 3524): Killing 9786:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/TaskPersister( 3524): removeObsoleteFile: deleting file=24_task.xml
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  (10617): MountEmulatedStorage()
E/Zygote  (10617): v2
I/libpersona(10617): KNOX_SDCARD checking this for 1000
I/libpersona(10617): KNOX_SDCARD not a persona
,I/SELinux (10617): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/PackageManager( 3524): findPreferredActivity: No PreferredActivities set
,I/SELinux (10617): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=10617 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (10617): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,I/ActivityManager( 3524): Killing 9801:com.sec.pcw.device/1000 (adj 15): bgCount ##31
,D/UsbSettingsManager( 3524): clearDefaults: com.example.hello
I/CrashAnrDetector( 3524): onPackageRemoved : com.example.hello
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/LocationWidgetApplication(10307): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/NearbySource(10547): Nearby Source Create!
E/SQLiteLog(10596): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
D/NearbyContext(10547): Nearby Context Create!
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(10617): TimaSignature is unavailable
D/ResourcesManager(10307): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
E/SQLiteDatabase(10596): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase(10596): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10596): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10596): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10596): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10596): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10596): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10596): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10596): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10596): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10596): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(10596): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteDatabase(10596): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(10596): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(10596): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(10596): 	at android.os.Binder.execTransact(Binder.java:446)
,E/SQLiteOpenHelper(10596): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper(10596): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(10596): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(10596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(10596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(10596): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(10596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(10596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(10596): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(10596): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(10596): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(10596): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(10596): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(10596): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(10596): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(10596): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteOpenHelper(10596): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteOpenHelper(10596): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteOpenHelper(10596): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteOpenHelper(10596): 	at android.os.Binder.execTransact(Binder.java:446)
D/ActivityThread(10617): Added TimaKeyStore provider
,W/SQLiteOpenHelper(10596): Opened filter.db in read-only mode
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,E/SQLiteLog(10596): (284) automatic index on titles(filter_id)
,D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3524): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3524): displayNotification : [0ah,00h,00h]
,E/Zygote  (10634): MountEmulatedStorage()
E/Zygote  (10634): v2
I/libpersona(10634): KNOX_SDCARD checking this for 10114
I/libpersona(10634): KNOX_SDCARD not a persona
D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3524): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3524): displayNotification : [0ah,00h,01h]
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
I/SELinux (10634): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.facebook.katana:dash for broadcast com.facebook.katana/com.facebook.dash.receivers.DashPackageUninstallReceiver: pid=10634 uid=10114 gids={50114, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/UsbHostManager( 3524): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3524): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
,D/UsbSettingsManager( 3524): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,I/SELinux (10634): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10634): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ContextImpl(10547): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(10547): Samsung link source created
,D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3524): displayNotification : [09h,00h,00h]
,E/ActivityThread( 9509): Failed to find provider info for com.facebook.appmanager.installrecord
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,I/ActivityManager( 3524): Killing 9340:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): bgCount ##31
,E/JavaBinder( 3524): !!! FAILED BINDER TRANSACTION !!!
,W/BroadcastQueue( 3524): Exception when sending broadcast to ComponentInfo{com.sec.pcw.device/com.sec.pcw.device.receiver.SYSTEMReceiver}
W/BroadcastQueue( 3524): android.os.TransactionTooLargeException
W/BroadcastQueue( 3524): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 3524): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue( 3524): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:947)
W/BroadcastQueue( 3524): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:292)
W/BroadcastQueue( 3524): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1173)
W/BroadcastQueue( 3524): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:192)
W/BroadcastQueue( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/BroadcastQueue( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue( 3524): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/TimaKeyStoreProvider(10634): TimaSignature is unavailable
,D/ActivityThread(10634): Added TimaKeyStore provider
D/ResourcesManager(10307): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,E/Zygote  (10654): MountEmulatedStorage()
E/Zygote  (10654): v2
I/libpersona(10654): KNOX_SDCARD checking this for 1000
I/libpersona(10654): KNOX_SDCARD not a persona
,I/SELinux (10654): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10654): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=10654 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (10654): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(10307): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/UsbHostManager( 3524): usbDeviceRemoved : /dev/bus/usb/001/001
,E/UsbHostManager( 3524): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,D/ResourcesManager(10307): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/EventHub( 3524): Removing device '/dev/input/event10' due to inotify event
,D/ResourcesManager(10307): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager(10617): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
,D/TimaKeyStoreProvider(10654): TimaSignature is unavailable
,D/ActivityThread(10654): Added TimaKeyStore provider
,E/SQLiteLog(10547): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,D/ResourcesManager(10307): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,E/SQLiteDatabase(10547): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(10547): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10547): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10547): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10547): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10547): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10547): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10547): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10547): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10547): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10547): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10547): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10547): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10547): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10547): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(10547): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(10547): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(10547): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(10547): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(10547): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(10547): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(10547): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(10547): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(10547): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(10547): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10547): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10547): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(10547): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(10547): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(10547): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(10547): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(10547): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(10547): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(10547): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(10547): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(10547): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(10547): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(10547): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(10547): 	at android.database.sqlite.SQLiteConne,ctionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(10547): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(10547): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(10547): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(10547): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(10547): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(10547): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(10547): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(10547): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(10547): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(10547): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(10547): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(10547): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(10547): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(10547): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(10547): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(10547): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(10547): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(10547): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(10547): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(10547): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(10547): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(10547): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(10547): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(10547): Opened local.db in read-only mode
,I/EventHub( 3524): Removing device '/dev/input/event7' due to inotify event
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ContextImpl(10617): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2994 
,I/EventHub( 3524): Removing device '/dev/input/event8' due to inotify event
,D/ResourcesManager(10634): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
D/ResourcesManager(10475): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ContactProvider(10547): getAllContactInfoList Start
,I/EventHub( 3524): Removing device '/dev/input/event9' due to inotify event
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog(10617): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10617): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase(10617): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10617): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10617): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10617): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10617): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10617): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10617): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10617): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10617): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10617): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10617): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/SQLiteDatabase(10617): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
E/SQLiteDatabase(10617): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase(10617): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10617): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10617): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime(10617): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime(10617): Process: com.android.keychain, PID: 10617
E/AndroidRuntime(10617): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10617): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(10617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(10617): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(10617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(10617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(10617): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(10617): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(10617): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(10617): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(10617): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(10617): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(10617): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(10617): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/AndroidRuntime(10617): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:55,4)
E/AndroidRuntime(10617): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime(10617): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10617): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10617): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ResourcesManager(10654): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/EventHub( 3524): Removing device '/dev/input/event11' due to inotify event
,E/Zygote  (10672): MountEmulatedStorage()
,E/Zygote  (10672): v2
I/libpersona(10672): KNOX_SDCARD checking this for 1000
,I/libpersona(10672): KNOX_SDCARD not a persona
,I/SELinux (10672): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=10672 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (10672): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10672): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.android.keychain
W/ResourcesManager(10634): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/PCWCLIENTTRACE_LOG(10654): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(10654): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(10654): new DMDBOpenHelper instance
,E/SQLiteLog(10654): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10654): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(10654): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10654): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10654): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10654): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10654): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10654): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10654): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10654): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10654): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10654): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10654): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase(10654): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(10654): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(10654): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(10654): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(10654): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(10654): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(10654): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(10654): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10654): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10654): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(10654): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(10654): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(10654): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(10654): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(10654): Shutting down VM
,E/AndroidRuntime(10654): FATAL EXCEPTION: main
E/AndroidRuntime(10654): Process: com.sec.pcw.device, PID: 10654
E/AndroidRuntime(10654): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10654): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(10654): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(10654): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(10654): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(10654): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(10654): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10654): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10654): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(10654): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(10654): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(10654): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(10654): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(10654): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10654): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(10654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(10654): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(10654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(10654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(10654): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(10654): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(10654): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(10654): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(10654): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(10654): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(10654): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(10654): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime(10654): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(10654): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(10654): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(10654): 	... 11 more
,I/EventHub( 3524): Removing device '/dev/input/event12' due to inotify event
,I/ActivityManager( 3524): Killing 8884:com.sec.android.app.shealth/u0a36 (adj 13): bgCount ##31
,V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,E/DropBoxManagerService( 3524): Can't write: system_app_crash
E/DropBoxManagerService( 3524): java.io.FileNotFoundException: /data/system/dropbox/drop181.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3524): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3524): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3524): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3524): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3524): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3524): 	... 5 more
I/EventHub( 3524): Removing device '/dev/input/event13' due to inotify event
,I/Process (10617): Sending signal. PID: 10617 SIG: 9
,D/TimaKeyStoreProvider(10672): TimaSignature is unavailable
,D/ActivityThread(10672): Added TimaKeyStore provider
E/DropBoxManagerService( 3524): Can't write: system_app_crash
E/DropBoxManagerService( 3524): java.io.FileNotFoundException: /data/system/dropbox/drop182.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3524): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3524): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3524): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3524): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3524): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3524): 	... 5 more
D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,I/art     (10475): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/art     (10475): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,E/Zygote  (10690): MountEmulatedStorage()
E/Zygote  (10690): v2
I/libpersona(10690): KNOX_SDCARD checking this for 10035
I/libpersona(10690): KNOX_SDCARD not a persona
,I/SELinux (10690): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10690): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/AndroidRuntime(10634): Shutting down VM
,I/ActivityManager( 3524): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=10690 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/AndroidRuntime(10634): FATAL EXCEPTION: main
E/AndroidRuntime(10634): Process: com.facebook.katana:dash, PID: 10634
E/AndroidRuntime(10634): java.lang.RuntimeException: Unable to instantiate application com.facebook.katana.app.FacebookApplication: java.lang.RuntimeException: java.io.FileNotFoundException: /data/data/com.facebook.katana/libs-dir-lock: open failed: EROFS (Read-only file system)
E/AndroidRuntime(10634): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:625)
E/AndroidRuntime(10634): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5088)
E/AndroidRuntime(10634): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(10634): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(10634): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10634): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10634): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(10634): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(10634): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(10634): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(10634): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(10634): Caused by: java.lang.RuntimeException: java.io.FileNotFoundException: /data/data/com.facebook.katana/libs-dir-lock: open failed: EROFS (Read-only file system)
E/AndroidRuntime(10634): 	at com.facebook.sosource.FBSoLoader.a(FBSoLoader.java:66)
E/AndroidRuntime(10634): 	at com.facebook.base.app.DelegatingApplication.attachBaseContext(DelegatingApplication.java:81)
E/AndroidRuntime(10634): 	at android.app.Application.attach(Application.java:205)
E/AndroidRuntime(10634): 	at android.app.Instrumentation.newApplication(Instrumentation.java:1004)
E/AndroidRuntime(10634): 	at android.app.Instrumentation.newApplication(Instrumentation.java:988)
E/AndroidRuntime(10634): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:620)
E/AndroidRuntime(10634): 	... 10 more
E/AndroidRuntime(10634): Caused by: java.io.FileNotFoundException: /data/data/com.facebook.katana/libs-dir-lock: open failed: EROFS (Read-only file system)
E/AndroidRuntime(10634): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/AndroidRuntime(10634): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/AndroidRuntime(10634): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/AndroidRuntime(10634): 	at com.facebook.soloader.FileLocker.<init>(FileLocker.java:20)
E/AndroidRuntime(10634): 	at com.facebook.soloader.FileLocker.a(FileLocker.java:16)
E/AndroidRuntime(10634): 	at com.facebook.soloader.SysUtil.a(SysUtil.java:215)
E/AndroidRuntime(10634): 	at com.facebook.sosource.DirectorySoSourceWithAssets.a(DirectorySoSourceWithAssets.java:69)
E/AndroidRuntime(10634): 	at com.facebook.sosource.FBSoLoader.a(FBSoLoader.java:63)
E/AndroidRuntime(10634): 	... 15 more
E/AndroidRuntime(10634): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/AndroidRuntime(10634): 	at libcore.io.Posix.open(Native Method)
E/AndroidRuntime(10634): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/AndroidRuntime(10634): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/AndroidRuntime(10634): 	... 22 more
E/SELinux (10690): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/EventHub( 3524): Removing device '/dev/input/event14' due to inotify event
,I/Process (10654): Sending signal. PID: 10654 SIG: 9
,V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.facebook.katana:dash
,E/lowmemorykiller( 2828): Error writing /proc/10654/oom_score_adj; errno=22
,D/MtpClient(10547): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(10547): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,E/SharedPreferencesImpl(10547): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,E/DropBoxManagerService( 3524): Can't write: system_app_crash
E/DropBoxManagerService( 3524): java.io.FileNotFoundException: /data/system/dropbox/drop183.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3524): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3524): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3524): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3524): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3524): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3524): 	... 5 more
,D/ResourcesManager(10672): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,I/ActivityManager( 3524): Killing 9818:com.policydm/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10690): TimaSignature is unavailable
,D/ActivityThread(10690): Added TimaKeyStore provider
,I/ActivityManager( 3524): Process com.android.keychain (pid 10617)(adj 5) has died(151,1267)
,W/ActivityManager( 3524): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,D/ResourcesManager(10475): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk

```
